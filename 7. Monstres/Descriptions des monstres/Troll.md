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
name: Troll
subtype: "Humanoïde tout à la fois intelligent et méchant, faisant 2,40 m de haut, avec un corps maigre et caoutchouteux. Se nourrit de la chair d’autres humanoïdes et vit sous terre, dans les contrées sauvages et les maisons en ruines ayant appartenu à d’anciennes victimes."
image:
ac: 4(15)
hit_dice: 6D8+3
thaco: 13(+6)
speed: 36m (12m)
jds: [10,11,12,13,14,(6)]
moral: 10 (8 peur du feu)
alignement: Chaotique
xp: 650
nbr: 1d8
nbr_dj: 1d8
loot: [[2. Types de trésors#Type D (3 900 po en moyenne)|D]]
hp: 3
roll_jds: 1d20
roll-moral: 2d6
traits:
  - name: Régénération
    desc: "3 rounds après avoir été blessé, le troll regagne 3 pv par round. Cette capacité peut lui permettre de rattacher des membres sectionnés."
  - name: Retour à la vie
    desc: "S’il est tué (0 pv), il se régénère et combat de nouveau en 2d6 rounds."
  - name: Feu et acide
    desc: "Ne peut pas régénérer les dégâts provenant de ces sources. C’est la seule façon de tuer définitivement un troll."
  - name: Peur du feu
    desc: "Moral 8 en cas d’attaque par le feu ou l’acide."
actions:
  - name: 2x Griffes
    desc: D20 jet d'attaque, 2 (1d6) de dégâts
  - name: 1x Morsure
    desc: D20 jet d'attaque, 2 (1d10) de dégâts
source: OSE
```
---
