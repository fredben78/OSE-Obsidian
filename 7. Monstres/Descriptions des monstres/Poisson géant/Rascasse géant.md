---
JDR: OSE
Type:
  - core
share: true
tags:
  - monster
statblock: inline
---
# `=this.file.name`


---
```statblock
layout: OSE
name: Rascasse géante
subtype: "Poisson épineux à la peau grumeleuse et rocailleuse. Vit dans les eaux salées peu profondes. Normalement passif, devient très agressif s’il est dérangé."
image:
alignement: Neutre
ac: 7(12)
hp: 3
hit_dice: 5D8+5
thaco: 14 (+5)
speed: 54m (18m)
jds: [12,13,14,15,16,(3)]
roll_jds: 1d20
roll-moral: 2d6
moral: 8
xp: "400"
nbr: 0 
nbr_dj: 2d4
loot: Aucun
traits:
  - name: Camouflage
    desc: "70 % 50 (1d100) de chances d’être confondu avec une formation rocheuse ou corallienne."
  - name: Saisir 
    desc: "S’il est saisi à pleines mains, le confondant avec un rocher ou une pierre, les 4 attaques d’épines touchent automatiquement."
  - name: Poison
    desc: "Provoque la mort (jet de sauvegarde contre le poison)."
actions:
  - name: 4x Epines
    desc: D20 jet d'attaque, 2 (1d4) de dégâts + poison
source: OSE
```
---
