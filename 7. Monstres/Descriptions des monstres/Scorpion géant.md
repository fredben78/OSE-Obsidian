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
name: Scorpion géant
subtype: "Énorme arachnide, gros comme un petit cheval, possédant des pinces et un dard mortel. Niche dans les cavernes, les ruines et les déserts."
image:
ac: 2(17)
hit_dice: 4D8
thaco: 16(+3)
speed: 45m (15m)
jds: [12,13,14,15,16,(2)]
moral: 11
alignement: Chaotique
xp: 125
nbr: 1d6
nbr_dj: 1d6
loot: [[2. Types de trésors#Type V (330 po en moyenne)|V]]
hp: 3
roll_jds: 1d20
roll-moral: 2d6
traits:
  - name: Agressif
    desc: "Attaque en général à vue."
  - name: Poison
    desc: "Provoque la mort (jet de sauvegarde contre le poison)."
  - name: Saisit et pique
    desc: "Bonus de +2 à l’attaque du dard, si une pince touche."
actions:
  - name: 2x Pince
    desc: D20 jet d'attaque, 2 (1d10) de dégâts
  - name: 1x Dard
    desc: D20 jet d'attaque, 2 (1d4) de dégâts + poison
source: OSE
```
---
