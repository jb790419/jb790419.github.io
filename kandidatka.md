---
layout: default
title: Kandidatka
---

## <a name="content"></a> Kandidátní listina

{% for kandidat in site.data.kandidati %}
1. {{ kandidat.jmeno }} {{kandidat.prijmeni}}, {{kandidat.vek}} let, {{kandidat.povolani}}
{% endfor %}
