---
JDR: OSE
Type:
  - core

tags:
  - monster
statblock: inline
aliases:
  - Pit viper
---
# `=this.file.name`


---
```statblock
layout: OSE
name: Crotale
subtype: "Serpent de 1,50 m de long, avec des écailles grises ou vertes."
image:
ac: 6(13)
hit_dice: 2D8
thaco: 18(+1)
speed: 27m (9m)
jds: [12,13,14,15,16,(1)]
moral: 7
alignement: Neutre
xp: 25
nbr: 1d8
nbr_dj: 1d8
loot: Aucun
hp: 3
roll_jds: 1d20
roll-moral: 2d6
traits:
  - name: Infravision
    desc: "Sur 18 m. Les orifices sur la tête lui permettent de ressentir la chaleur."
  - name: Initiative
    desc: "En raison de sens spéciaux, gagne toujours l’initiative (pas de jet)."
  - name: Poison
    desc: "Provoque la mort (jet de sauvegarde contre le poison)."
actions:
  - name: 1x Morsure
    desc: D20 jet d'attaque, 2 (1d4) de dégâts + poison
source: OSE
```
---
