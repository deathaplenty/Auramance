---
title: Sciuridin
layout: page
characteristics:
  Health: "5"
  Body: "-5"
  Movement: "+10"
  Athletics: "+3 when used for climbing"
  Evasion: "+5"
---
Very small squirrel humanoids. They're small (about 40 centimeters tall, or 1/4 the size of the average human) and fast, and some are even capable of speech.

## Available Magic
- Consultation


## Characteristics
{% for characteristic in page.characteristics %}
{% if characteristic[1] == false %}- {{characteristic[0]}} Forbidden{% else %}- {{characteristic[0]}} {{characteristic[1]}}{% endif %}{% endfor %}
<!--Sorry for the ugliness above. Shitty spacing in the list happens otherwise for some reason.  -->
