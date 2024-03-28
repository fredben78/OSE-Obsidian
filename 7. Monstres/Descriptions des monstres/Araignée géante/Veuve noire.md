---
JDR: OSE
Type:
  - core

tags:
  - monster
statblock: inline
aliases:
  - Black widow
---
# `=this.file.name`


---
```statblock
name: Veuve noire
subtype: "Araignée noire, de 1,80 m de long avec un motif de sablier rouge sur l’abdomen ; habite dans des tanières remplies de toiles et s’attaque parfois aux humains."
layout: OSE
image:
ac: 6(13)
hit_dice: 3D8
thaco: 17(+2)
speed: 18m (6m) / 36m (12m) dans sa toile
jds: [12,13,14,15,16,(2)]
moral: 8
alignement: Neutre
xp: 50
nbr: 1d3
nbr_dj: 1d3
loot: [[2. Types de trésors#Type U (160 po en moyenne)|U]]
hp: 3
roll_jds: 1d20
roll-moral: 2d6
traits:
  - name: Poison
    desc: "Provoque la mort en 1 tour (jet de sauvegarde contre le poison)."
  - name: Toiles
    desc: "Les créatures prises dans les toiles s’emmêlent et ne peuvent plus bouger. Se libérer dépend de la Force: \n 5 (2d4) tours pour la force d’un humain normal.\n 4 rounds pour une force supérieure à 18.\n 2 rounds pour les créatures ayant une force de géant. \n \n Les toiles d’araignée peuvent être détruites par le feu en deux rounds. Toutes les créatures prises dans une toile enflammée subissent 3 (1d6) points de dégâts."
actions:
  - name: 1x Morsure
    desc: D20 jet d'attaque, 2 (2d6) de dégâts + poison
source: OSE
```
---
