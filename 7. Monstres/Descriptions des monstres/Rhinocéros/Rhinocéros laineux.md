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
name: Rhinocéros laineux
subtype: "Rhinocéros géant adapté aux climats froids, le corps recouvert d’une épaisse fourrure blanche. Vit en troupeaux dans les régions froides du Monde perdu."
image:
ac: 4(15)
hit_dice: 8D8
thaco: 12(+7)
speed: 36m (12m)
jds: [10,11,12,13,14,(4)]
moral: 6
alignement: Neutre
xp: 650
nbr: 0
nbr_dj: 1d8
loot: Aucun
hp: 3
roll_jds: 1d20
roll-moral: 2d6
traits:
  - name: Charge
    desc: "S’il est dérangé ou menacé, il charge dans une direction prise au hasard. Nécessite une trajectoire dégagée d’au moins 20 m entre lui et sa cible. Peut lancer une attaque de corne sur toute la trajectoire, qui inflige doubles dégâts."
  - name: Piétinement
    desc: "3-sur-4 chances de piétiner à chaque round. Bonus de +4 pour toucher les créatures de taille humaine ou plus petites."
actions:
  - name: 1x Corne
    desc: D20 jet d'attaque, 2 (2d6) de dégâts
  - name: 1x Piétinement
    desc: D20 jet d'attaque, 2 (2d12) de dégâts
source: OSE
```
---
