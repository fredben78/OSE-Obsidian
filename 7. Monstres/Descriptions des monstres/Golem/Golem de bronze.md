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
name: Golem de bronze
layout: OSE
subtype: "Cette créature artificielle en bronze, possédant une grande chaleur interne, ressemble à un géant de feu."
image:
ac: 0(19)
hit_dice: 20D8
thaco: 6(+13)
speed: 54m (18m)
jds: [6,7,8,8,10,(10)]
moral: 12
alignement: Neutre
xp: "4300"
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
  - name: Sang incendiaire
    desc: "S’il est endommagé par une arme tranchante, le golem de bronze émet un jet de feu liquide : l’attaquant subit 6 (2d6) de dégâts (jet de sauvegarde contre la mort pour l’éviter)."
  - name: Immunité au feu
    desc: "Immunisé aux dégâts de feu."
actions:
  - name: 1x Poing
    desc: D20 jet d'attaque, 2 (3d10) de dégâts + 5 (1d10) chaleur
source: OSE
```
---
