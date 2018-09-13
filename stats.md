---
  layout: page
  title: Stats
  permalink: /stats
  categories: navbar
---

This is where all of our stats are!

{% for page in site.pages%}
  {% if page.categories == "stats"%}
[{{page.title}}]({{ site.baseurl }}{{ page.url }})
  {%endif%}
{%endfor%}
