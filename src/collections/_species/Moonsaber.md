---
title: Moonsaber
layout: page
characteristics:
  Powerful Senses:
  Body: "+2"
  Spirit: "-2"
  Auramancy: false
  Archery: "-2"
---
Moonsabers, called "Moonsaber clan" by some, are a race of beings that are born as large cat animals akin to tigers, but they can take a humanoid form permanently once they reach a mature age and undergo a "ritual." The resulting humanoid is that of a human with pointed, furry ears and razor sharp teeth. This process is irreversable and undergoing it strips the moonsaber of their ability to reproduce and their ability to harm etherials with normal attacks.


## Characteristics
{% for characteristic in page.characteristics %}
{% if characteristic[1] == false %}- {{characteristic[0]}} Forbidden{% else %}- {{characteristic[0]}} {{characteristic[1]}}{% endif %}{% endfor %}
<!--Sorry for the ugliness above. Shitty spacing in the list happens otherwise for some reason.  -->

### Characteristics for Tiger Form
- Moonfangs
  - Can damage etherials.
- Can't use equipment
- Can't speak
