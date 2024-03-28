---
JDR: OSE
Type:
  - core

tags:
  - monster
statblock: inline
aliases:
  - Hippogriff
---
# `=this.file.name`


---
```statblock
layout: OSE
name: Hippogriffe
subtype: "Créature fantastique qui combine les caractéristiques d’un aigle géant (tête et partie avant) et d’un cheval. Il construit son nid parmi les rochers escarpés."
image:
ac: 5(14)
hit_dice: 3D8+1
thaco: 16(+3)
speed: 54m (18m) / 108m (36m) vol
jds: [12,13,14,15,16,(2)]
moral: 8
alignement: Neutre
xp: "50"
nbr: 0
nbr_dj: 2d8
loot: Aucun
hp: 3
roll_jds: 1d20
roll-moral: 2d6
forceColumns: true
columns: 1
traits:
  - name: Haine des pégases
    desc: "L’hippogriffe les attaque généralement."
  - name: Monture
    desc: "Peut transporter un cavalier de taille humaine."
  - name: Dressage
    desc: "Il peut être dressé pour servir de monture."
actions:
  - name: 2x Griffes
    desc: D20 jet d'attaque, 2 (1d6) de dégâts
  - name: 1x Morsure
    desc: D20 jet d'attaque, 2 (1d10) de dégâts
source: OSE
```
---
