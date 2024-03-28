---
JDR: OSE
Type:
  - core

tags:
  - monster
statblock: inline
aliases:
  - War horse
---
# `=this.file.name`


---
```statblock
name: Cheval de guerre
layout: OSE
subtype: "Élevé pour sa force et son courage au combat. Adapté aux courtes accélérations pour charger ; ne convient pas à une chevauchée de longue distance."
image:
alignement: Neutre
ac: 7 (12)
hp: 13
hit_dice: 3D6
thaco: 17
speed: 36 m (12 m)
jds: [12, 13, 14, 15, 16, (2)]
roll_jds: 1d20
roll-moral: 2d6
moral: 9
xp: "35"
nbr: 0
nbr_dj: 0
loot:  Aucun
forceColumns: true
columns: 1
traits:
  - name: Charge
    desc: " Le cheval ne doit pas être engagé en mêlée. Il faut également un terrain dégagé d'au moins 20 m. Si elle touche, la lance du cavalier inflige le double de dégâts. Le cheval ne peut pas utiliser ses attaques naturelles lors de la charge."
  - name: Mêlée
    desc: "En mêlée, le cavalier et le cheval peuvent tous les deux attaquer."
actions:
  - name: 2x sabots 
    desc: D20 jet d'attaque, 3 (1d6) de dégâts 
source: OSE
```
---
