---
layout: post
title: Kandidáti
permalink: kandidati
menu: true
order: 1
author: abcd
addons: related
description: >
  Kandidátka Otevřené radnice pro komunální volby v Chocni 5.&nbsp;a&nbsp;6.&nbsp;října&nbsp;2018
---
![](/assets/img/people.png)

{% for author_key in site.data.authors %}
{% assign author = author_key[1] %}
{% include components/author.html author=author heading=author.name heading_tag='h2' %}
{% endfor %}
