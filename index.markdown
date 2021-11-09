---
title: Gallery index
layout: index
---

{% for exhibit in site.exhibits %}

<img src="{{ exhibit.image-url }}" width= 256>
<p>{{ exhibit.title }} by {{ exhibit.creator }}</p>
<p><a herf="{{ exhibit.lincece-url }}"> {{ exhibit.licence }}</a></p>

{% endfor %}