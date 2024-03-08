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
name: Géant de pierre
subtype: "Humanoïde, haut de 4,20 m, a une peau grise semblable à de la pierre. Habite dans des cavernes naturelles ou des huttes primitives construites en pierre."
image:
ac: 4(15)
hit_dice: 9D8
thaco: 12(+7)
speed: 36m (12m)
jds: [8,9,10,10,12,(9)]
moral: 9
alignement: Neutre
xp: "900"
nbr: 1d2
nbr_dj: 1d6
loot: [[2. Types de trésors|E]] + 5000po
hp: 3
roll_jds: 1d20
roll-moral: 2d6
forceColumns: true
columns: 1
traits:
  - name: Armes
    desc: "Gourdins en pierre faits à partir d’énormes stalactites."
  - name: Lancer de rochers
    desc: "Jusqu’à 90 m."
  - name: Gardiens
    desc: "50 %  50 (1d100) de chances d’être accompagné par 2 (1d4) [[Ours des cavernes|ours des cavernes]]."
  - name:
    desc:
actions:
  - name: 1x Arme
    desc: D20 jet d'attaque, 2 (3d6) de dégâts
  - name: ou 1x Rocher
    desc: D20 jet d'attaque, 2 (3d6) de dégâts
source: OSE
```
---
