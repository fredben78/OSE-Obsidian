---
JDR: OSE
Type:
  - core
share: true
tags:
  - monster
statblock: inline
---
# `=this.file.name`

---
```statblock
layout: OSE
name: Cube gélatineux
subtype: "Cube de gelée transparente de 3 m de côté. Se déplace à travers les donjons en absorbant les détritus et les créatures vivantes qu’il rencontre."
image:
alignement: Neutre
ac: 8(11)
hp: 18
hit_dice: 4D8
thaco: 16(+3)
speed: 18m (9m)
jds: [12, 13, 14, 15, 16, (2)]
moral: 12
roll_jds: 1d20
roll-moral: 2d6
xp: "125"
nbr: 1 
nbr_dj: 0
loot: [[2. Treasure Types#Type V (330 po en moyenne)|V]]
forceColumns: true
columns: 1
traits:
  - name: Surprise
    desc: "Du fait de sa quasi-invisibilité, le cube gélatineux surprend 4-sur-6 fois."
  - name: Paralysie
    desc: "Dure 4 (2d4) tours (jet de sauvegarde contre la paralysie)."
  - name: Immunité naturelle
    desc: "Immunisé aux dégâts infligés par le froid ou la foudre"
  - name: Objets absorbés
    desc: "Les objets indigestes (par exemple, les gemmes ou les pièces) restent à l’intérieur du cube et sont transportés en semblant flotter dans l’air."
actions:
  - name: 1x Toucher
    desc: D20 jet d'attaque, 2 (2d4) de dégâts + Paralysie
source: OSE
```
---