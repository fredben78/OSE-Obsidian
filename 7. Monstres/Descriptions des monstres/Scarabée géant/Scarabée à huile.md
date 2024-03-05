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
name: Scarabée à huile
subtype: "On peut rencontrer sous terre ce coléoptère fouisseur de 1 m de long."
image:
ac: 4(15)
hit_dice: 2D8
thaco: 18(+1)
speed: 36m (12m)
jds: [12,13,14,15,16,(1)]
moral: 8
alignement: Neutre
xp: 25
nbr: 1d8
nbr_dj: 2d6
forceColumns: true
columns: 1
loot: Aucun
hp: 3
roll_jds: 1d20
roll-moral: 2d6
traits:
  - name: Crachat huileux
    desc: "En réaction à une attaque, cible un adversaire à 1,50 m de lui. Une attaque réussie provoque des cloques sur la peau infligeant un malus de – 2 aux jets d’attaques pendant 24 heures. Le sort Guérison des blessures légères peut être utilisé pour soigner ces cloques, les faisant disparaître au lieu de rendre des points de vie."
actions:
  - name: 1x Morsure
    desc: D20 jet d'attaque, 2 (1d6) de dégâts
  - name: 1x Crachat huileux
    desc: D20 jet d'attaque, Cloques
source: OSE
```
---
