---
JDR: OSE
Type:
  - core

tags:
  - monster
statblock: inline
aliases:
  - Wood golem
---
# `=this.file.name`


---
```statblock
layout: OSE
name: Golem de bois
subtype: "Humanoïde en bois, haut de 1 m, grossièrement construit."
image:
ac: 7(12)
hit_dice: 2D8+2
thaco: 17(+2)
speed: 36m (12m)
jds: [12,13,14,15,16,(1)]
moral: 12
alignement: Neutre
xp: "25"
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
  - name: Initiative
    desc: "Malus de –1 à cause de ses mouvements raides."
  - name: Inflammable
    desc: "Malus de –2 à ses jets de sauvegarde contre les attaques de feu ; subit un point de dégâts supplémentaire par dé."
actions:
  - name: 1x Poing
    desc: D20 jet d'attaque, 2 (1d8) de dégâts
source: OSE
```
---
