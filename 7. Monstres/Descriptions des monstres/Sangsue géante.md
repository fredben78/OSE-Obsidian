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
name: Sangsue géante
subtype: "Horrible créature, de 1 m à 1,20 m de long, ressemblant à une limace avec des bouches à ventouses. Se cache dans les marais."
image:
ac: 7(12)
hit_dice: 6D8
thaco: 14(+5)
speed: 27m (9m)
jds: [12,13,14,15,16,(3)]
moral: 10
alignement: Neutre
xp: 275
nbr: 0
nbr_dj: 1d4
loot: Aucun
hp: 3
roll_jds: 1d20
roll-moral: 2d6
traits:
  - name: Absorption de sang
    desc: "S’attache à la victime si l’attaque est réussie, infligeant 3 (1d6) points de dégâts automatiques par round."
  - name: Détachement
    desc: "Doit être tuée."
  - name: Si la victime meurt
    desc: "La sangsue se détache et trouve un endroit caché pour digérer."
actions:
  - name: 1x Morsure
    desc: D20 jet d'attaque, 2 (1d6) de dégâts + Absorption de sang
  - name:
    desc: D20 jet d'attaque, 2 (1d3) de dégâts
source: OSE
```
---
