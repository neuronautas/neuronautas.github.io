---
title: Álbum
layout: single
permalink: /showcase/
---

{% for page in site.showcase %}
{% if page.layout == "single" %}
[{{ page.title }}]({{ page.url | prepend: site.baseurl }})
{% endif %}
{% endfor %}