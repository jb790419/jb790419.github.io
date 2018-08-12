---
layout: default
---

# Kandidátní listina

{% for kandidat in site.data.kandidati %}
1. {{ kandidat.jmeno }} {{kandidat.prijmeni}}, {{kandidat.vek}}, {{kandidat.povolani}}
{% endfor %}
