---
JDR: OSE
Type:
  - core
share: true
tags:
  - monster
statblock: inline
---
# Chien esquiveur

------
```statblock
layout: OSE
name: Chien esquiveur
subtype: "Chien très intelligent, semblable à un dingo, qui vit en meute et a la capacité innée de voyager dans et hors de la réalité."
image:
alignement: Loyal
ac: 5(14)
hp: 18
hit_dice: 4D8
thaco: 16 (+3)
speed: 36m (12m)
jds: [10, 11, 12, 13, 14, (4)]
roll_jds: 1d20
roll-moral: 2d6
moral: 6
xp: "125"
nbr: 1d6
nbr_dj: 1d6
loot: [[2. Treasure Types#Type C (1 000 po en moyenne)|C]]
forceColumns: true
columns: 1
traits:
  - name: Intermittence
    desc: "En combat, se téléporte près d’un ennemi, attaque, puis réapparaît à 2 (1d4) × 3 m de distance. S’il a l’initiative, il peut utiliser cette capacité sans que l’adversaire puisse contre-attaquer."
  - name: Disparition
    desc: "Au bord de la défaite, la meute peut s’enfuir en disparaissant entièrement."
  - name: Haine des bêtes dimensionnelles
    desc: "Le chien esquiveur les attaque toujours."
actions:
  - name: 1x morsure
    desc: D20 jet d'attaque, 3 (1d6) de dégâts
source: OSE
```
---