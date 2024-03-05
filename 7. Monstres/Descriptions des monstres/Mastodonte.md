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
name: Mastodonte
subtype: "Éléphant à long poil avec de grandes défenses. Vit dans les régions glacées ou celles du Monde perdu."
image:
ac: 3(16)
hit_dice: 15D8
thaco: 9(+10)
speed: 36m (12m)
jds: [8,9,10,10,12,(8)]
moral: 8
alignement: Neutre
xp: 1350
nbr: 0
nbr_dj: 2d8
loot: Défenses
hp: 3
roll_jds: 1d20
roll-moral: 2d6
traits:
  - name: Charge
    desc: "Au premier round de combat, lorsqu’il n’est pas encore engagé dans la mêlée. Nécessite une trajectoire dégagée d’au moins 20 m. Les défenses infligent alors double dégâts."
  - name: Piétinement
    desc: "3-sur-4 chances de piétiner à chaque round. Bonus de +4 pour toucher les créatures de taille humaine ou plus petites."
  - name: Ivoire
    desc: " 40 (2d4)x100 po par défense."
actions:
  - name: 2x Défense
    desc: D20 jet d'attaque, 2 (2d6) de dégâts
  - name: ou 1x Piétinement
    desc: D20 jet d'attaque, 2 (4d8) de dégâts
source: OSE
```
---
