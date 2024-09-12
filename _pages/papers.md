---
layout: archive
title: "Papers"
permalink: /papers/
author_profile: true

---

## Preprints 

{% for pub in site.data.preprints %}
- <small>**{{ pub.title }}**
{{ pub.authors }}
_{{ pub.journal }}_, {{ pub.year }}.
[Link]({{ pub.url }})</small>
{% endfor %}


## Published

{% for pub in site.data.published %}
- <small>**{{ pub.title }}**<br>
{{ pub.authors }}<br>
_{{ pub.journal }}_, {{ pub.year }}.
[Link]({{ pub.url }})</small>
{% endfor %}

