---
title: Checks
layout: page

---

When rolling dice, a check is a value that you must either meet or beat (your roll has to be greater than or equal to the check).
Positive modifiers reduce this value, making it easier to succeed.

{% for page in site.checks %}
  {% if page.check %}
[{{page.title}}]({{site.baseurl}}{{ page.url }})
  {% endif %}
{% endfor %}
