---
title: Human
layout: page
characteristics:
  Health: 20
  Auramancy : false
  Empty-Handed: "-2"
  Throwing: "+1"
  Two-Handed: "+1"
---
Generic

## Characteristics
{% for characteristic in page.characteristics %}
{% if characteristic[1] == false %}- {{characteristic[0]}} Forbidden{% else %}- {{characteristic[0]}} {{characteristic[1]}}{% endif %}{% endfor %}
<!--Sorry for the ugliness above. Shitty spacing in the list happens otherwise for some reason.  -->
