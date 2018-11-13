---
title: Species
layout: page
navbar: true
permalink: /species/
---
This is an exhaustive list of all species in the game

{% for page in site.species %}
[{{page.title}}]({{site.baseurl}}{{ page.url }})
{% endfor %}
