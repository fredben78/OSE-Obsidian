---
JDR: OSE
Type:
  - core

tags:
  - monster
statblock: inline
aliases:
  - Bull shark
---
# `=this.file.name`


---
```statblock
layout: OSE
name: Requin-bouledogue
subtype: "Long de 2,40 m, de couleur foncée, il attaque en heurtant sa proie pour la mordre ensuite alors qu’elle est étourdie."
image:
ac: 4(15)
hit_dice: 2D8
thaco: 18(+1)
speed: 54m (18m)
jds: [12,13,14,15,16,(1)]
moral: 7
alignement: Neutre
xp: 20
nbr: 0
nbr_dj: 3d6
loot: Aucun
hp: 3
roll_jds: 1d20
roll-moral: 2d6
traits:
  - name: Goût du sang
    desc: "Peut détecter du sang dans l’eau jusqu’à 90 m de distance."
  - name: Frénésie dévorante
    desc: "Déclenchée par le goût du sang : attaque toujours ; aucun jet de moral."
  - name: Percussion
    desc: "Jet de sauvegarde contre la paralysie ou être étourdie pendant 3 rounds."
actions:
  - name: 1x Morsure
    desc: D20 jet d'attaque, 2 (2d4) de dégâts
  - name: ou 1x Percursion
    desc: D20 jet d'attaque, étourdissement
source: OSE
```
---
