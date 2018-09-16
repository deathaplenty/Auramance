---
title: Attributes
layout: page
categories: navbar
permalink: /attributes
---

Attributes measure core features of a character or creature. These values are fixed upon character or creature creation and rarely change.

Attributes range from 1-10 and cannot be pushed below 1 or above 10


{% for page in site.pages%}
  {% if page.categories == "attributes"%}
[{{page.title}}]({{ site.baseurl }}{{ page.url }})
  {%endif%}
{%endfor%}
