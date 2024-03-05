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
name: Cobra cracheur
subtype: "Serpent de 1 m de long, avec des écailles grises ou blanches. Préfère attaquer à distance avec son crachat."
image:
ac: 7(12)
hit_dice: 1D8
thaco: 19(0)
speed: 27m (9m)
jds: [12,13,14,15,16,(1)]
moral: 7
alignement: Neutre
xp: 13
nbr: 1d6
nbr_dj: 1d6
loot: Aucun
hp: 3
roll_jds: 1d20
roll-moral: 2d6
traits:
  - name: Crachat aveuglant
    desc: "Portée: 1,80 m. Provoque une cécité permanente (jet de sauvegarde contre le poison)."
  - name: Poison
    desc: "Provoque la mort en 5 (1d10) tours (jet de sauvegarde contre le poison)."
actions:
  - name: 1x Crachat
    desc: D20 jet d'attaque, Cécité
  - name: 1x Morsure
    desc: D20 jet d'attaque, 2 (1d3) de dégâts + poison
source: OSE
```
---
