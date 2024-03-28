---
JDR: OSE
Type:
  - core

tags:
  - monster
statblock: inline
aliases:
  - Gold Dragon
---
# `=this.file.name`


---
```statblock
layout: OSE
name: Dragon d'or
subtype: "On peut le rencontrer sur n’importe quel terrain, souvent sous l’apparence d’une personne ou d’un animal."
image:
alignement: Loyal
ac: -2(21)
hp: 49
hit_dice: 11D8
thaco: 11(+8)
speed: 27m (9m), 72m (24m) vol
jds: [ 6, 7, 8, 8, 10, (11)]
roll_jds: 1d20
roll-moral: 2d6
nbr_dj: 1d4
moral: 10
xp: "2700"
nbr: 1d4
loot: [[2. Types de trésors#Type H (60 000 po en moyenne)|H]]
traits:
  - name: Souffle
    desc: "Cône de feu ou nuage de chlore gazeux de 27 m de long."
  - name: Langue et sorts
    desc: 100%, 4x 1er niveau, 4x 2ème niveau, 4x 3 niveau
  - name: Sommeil
    desc: 5% 50 (1d100)
  - name: Changement de forme
    desc: "Peut prendre la forme dune personne ou d'un animal"
actions:
  - name: 2x griffes
    desc: D20 jet d'attaque, 2 (2d4) de dégâts
  - name: 1x morsure
    desc: D20 jet d'attaque, 2 (6d6) de dégâts
  - name: ou Souffle
    desc: "égal aux points de vie actuel du dragon (jet de sauvegarde contre les souffles divise par deux)"
source: OSE
```
---
