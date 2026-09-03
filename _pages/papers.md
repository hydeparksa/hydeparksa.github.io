---
layout: archive
title: "Publications"
permalink: /papers/
author_profile: true

---
## Book projects 

{% for pub in site.data.books %}
- **{{ pub.title }}**<br>
{{ pub.authors }}, {{ pub.year }}
[[link]({{ pub.url }})].
{% endfor %}

## Preprints 

{% for pub in site.data.preprints %}
- **{{ pub.title }}**<br>
{{ pub.authors }}<br>
_arxiv:{{ pub.arxiv }}_, {{ pub.year }}.
[[arXiv]({{ pub.url }})]
{% endfor %}


## Published

{% for pub in site.data.published %}
- **{{ pub.title }}**<br>
{{ pub.authors }}<br>
_{{ pub.journal }}_, {{ pub.year }}.
[[Journal]({{ pub.url }})] [[arXiv]({{ pub.arxiv_url}})] [[MathSciNet]({{ pub.mathscinet_url }})] [[zbMATH]({{ pub.zbmath_url }})]


{% endfor %}
