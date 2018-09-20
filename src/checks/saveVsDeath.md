---
title: Save Vs Death
savingThrow: true
formula: "D20 >= 21 - FLOOR((Body + Spirit)/2)"
---
Any time a character would take lethal damage, they may make a saving throw vs death. If it is successful, the character is reduced to 1 health. If it is unsuccessful, the user takes damage as normal.

## Affected by
- [Body]({{site.baseurl}}{%link _attributes/body.md %}) and [Spirit]({{site.baseurl}}{%link _attributes/spirit.md %})
  - Subtract the floored average of these two stats from the base (21)

## Formula
{{page.formula}}
