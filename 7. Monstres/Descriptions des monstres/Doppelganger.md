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
name: Doppleganger
subtype: "Changeur de forme de nature magique, malfaisant et très rusé."
image: 
alignement: Chaotique
ac: 5(14)
hp: 18
hit_dice: 4D8
thaco: 16 (+3)
speed: 27m (9m)
jds: [6, 7, 8, 8, 10, (10)]
roll_jds: 1d20
roll-moral: 2d6
nbr_dj: 1d6
moral: 10
xp: "125"
nbr: 1d6
forceColumns: true
columns: 1
loot: [[2. Treasure Types#Type E (2 300 po en moyenne)|E]]
traits:
  - name: Vol d’apparence
    desc: "Peut adopter la forme d’une créature de taille humaine (2,10 m ou moins) qu’il a observée, avant de l’attaquer."
  - name: Tromperie
    desc: "Va tenter de tuer un PJ pour le remplacer, avant d’attaquer le groupe par surprise (par exemple, pendant un combat)."
  - name: Retour
    desc: "À sa mort, le doppelganger reprend sa forme naturelle."
  - name: Immunité aux sorts
    desc: "N’est pas affecté par les sorts sommeil et charme."
actions:
  - name: 1x morsure
    desc: D20 jet d'attaque, 2 (1d12) de dégâts
source: OSE
```
---