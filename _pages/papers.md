---
layout: archive
title: "Papers"
permalink: /papers/
author_profile: true

---

## Preprints 

{% for pub in site.data.preprints %}
- **{{ pub.title }}**
{{ pub.authors }}
_{{ pub.journal }}_, {{ pub.year }}.
[Link]({{ pub.url }})
{% endfor %}


## Published

{% for pub in site.data.published %}
- **{{ pub.title }}**<br>
{{ pub.authors }}<br>
_{{ pub.journal }}_, {{ pub.year }}.
[Link]({{ pub.url }})
{% endfor %}