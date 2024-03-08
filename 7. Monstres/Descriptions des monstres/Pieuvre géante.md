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
name: Pieuvre géante
subtype: "Ce céphalopode géant à huit bras se cache dans les eaux côtières à proximité des villages."
image:
ac: 7(12)
hit_dice: 8D8
thaco: 12(+7)
speed: 27m (9m)
jds: [10,11,12,13,14,(4)]
moral: 7
alignement: Neutre
xp: 650
nbr: 0
nbr_dj: 1d2
loot: Aucun
hp: 3
roll_jds: 1d20
roll-moral: 2d6
traits:
  - name: Constriction
    desc: "Après une attaque réussie, les tentacules saisissent la victime et se resserrent. Chaque tentacule qui serre inflige 1 (1d3) points de dégâts automatiques par round, plus un malus de –1 aux attaques."
  - name: Sectionner les tentacules
    desc: "Nécessite de porter un coup avec une arme tranchante infligeant 6 points de dégâts ou plus."
  - name: Nuage d’encre
    desc: "Lorsqu’elle s’échappe, elle peut émettre un nuage d’encre noire (24 m de diamètre) et s’enfuir à une vitesse 3 fois supérieure à son déplacement normal."
actions:
  - name: 8x Tentacule
    desc: D20 jet d'attaque, 2 (1d3) de dégâts
  - name: 1x Morsure
    desc: D20 jet d'attaque, 2 (1d6) de dégâts
source: OSE
```
---
