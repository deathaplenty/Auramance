---
title: Spells
layout: page
ability: true
permalink: /spells/
---

Spells are a structured and formulaic way to use magical energies. If you have any auramancy capability, then you can use spells directly. If you're more of the kind of adventurer to ask for the aid of the magical creatures nearby (consultation), You will be choosing the spells they can use. The required Auramancy level is also the amount of mana a spell costs. Don't expect strong spells in the early game.
## Offensive
{% for page in site.spells %}
  {% if page.offense %}
[{{page.title}}]({{site.baseurl}}{{page.url}})
  {% endif %}
{% endfor %}
## Defensive
{% for page in site.spells %}
  {% if page.defense %}
[{{page.title}}]({{site.baseurl}}{{page.url}})
  {% endif %}
{% endfor %}
## Utility
{% for page in site.spells %}
  {% if page.utility %}
[{{page.title}}]({{site.baseurl}}{{page.url}})
  {% endif %}
{% endfor %}