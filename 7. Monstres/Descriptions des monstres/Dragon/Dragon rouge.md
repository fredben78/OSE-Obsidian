---
JDR: OSE
Type:
  - core

tags:
  - monster
statblock: inline
---
# `=this.file.name`


---
```statblock
layout: OSE
name: Dragon rouge
subtype: "Habite dans les collines et les montagnes."
image:
alignement: Chaotique
ac: -1(20)
hp: 45
hit_dice: 10D8
thaco: 11(+8)
speed: 27m (9m), 72m (24m) vol
jds: [6, 7, 8, 8, 10, (10)]
moral: 10
roll_jds: 1d20
roll-moral: 2d6
xp: "2300"
nbr: 1d4
nbr_dj: 1d4
loot: [[2. Types de trésors#Type H (60 000 po en moyenne)|H]]
traits:
  - name: Souffle
    desc: "Cône de feu de 27m de long. 60 cm de large à l’entrée, 9 m à l’extrémité. "
  - name: Langue et sorts
    desc: "50% 50 (1d100), 3× 1er niveau, 3× 2e niveau, 3× 3e niveau."
  - name: Sommeil
    desc: 10% 50 (1d100)
actions:
  - name: 2x griffes
    desc: D20 jet d'attaque, 2 (1d8) de dégâts
  - name: Morsure
    desc: D20 jet d'attaque, 2 (4d8) de dégâts
  - name: ou Souffle
    desc: "égal aux points de vie actuel du dragon (jet de sauvegarde contre les souffles divise par deux)"
source: OSE
```
---
