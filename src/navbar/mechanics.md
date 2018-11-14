---
title: Mechanics
layout: page
navbar: true
permalink: /mechanics
---
This is a landing page for all game mechanics.
{% for page in site.mechanics %}
[{{page.title}}]({{site.baseurl}}{{ page.url }})
{% endfor %}
