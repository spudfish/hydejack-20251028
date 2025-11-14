---
layout: default_noarticle
title: Tal McThenia
permalink: "/"
subtitle: Writer
redirect_from:
  - /in-the-works/
  - /more-works/
---

{% capture fullpage %}
{% include sections/work.md %}
{% include sections/bio.md %}
{% include sections/contact.md %}
{% endcapture %}

{{ fullpage
   | markdownify
   | replace: '<a href="http', '<a target="_blank" rel="noopener" href="http' }}
