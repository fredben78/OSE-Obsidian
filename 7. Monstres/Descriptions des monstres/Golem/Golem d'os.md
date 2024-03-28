---
JDR: OSE
Type:
  - core

tags:
  - monster
statblock: inline
aliases:
  - Bone golem
---
# `=this.file.name`


---
```statblock
layout: OSE
name: Golem d'os
subtype: "Cette créature artificielle, haute de 1,80 m, en os humains, prend une forme humanoïde, mais possède quatre bras attachés à différents endroits du torse."
image:
ac: 2(17)
hit_dice: 8D8
thaco: 12(+7)
speed: 36m (12m)
jds: [10,11,12,13,14,(4)]
moral: 12
alignement: Neutre
xp: "650"
nbr: 1
nbr_dj: 1
loot: Aucun
hp: 3
roll_jds: 1d20
roll-moral: 2d6
forceColumns: true
columns: 1
traits:
  - name: Immunité
    desc: "Immunisé contre les gaz ; insensible aux sorts charme, paralysie et sommeil."
  - name: Autres matériaux
    desc: "Des golems formés d’autres matériaux sont également possibles."
  - name: Construction
    desc: "Long processus très complexe et coûteux."
  - name: Immunité aux dégâts normaux
    desc: "Ne peut être blessé que par des attaques magiques."
  - name: Armes
    desc: "4 × 1 main ou 2 × 2 mains."
  - name: Attaques multiples
    desc: "Peut attaquer 2 cibles chaque round."
  - name: Immunité naturelle
    desc: "Immunisé au feu, au froid et à l’électricité."
actions:
  - name: 2 ou 4x arme 
    desc: D20 jet d'attaque, 2 (1d6) de dégâts ou selon arme
source: OSE
```
---
