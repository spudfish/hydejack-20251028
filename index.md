---
title: Tal McThenia
permalink: "/"
layout: default
subtitle: Writer
---

{% capture fullpage %}
  {% include sections/work.md %}
  {% include sections/bio.md %}
  {% include sections/contact.md %}
{% endcapture %}

{{ fullpage
   | markdownify
   | replace: '<a href="http', '<a target="_blank" rel="noopener" href="http' }}
