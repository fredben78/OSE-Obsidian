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
name: Thoul
subtype: "Abomination magique qui ressemble à un hobgobelin (sauf en cas d’examen attentif), mais possède en même temps des capacités héritées des trolls et des goules. Vivent parfois avec les hobgobelins."
image:
ac: 6(13)
hit_dice: 3D8
thaco: 17(+2)
speed: 36m (12m)
jds: [12,13,14,15,16,(3)]
moral: 10
alignement: Chaotique
xp: 65
nbr: 1d6
nbr_dj: 1d10
loot: [[2. Types de trésors#Type C (1 000 po en moyenne)|C]]
hp: 3
roll_jds: 1d20
roll-moral: 2d6
traits:
  - name: Paralysie
    desc: "Une attaque réussie paralyse la victime pour 5 (2d4) tours (un jet de sauvegarde contre la paralysie annule l’effet). Les elfes et les créatures plus grandes qu’un ogre sont immunisés. Après avoir paralysé un adversaire, un thoul passe à un autre."
  - name: Régénération
    desc: "Un thoul blessé récupère un point de vie au début de chaque round aussi longtemps qu’il est en vie."
actions:
  - name: 2x Griffes
    desc: D20 jet d'attaque, 2 (1d3) de dégâts + paralysie
  - name: 1x Arme
    desc: D20 jet d'attaque, 2 (1d6) de dégâts ou selon l'arme
source: OSE
```
---
