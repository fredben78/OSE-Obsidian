---
JDR: OSE
Type:
  - core

tags:
  - monster
statblock: inline
aliases:
  - Fire giant
---
# `=this.file.name`


---
```statblock
layout: OSE
name: Géant du feu
subtype: "Humanoïde, haut de 4,80 m, aux cheveux noirs et à la peau rouge, s’habille en armures façonnées à partir de métaux dorés (laiton, bronze, cuivre). Habite dans des endroits à la chaleur extrême (par exemple, à proximité des volcans)."
image:
ac: 4(+15)
hit_dice: 11D8+2
thaco: 10(+9)
speed: 36m (12m)
jds: [6,7,8,8,10,(11)]
moral: 9
alignement: Chaotique
xp: "1100"
nbr: 1d2
nbr_dj: 1d3
loot: [[2. Types de trésors#Type E (2 300 po en moyenne)|E]] + 5000po
hp: 3
roll_jds: 1d20
roll-moral: 2d6
forceColumns: true
columns: 1
traits:
  - name: Lancer de rochers
    desc: "Jusqu’à 60 m."
  - name: Immunité au feu
    desc: "Immunisé aux dégâts de feu."
  - name: Château
    desc: "Noir, aux murailles basses. Fait en terre cuite et en fer brut."
  - name: Gardiens
    desc: "20 % 50 (1d100) de chances d’être accompagné par 2 (1d3) [[Hydra|hydres]] ; sinon, par 8 (3d6) [[Molosse satanique|molosses sataniques]]."
actions:
  - name: 1x Arme
    desc: D20 jet d'attaque, 2 (5d6) de dégâts
  - name: ou 1x Rocher
    desc: D20 jet d'attaque, 2 (3d6) de dégâts
source: OSE
```
---
