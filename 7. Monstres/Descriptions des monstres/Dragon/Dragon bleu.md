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
name: Dragon bleu
subtype: "Privilégie les plaines ouvertes et les déserts."
image:
alignement: Neutre
ac: 0(19)
hp: 40
hit_dice: 9D8
thaco: 12(+7)
speed: 27m (9m) / 72m (24m) vol
jds: [8, 9, 10, 10, 12, (9)]
roll_jds: 1d20
roll-moral: 2d6
moral: 9
nbr_dj: 1d4
xp: "2300"
nbr: 1d4
loot: [[2. Treasure Types#Type H (60 000 po en moyenne)|H]]
traits:
  - name: Souffle
    desc: "Ligne de foudre de 30m de long, 1,50 m de large sur toute la longueur."
  - name: "Langue et sorts"
    desc: "40% 50 (1d100), 4x 1er niveau, 4x 2ème niveau"
  - name: Sommeil
    desc: "20% 50 (1d100)"
actions:
  - name: 2x griffes
    desc: D20 jet d'attaque, 2 (1d6+1) de dégâts
  - name: 1x morsure
    desc: D20 jet d'attaque, 2 (3d10) de dégâts
  - name: ou Souffle
    desc: "égal aux points de vie actuel du dragon (jet de sauvegarde contre les souffles divise par deux)"
source: OSE
```
---
