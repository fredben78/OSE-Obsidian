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
name: Tricératops
subtype: "Cet énorme dinosaure herbivore et agressif, faisant 3,60 m à l’épaule et presque 12 m de long, possède une crête protectrice derrière la tête et trois longues cornes. Vit dans les prairies du Monde perdu."
image:
ac: 2(17)
hit_dice: 11D8
thaco: 11(+8)
speed: 27m (9m)
jds: [10,11,12,13,14,(6)]
moral: 8
alignement: Neutre
xp: 1100
nbr: 0
nbr_dj: 1d4
loot: Aucun
hp: 3
roll_jds: 1d20
roll-moral: 2d6
traits:
  - name: Agressif
    desc: "Attaque normalement à vue."
  - name: Charge
    desc: "Au premier round de combat, lorsqu’il n’est pas encore engagé dans la mêlée. Nécessite une trajectoire dégagée d’au moins 20 m. La corne inflige alors double dégâts."
  - name: Piétinement
    desc: "3-sur-4 chances de piétiner à chaque tour. Bonus de +4 pour toucher les créatures de taille humaine ou plus petites."
actions:
  - name: 1x Corne
    desc: D20 jet d'attaque, 2 (3d6) de dégâts
  - name: ou 1x Piétinement
    desc: D20 jet d'attaque, 2 (3d6) de dégâts
source: OSE
```
---
