{% for page in site.pages %}
    {% if page[{{include.type}}] %}
[{{page.title}}]({{ site.baseurl }}{{ page.url }})
    {% endif %}
{% endfor %}
