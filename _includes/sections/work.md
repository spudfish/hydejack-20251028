<!-- WORK SECTION WRAPPER -->
<section id="work" class="section section--work anchor">

  <!-- SUBSECTION HEADING 1 of 2: Selected Work -->
  <h2>Work</h2>

  <!-- LOOP: Render each Top Work item (collection: top-work) -->
  {% assign items = site["top-work"] | sort: "order" %}
  {% for i in items %}

    {% include top-work.html
       title=i.title
       desc=i.desc
       call_to_action=i.call_to_action
       image_file=i.image_file
       image_link=i.image_link
       image_alt=i.image_alt
    %}
  {% endfor %}

  <!-- SUBSECTION HEADING 2 of 2: Other Work -->
  <h2>Other Work</h2>

  <!-- INCLUDE: Other Work grid wrapper (loops _other-work collection) -->
  {% include sections/other-work.html %}

</section>
<!-- [END WORK SECTION WRAPPER] -->
