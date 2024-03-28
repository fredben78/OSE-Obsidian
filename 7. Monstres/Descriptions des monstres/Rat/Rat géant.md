---
JDR: OSE
Type:
  - core

tags:
  - monster
statblock: inline
aliases:
  - Giant rat
---
# `=this.file.name`


---
```statblock
layout: OSE
name: Rat géant
subtype: "Long de 1 m ou plus, avec fourrure noire ou grise, il vit souvent dans les parties sombres des donjons et à proximité de monstres morts-vivants."
image:
ac: 7(12)
hit_dice: 1D4
thaco: 19(0)
speed: 36m (12m) / 18m (6m) nage
jds: [12,13,14,15,16,(1)]
moral: 8
alignement: Neutre
xp: 5
nbr: 3d6
nbr_dj: 3d10
loot: [[2. Types de trésors#Type C (1 000 po en moyenne)|C]]
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
actions:
  - name: 1x Morsure
    desc: D20 jet d'attaque, 2 (1d3) de dégâts + maladie
source: OSE
```
---
