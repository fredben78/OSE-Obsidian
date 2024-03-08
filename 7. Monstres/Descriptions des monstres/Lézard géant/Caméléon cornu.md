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
layout: OSE
name: Caméléon cornu
subtype: "Lézard long de 2,10 m, dont les écailles aux couleurs changeantes lui servent de camouflage."
image:
ac: 2(17)
hit_dice: 5D8
thaco: 15(+4)
speed: 36m (12m)
jds: [12,13,14,15,16,(3)]
moral: 7
alignement: Neutre
xp: 300
nbr: 1d3
nbr_dj: 1d6
loot: [[2. Types de trésors#Type U (160 po en moyenne)|U]]
hp: 3
roll_jds: 1d20
roll-moral: 2d6
traits:
  - name: Surprise
    desc: "Sur un 1-à-5, en raison du camouflage."
  - name: Langue collante
    desc: "Peut attaquer des cibles jusqu’à 1,50 m de distance. Si l’attaque réussit, la victime est traînée vers la gueule et mordue ( 4 (2d4) points de dégâts)."
  - name: Queue
    desc: "N’inflige aucun dégât, mais renverse l’adversaire, qui ne peut pas attaquer ce round."
actions:
  - name: 1x Langue / Morsure
    desc: D20 jet d'attaque, 2 (2d4) de dégâts
  - name: 1x Corne
    desc: D20 jet d'attaque, 2 (1d6) de dégâts
  - name: 1x Queue
    desc: D20 jet d'attaque, renversé
source: OSE
```
---
