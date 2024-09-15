---
layout: archive
title: "Conferences and workshops I helped to organize:"
permalink: /conferences/
author_profile: true

---
<br>
{% for conf in site.data.conferences %}
- **{{ conf.name }}**<br>
organized with: {{ conf.organizers }}<br>
{{ conf.location }}, {{ conf.date }}.
[[Link]({{ conf.url }})]
{% endfor %}


