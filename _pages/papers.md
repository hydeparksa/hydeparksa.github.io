---
layout: archive
title: "Papers"
permalink: /papers/
author_profile: true

---

## Preprints 

{% for pub in site.data.preprints %}
- **{{ pub.title }}**<br>
{{ pub.authors }}<br>
_arxiv:{{ pub.arxiv }}_, {{ pub.year }}.
[ArXiv]({{ pub.url }})
{% endfor %}


## Published

{% for pub in site.data.published %}
- **{{ pub.title }}**<br>
{{ pub.authors }}<br>
_{{ pub.journal }}_, {{ pub.year }}.
[Journal]({{ pub.url }})
{% endfor %}

