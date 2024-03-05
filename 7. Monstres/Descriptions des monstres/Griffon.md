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
name: Griffon
subtype: "Grand rapace prédateur qui combine les caractéristiques d’un aigle (tête, ailes, griffes avant) et celles d’un lion. Chasse les chevaux."
image:
ac: 5(14)
hit_dice: 7D8
thaco: 13(+6)
speed: 36m (12m) / 108m (36m) vol
jds: [10,11,12,13,14,(4)]
moral: 8
alignement: Neutre
xp: "450"
nbr: 0
nbr_dj: 2d8
loot: [[2. Treasure Types#Type E (2 300 po en moyenne)|E]]
hp: 3
roll_jds: 1d20
roll-moral: 2d6
forceColumns: true
columns: 1
traits:
  - name: Attaque les chevaux
    desc: "Jusqu’à 36 m, à moins de réussir un test de morale."
  - name: Défense du nid
    desc: "Attaque si on l’approche."
  - name: Dressage
    desc: "Les petits capturés peuvent être dressés comme des montures loyales. Mais l’entraînement ne fera pas disparaître leur nature féroce : ils attaqueront toujours instinctivement les chevaux."
actions:
  - name: 2x Griffes
    desc: D20 jet d'attaque, 2 (1d4) de dégâts
  - name: 1x Morsure
    desc: D20 jet d'attaque, 2 (2d8) de dégâts
source: OSE
```
---
