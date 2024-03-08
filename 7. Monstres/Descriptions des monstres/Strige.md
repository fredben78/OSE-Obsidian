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
name: Strige
layout: OSE
subtype: "Créature à plumes rappelant des oiseaux, dont le bec est long et acéré."
image:
ac: 7(12)
hit_dice: 1D8
thaco: 19(0)
speed: 9m (3m) / 54m (18m) vol
jds: [12,13,14,15,16,(2)]
moral: 9
alignement: Neutre
xp: 13
nbr: 1d10
nbr_dj: 3d12
loot: [[2. Types de trésors#Type L (240 po en moyenne)|L]]
hp: 3
roll_jds: 1d20
roll-moral: 2d6
traits:
  - name: Attaque en piqué
    desc: "La première attaque se fait avec un bonus de +2 pour toucher."
  - name: Absorption de sang
    desc: "Après une attaque réussie, la strige se fixe sur sa cible afin de lui boire le sang: 1 (1d3) points de dégâts automatiques par round."
  - name: Détachement
    desc: "Uniquement à la mort de la strige ou de la victime."
actions:
  - name: 1x Bec
    desc: D20 jet d'attaque, 2 (1d3) de dégâts + absorption de sang
source: OSE
```
---
