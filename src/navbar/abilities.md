---
title: Abilities
layout: page
navbar: true
permalink: /abilities
---
Abilities are a generic term for any action a character can take such as casting spells or playing songs. Below are links to respective ability categories.


{% for page in site.abilities %}
[{{page.title}}]({{site.baseurl}}{{ page.url }})
{% endfor %}
