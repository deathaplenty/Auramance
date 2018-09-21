---
title: Saving Throws
layout: page
mechanic: true
check: true
---
Saving throws are checks to specifically avoid some outcome.

{% for page in site.checks %}
  {% if page.savingThrow %}
[{{page.title}}]({{site.baseurl}}{{ page.url }})
  {% endif %}
{% endfor %}
