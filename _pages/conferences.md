---
layout: archive
title: "Conferences organized"
permalink: /conferences/
author_profile: true

---


{% for conf in site.data.conferences %}
- **{{ conf.name }}**<br>
organized with: {{ conf.organizers }}<br>
{{ conf.location }}, {{ conf.date }}.
[[Link]({{ conf.url }})]
{% endfor %}


