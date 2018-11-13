---
title: Elf
layout: page
characteristics:
  Health: 16
  Mind: "+1"
  Body: "-2"
  Spirit: "+1"
  Auramancy: "+1"
  Archery: "+1"
  Two-Handed: "-1"
---
Fae

## Characteristics
{% for characteristic in page.characteristics %}
{% if characteristic[1] == false %}- {{characteristic[0]}} Forbidden{% else %}- {{characteristic[0]}} {{characteristic[1]}}{% endif %}{% endfor %}
<!--Sorry for the ugliness above. Shitty spacing in the list happens otherwise for some reason.  -->




## Lore
Elves do not generally care for other humanoid species. During the rise of humans in the northern forests, elves chose to distance themselves and relocated to a desert oasis near the equator. Elves are still fair-skinned despite their desert habitat due to their genetic approach to preventing harmful sun damage. An Elf's skin is naturally reflective of high frequency light, giving them a very slight blue-violet tint over their alabaster skin tone.
