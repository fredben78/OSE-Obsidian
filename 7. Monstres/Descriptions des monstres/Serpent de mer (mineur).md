---
JDR: OSE
Type:
  - core

tags:
  - monster
statblock: inline
aliases:
  - Sea serpent (lesser)
---
# `=this.file.name`


---
```statblock
layout: OSE
name: Serpent de mer (mineur)
subtype: "Ce monstre marin, entre 6 et 9 m de long, ressemble à un serpent avec des rangées de nombreuses nageoires."
image:
ac: 5(14)
hit_dice: 6D8
thaco: 14(+5)
speed: 45m (15m)
jds: [12,13,14,15,16,(3)]
moral: 8
alignement: Neutre
xp: 275
nbr: 0
nbr_dj: 2d6
loot: Aucun 
hp: 3
roll_jds: 1d20
roll-moral: 2d6
traits:
  - name: Bond en avant
    desc: "Peut effectuer une attaque en bondissant de l’eau jusqu’à 6 m de hauteur pour utiliser son attaque de morsure."
  - name: Constriction
    desc: "S’enroule autour d’un navire de même taille ou plus petit, et l’écrase."
actions:
  - name: 1x Morsure
    desc: D20 jet d'attaque, 2 (2d6) de dégâts
  - name: ou 1x Constriction
    desc: D20 jet d'attaque, 2 (1d10) de dégâts de structure
source: OSE
```
---
