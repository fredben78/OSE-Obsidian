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
name: Dragon blanc
subtype: "On le trouve dans les régions froides."
image:
alignement: Neutre
ac: 3(16)
hp: 27
hit_dice: 6D8
thaco: 14 (+5)
speed: 27m (9m) / 72m (24m) vol
jds: [10, 11, 12, 13, 14, (6)]
roll_jds: 1d20
roll-moral: 2d6
moral: 8
xp: "725"
nbr: 1d4
nbr_dj: 1d4
loot: [[2. Types de trésors#Type H (60 000 po en moyenne)|H]]
traits:
  - name: Souffle
    desc: "Cône de froid de 24 m de long, 60 cm de large à l’entrée, 9 m à l’extrémité."
  - name: "Langue et sorts"
    desc: "10% 50 (1d100), 3x 1er niveau."
  - name: Sommeil
    desc: "50% 50 (1d100)"
actions:
  - name: 2x griffes 
    desc: D20 jet d'attaque, 2 (1d4) de dégâts
  - name: Morsure
    desc: D20 jet d'attaque (2d8) de dégâts
  - name: ou Souffle
    desc: "égal aux points de vie actuel du dragon (jet de sauvegarde contre les souffles divise par deux)"
source: OSE
```
---
