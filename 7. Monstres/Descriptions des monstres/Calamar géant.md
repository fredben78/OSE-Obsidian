---
JDR: OSE
Type:
  - core

tags:
  - monster
statblock: inline
aliases:
  - Giant squid
---
# `=this.file.name`


---
```statblock
layout: OSE
name: Calamar géant
subtype: "Céphalopode géant doté de dix tentacules. Peut attaquer les navires à l’aide de ses deux plus grands. Habite dans les profondeurs de la mer et ne remonte à la surface que pour trouver des proies."
image:
ac: 7(12)
hit_dice: 6D8
thaco: 14(+5)
speed: 36m (12m)
jds: [12,13,14,15,16,(3)]
moral: 7
alignement: Neutre
xp: 275
nbr: 0
nbr_dj: 1d4
loot: [[2. Types de trésors#Type V (330 po en moyenne)|V]]
hp: 3
roll_jds: 1d20
roll-moral: 2d6
traits:
  - name: Écraser les bateaux
    desc: "25 % de chances d’enrouler ses 2 grands tentacules autour d’un bateau, infligeant 5 (1d10) points de dégâts de structure par tentacule. Lorsque les grands tentacules attaquent un bateau, le rostre inflige automatiquement lors des rounds suivants 2 points de dégâts de structure."
  - name: Saisir l’équipage
    desc: "Le calmar géant a 75 % de chances de saisir un membre d’équipage sur le pont et de le faire tomber à l’eau pour le dévorer."
  - name: Constriction
    desc: "Après une attaque réussie, les tentacules saisissent la victime et se resserrent sur elle, lui infligeant automatiquement 2 (1d4) points de dégâts par round."
  - name: Sectionner les tentacules
    desc: "Nécessite de porter un coup infligeant 6 points de dégâts ou plus (pour les 8 petits tentacules) ou 10 dégâts ou plus (pour les 2 grands tentacules)."
  - name: Nuage d’encre
    desc: "Lorsque le calmar géant s’échappe, il peut émettre un nuage d’encre noire (18 m de diamètre) et s’enfuir à une vitesse 3 fois supérieure à son déplacement normal. Il ne peut le faire que deux fois par jour au maximum."
  - name: Spécimens gigantesques
    desc: "Il arrive de rencontrer des spécimens deux ou trois fois plus gros."
actions:
  - name: 8x Petit tentacule
    desc: D20 jet d'attaque, 2 (1d4) de dégâts de constriction
  - name: 2x Grand tentacule
    desc: D20 jet d'attaque, 2 (1d4) de dégâts de constriction ou 5 (1d10) de dégats de points de strcuture
  - name: 1x Rostre
    desc: D20 jet d'attaque, 2 (1d10) de dégâts ou 2 points de dégâts de structure
source: OSE
```
---
