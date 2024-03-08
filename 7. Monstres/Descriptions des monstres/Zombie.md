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
name: Zombie
subtype: "Cadavre d’humanoïde apathique ayant été réanimé par un magicien ou un clerc expérimenté pour faire office de gardien."
image:
ac: 8(11)
hit_dice: 2D8
thaco: 18(+1)
speed: 18m (9m)
jds: [12,13,14,15,16,(1)]
moral: 12
alignement: Chaotique
xp: 20
nbr: 2d4
nbr_dj: 4d6
loot: Aucun
hp: 3
roll_jds: 1d20
roll-moral: 2d6
traits:
  - name: Gardien
    desc: "Attaque toujours à vue."
  - name: Initiative
    desc: "Perd toujours l’initiative (pas de jet nécessaire)."
  - name: Mort-vivant
    desc: "Ne fait aucun bruit jusqu’à ce qu’il attaque. Immunisé contre les effets affectant les créatures vivantes (par exemple, le poison). Immunisé contre les sorts affectant ou lisant l’esprit (par exemple, charme, paralysie, sommeil)."
actions:
  - name: 1x arme
    desc: D20 jet d'attaque, 2 (1d8) de dégâts ou selon l'arme
source: OSE
```
---
