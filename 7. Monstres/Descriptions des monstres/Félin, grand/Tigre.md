---
JDR: OSE
Type:
  - core

tags:
  - monster
statblock: inline
aliases:
  - Cat
  - Tiger
---
# `=this.file.name`


---
```statblock
layout: OSE
name: Tigre
subtype: "Ce grand chasseur solitaire, dont la fourrure rayée lui sert de camouflage, apprécie les régions boisées et froides."
image:
alignement: Neutre
ac: 6(13)
hp: 27
hit_dice: 6D8
thaco: 14 (+5)
speed: 45m (15m)
jds: [12, 13, 14, 15, 16, (3)]
roll_jds: 1d20
roll-moral: 2d6
nbr_dj: 1d3
moral: 9
xp: "275"
nbr: 1
loot: [[2. Types de trésors#Type U (160 po en moyenne)|U]]
traits:
  - name: Poursuite
    desc: "Poursuivent toujours leurs proies en fuite."
  - name: Surprise
    desc: "Dans les régions boisées, grâce à son camouflage, il attaque par surprise sur un résultat de 1-4"
actions:
  - name: 2x griffes 
    desc: D20 jet d'attaque, 2 (1d6) de dégâts
  - name: 1x morsure
    desc: D20 jet d'attaque, 2 (2d6) de dégâts
source: OSE
```
---
