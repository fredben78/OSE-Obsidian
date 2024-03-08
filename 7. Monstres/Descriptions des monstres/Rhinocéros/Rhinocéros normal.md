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
name: Rhinocéros normal
subtype: "Mammifère herbivore de couleur sombre et doté d’une armure de plaques de peau très épaisses."
image:
ac: 5(14)
hit_dice: 6D8
thaco: 14(+5)
speed: 36m (12m)
jds: [12,13,14,15,16,(3)]
moral: 6
alignement: Neutre
xp: 275
nbr: 0
nbr_dj: 1d12
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
    desc: D20 jet d'attaque, 2 (2d4) de dégâts
  - name: 1x Piétinement
    desc: D20 jet d'attaque, 2 (2d8) de dégâts
source: OSE
```
---
