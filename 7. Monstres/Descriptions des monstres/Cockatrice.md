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
name: Cockatrice
subtype: "Un hybride magique de petite taille, à la fois oiseau et reptile. Elle possède une longue queue de serpent et la tête, les pattes et les ailes d’un coq. Vit dans tous les types d’environnements."
image:
alignement: Neutre
ac: 6 (13)
hp: 22
hit_dice: 5D8
thaco: 15 (+4)
speed: 27m (9m)  54 m (18m) vol
jds: [10, 11, 12, 13, 14, 5, d20]
roll_jds: 1d20
roll-moral: 2d6
moral: 7
xp: "425"
nbr: 1d4
nbr_dj: 1d8
loot: [[2. Types de trésors#Type D (3 900 po en moyenne)|D]]
forceColumns: true
columns: 1
traits:
  - name: "Pétrification"
    desc: "Quiconque est touché par une cockatrice doit effectuer un jet de sauvegarde contre la pétrification."
actions:
  - name: 1x coup de bec
    desc: D20 jet d'attaque, 2 (1d6) de dégâts + pétrification
source: OSE
```
---