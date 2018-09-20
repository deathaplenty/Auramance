---
layout: page
title: Skills
navbar: true
permalink: /skills
---
This game works on a skill-based system. Each skill ranges from 0-10, where 0 means you have absolutely no ability to perform said skill and 10 means that you are a master of that skill.

If a skill has a 0 value, it cannot be increased via level up until the character makes attempts at learning the basics.

## Skill List
### Magic
{% for page in site.skills %}
  {% if page.magic %}
[{{page.title}}]({{site.baseurl}}{{page.url}})
  {% endif %}
{% endfor %}

### Melee
{% for page in site.skills %}
  {% if page.melee %}
[{{page.title}}]({{site.baseurl}}{{page.url}})
  {% endif %}
{% endfor %}

### Ranged
{% for page in site.skills %}
  {% if page.ranged %}
[{{page.title}}]({{site.baseurl}}{{page.url}})
  {% endif %}
{% endfor %}
### Defense
{% for page in site.skills %}
  {% if page.defense %}
[{{page.title}}]({{site.baseurl}}{{page.url}})
  {% endif %}
{% endfor %}

### Utility
{% for page in site.skills %}
  {% if page.utility %}
[{{page.title}}]({{site.baseurl}}{{page.url}})
  {% endif %}
{% endfor %}


## Learning new skills
 So you want to pick up a skill you have no ability for. To go about this, a character must successfully use that skill 10 times. After that, they may allot a skill point in a level 0 skill and level it up as normal afterwards.

## Rolls and Checks
Typically one skill will be used offensively and another will be used in defense of that. An example might be one-handed and evasion. This is how rolls typically go:

## Base Rules
- Both parties in a conflict roll a d20 and add their respective offense and defense bonuses
- The party that rolls highest, wins
- break ties with another roll

In our our example, let's say a character with 1 point of one-handed skill swings a sword at a character with 1 point of dodge skill. Both characters roll a d20 and add 1 to their roll. If the defensive party rolls higher, they dodge. If the offensive party rolls higher, they hit.
