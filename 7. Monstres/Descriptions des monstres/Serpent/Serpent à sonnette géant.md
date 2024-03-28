---
JDR: OSE
Type:
  - core

tags:
  - monster
statblock: inline
aliases:
  - Giant rattler
---
# `=this.file.name`


---
```statblock
layout: OSE
name: Serpent à sonnette géant
subtype: "Long serpent de 3 m de long, avec des écailles brunes et blanches en forme de diamant, et une cascabelle d’écailles râpeuses sur sa queue."
image:
ac: 5(14)
hit_dice: 4D8
thaco: 16(+3)
speed: 36m (12m)
jds: [12,13,14,15,16,(2)]
moral: 8
alignement: Neutre
xp: 125
nbr: 1d4
nbr_dj: 1d4
loot: [[2. Types de trésors#Type U (160 po en moyenne)|U]]
hp: 3
roll_jds: 1d20
roll-moral: 2d6
traits:
  - name: Cascabelle
    desc: "Il la secoue pour avertir les créatures qu’il ne souhaite pas attaquer."
  - name: Poison
    desc: "Provoque la mort en 3 (1d6) tours (jet de sauvegarde contre le poison)."
  - name: Vitesse
    desc: "Attaque deux fois par round. La deuxième attaque a lieu à la fin de chaque round."
actions:
  - name: 2x Morsure
    desc: D20 jet d'attaque, 2 (1d4) de dégâts + poison
source: OSE
```
---
