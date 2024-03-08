---
JDR: OSE
Type:
  - core

tags:
  - monster
statblock: inline
---
# Berserker

------
```statblock
layout: OSE
name: Berserker
subtype: "Guerrier qui entre en rage pendant le combat. Il ne fait jamais de prisonniers."
image:
alignement: Neutre
ac: 7(12)
hp: 5
hit_dice: 1D8+1
thaco: 18(+1)
speed: 36m (12m)
jds: [12, 13, 14, 15, 16, (1)]
roll_jds: 1d20
moral: 12
roll-moral: 2d6
xp: "19"
nbr: 1d6
nbr_dj: 3d10
loot: [[2. Types de trésors#Type U (160 po en moyenne)|U]] ([[2. Types de trésors#Type B (2 000 po en moyenne)|B]])
forceColumns: true
columns: 1
traits:
  - name: Rage de bataille 
    desc: "Bonus de +2 à l’attaque contre les humains et humanoïdes similaires (par exemple, orques, gobelins, etc.). La rage le pousse parfois à attaquer ses alliés."
  - name: Butin
    desc: "Ne possède qu’un trésor de type B lorsqu’on le rencontre dans les contrées sauvages."
actions:
  - name: 1x arme
    desc: D20 jet d'attaque, 2 (1d8) de dégâts ou selon arme
source: OSE
```
---