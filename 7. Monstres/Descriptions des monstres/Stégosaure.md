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
name: Stégosaure
subtype: "Dinosaure herbivore trapu, avec une crête d’écailles le long du dos et une queue parsemée de pointes (qu’il utilise pour dissuader ses attaquants). Habite dans les environnements subtropicaux du Monde perdu."
image:
ac: 3(16)
hit_dice: 11D8
thaco: 11(+8)
speed: 18m (6m)
jds: [10,11,12,13,14,(6)]
moral: 7
alignement: Neutre
xp: 1100
nbr: 0
nbr_dj: 1d4
loot: Aucun
hp: 3
roll_jds: 1d20
roll-moral: 2d6
traits:
  - name: Piétinement
    desc: "3-sur-4 chances de piétiner à chaque round. Bonus de +4 pour toucher les créatures de taille humaine ou plus petites."
actions:
  - name: 1x Queue
    desc: D20 jet d'attaque, 2 (2d8) de dégâts
  - name: ou 1x Piétinement
    desc: D20 jet d'attaque, 2 (2d8) de dégâts
source: OSE
```
---
