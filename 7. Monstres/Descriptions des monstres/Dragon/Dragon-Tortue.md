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
name: Dragon Tortue
subtype: "Monstre marin gigantesque ayant le corps et la carapace d’une tortue, ainsi que la tête, la queue et les pattes d’un dragon. Il se cache dans d’immenses grottes au fond de l’océan, ne remontant que rarement à la surface."
image:
alignement: Chaotique
ac: -2(21)
hp: 135
hit_dice: 30D8
thaco: 5(+14)
speed: 9m (3m), 27m (9m) nage
jds: [4, 5, 6, 5, 8, (15)]
roll_jds: 1d20
roll-moral: 2d6
nbr_dj: 1
moral: 10
xp: "9000"
nbr: 0 
loot: [[2. Types de trésors#Type H (60 000 po en moyenne)|H]]
traits:
  - name: Souffle
    desc: "Nuage de vapeur de 27 m de long et de 9 m de large. Peut être utilisé jusqu’à trois fois par jour. Toutes les personnes présentes dans la zone subissent des dégâts égaux aux points de vie actuels du dragon-tortue (jet de sauvegarde contre les souffles pour n’en subir que la moitié)."
  - name: Pris pour une île
    desc: "Lorsqu’il flotte, on peut facilement confondre le dragon-tortue avec une petite île."
  - name: Attaquer les navires
    desc: "Il essaie parfois, en faisant surface sous eux, de détruire les navires et de dévorer l’équipage."
  - name: "Trésor"
    desc: "Provenant des navires coulés"
actions:
  - name: 2x Griffes 
    desc: D20 jet d'attaque, 2 (1d8) de dégâts
  - name: 1x Morsure
    desc: D20 jet d'attaque, 2 (1d6) x10 de dégâts
  - name: ou Souffle
    desc: "égal aux points de vie actuel du dragon (jet de sauvegarde contre les souffles divise par deux)"
source: OSE
```
---