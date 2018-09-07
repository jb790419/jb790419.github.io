---
layout: post
title: Kandidáti
permalink: kandidati
menu: true
order: 1
author: abcd
addons: related
description: >
  Kandidátka Otevřené radnice pro komunální volby v Chocni,
  které se konají 5. a 6. října 2018
---
![](/assets/img/people.png)

{% for author_key in site.data.authors %}
{% assign author = author_key[1] %}
{% include components/author.html author=author heading=author.name heading_tag='h2' %}
{% endfor %}
