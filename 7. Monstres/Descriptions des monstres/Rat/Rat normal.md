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
name: Rat normal
subtype: "Meute de rat grouillants de 15 à 60 cm de long, à la fourrure brune ou grise."
image:
ac: 9(10)
hit_dice: 1D1
thaco: 19(0)
speed: 18m (6m) / 9m (3m) nage
jds: [14,15,16,17,18,(HN)]
moral: 5
alignement: Neutre
xp: 5
nbr: 5d10
nbr_dj: 2d10
loot: [[2. Types de trésors#L|L]]
hp: 3
roll_jds: 1d20
roll-moral: 2d6
traits:
  - name: Maladie
    desc: "Une morsure a 1-sur-20 chance d’infecter la cible (jet de sauvegarde contre le poison). La maladie a 1-sur-4 chance d’être mortelle (mort en 3 (1d6) jours). Sinon, la victime est malade et alitée pendant un mois."
  - name: Peur du feu
    desc: "Fuient le feu, à moins d’être forcés de se battre par la personne qui les a convoqués."
  - name: Attaque dans l’eau
    desc: "Excellents nageurs, attaquent sans malus."
  - name: Meute
    desc: "Chaque groupe de 5 à 10 rats attaque en meute. Chaque meute n’effectue qu’une seule attaque contre une créature donnée."
  - name: Engloutissement
    desc: "La créature attaquée doit effectuer un jet de sauvegarde contre la mort ou tomber à terre et être dans l’incapacité d’attaquer jusqu’à ce qu’elle se soit relevée."
actions:
  - name: 1x Morsure
    desc: D20 jet d'attaque, 2 (1d6) de dégâts + maladie
source: OSE
```
---
