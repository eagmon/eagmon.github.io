---
layout: page
title: Selected Publications
permalink: /publications/
---

{% for publication in site.data.publications %}
1. **{{ publication.authors }}** ({{ publication.year }}). {{ publication.title }} _{{ publication.journal }}_. [Available here]({{ publication.link }})
{% endfor %}
