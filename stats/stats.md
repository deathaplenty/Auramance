---
title: Stats
layout: page
categories: navbar
permalink: /stats
---

Stats are the physical attributes of a player. These are fixed upon player creation and rarely change.

Stats range from 1-10 and cannot be pushed below 1 or above 10


{% for page in site.pages%}
  {% if page.categories == "stats"%}
[{{page.title}}]({{ site.baseurl }}{{ page.url }})
  {%endif%}
{%endfor%}
