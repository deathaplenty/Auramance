---
title: Attributes
layout: page
navbar: true
permalink: /attributes
---

Attributes measure core features of a character or creature. These values are fixed upon character or creature creation and rarely change.

Attributes range from 1-10. If an attribute is pushed below 1, the character loses the ability to act. An attribute can be pushed above 10 via equipment or effects.


{% for page in site.attributes %}
[{{page.title}}]({{site.baseurl}}{{ page.url }})
{% endfor %}
