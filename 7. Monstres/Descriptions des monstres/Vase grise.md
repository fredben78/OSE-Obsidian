---
JDR: OSE
Type:
  - core

tags:
  - monster
statblock: inline
aliases:
  - Grey ooze
---
# `=this.file.name`


---
```statblock
layout: OSE
name: Vase grise
subtype: "Horreur visqueuse qui se cache sur les surfaces en pierre ou parmi les rochers."
image:
ac: 8(11)
hit_dice: 3D8
thaco: 17(+2)
speed: 3m (1m)
jds: [12,13,14,15,16,(2)]
moral: 12
alignement: Neutre
xp: "50"
nbr: 1
nbr_dj: 1
loot: Aucun
hp: 3
roll_jds: 1d20
roll-moral: 2d6
forceColumns: true
columns: 1
traits:
  - name: Se confond avec la pierre
    desc: "Difficile de la distinguer de la pierre humide."
  - name: Acide
    desc: "Après une attaque réussie, elle se colle à la victime et exsude de l’acide, qui détruit immédiatement toute armure normale et inflige 4 (2d8) dégâts par round. Une armure magique est dissoute en un tour."
  - name: Immunité naturelle
    desc: "Immunisée au froid ou au feu."
actions:
  - name: 1x Toucher
    desc: D20 jet d'attaque, 2 (2d8) de dégâts
source: OSE
```
---
