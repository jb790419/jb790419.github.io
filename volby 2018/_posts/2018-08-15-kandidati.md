---
layout: post
title: Kandidáti
permalink: kandidati
menu: true
order: 1
description: >
  Kandidátka Otevřené radnice pro komunální volby v Chocni,
  které se konají 5. a 6. října 2018
---
![](/assets/img/people.png)

{% for kandidat in site.data.kandidati %}
1. {{ kandidat.jmeno }} {{kandidat.prijmeni}}, {{kandidat.vek}} let, {{kandidat.povolani}}
{% endfor %}
