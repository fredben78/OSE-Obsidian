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
name: Tarentulle
subtype: "Cette araignée chasseuse aux longs poils, faisant 2,10 m de long, est magique et ressemble à une tarentule."
layout: OSE
image:
ac: 5(14)
hit_dice: 4D8
thaco: 16(+3)
speed: 36m (12m)
jds: [12,13,14,15,16,(2)]
moral: 8
alignement: Neutre
xp: 125
nbr: 1d
nbr_dj: 1d3
loot: [[2. Treasure Types#Type U (160 po en moyenne)|U]]
hp: 3
roll_jds: 1d20
roll-moral: 2d6
traits:
  - name: Poison
    desc: "Jet de sauvegarde contre le poison ou la cible se met à danser pendant 2d6 tours (souffrant de spasmes douloureux et saccadés qui ressemblent à une danse macabre)."
  - name: Les spectateurs
    desc: "Les spectateurs de la personne affectée par le poison doivent effectuer un jet de sauvegarde contre les sorts ou commencer à danser de la même manière, aussi longtemps que la victime est empoisonnée."
  - name: Danse
    desc: "Les personnes affectées subissent un malus de –4 sur leurs jets d’attaque et à leur CA. Après 5 tours de danse, ils sont épuisés et s’écroulent à terre, sans défense."
actions:
  - name: 1x Morsure
    desc: D20 jet d'attaque, 2 (1d8) de dégâts + poison
source: OSE
```
---
