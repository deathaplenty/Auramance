{% for page in site.pages %}
  {% for category in page.categories %}
    {% if category == {{include.category}} %}
[{{page.title}}]({{ site.baseurl }}{{ page.url }})
    {% endif %}
  {% endfor %}
{% endfor %}
