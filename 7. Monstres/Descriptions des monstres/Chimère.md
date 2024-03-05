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
name: Chimère
subtype: "Horrible monstruosité hybride avec le torse et les pattes avant d’un lion, les pattes arrière d’une chèvre, les ailes d’un dragon et trois têtes : chèvre, lion et dragon. Habite dans les zones sauvages et vallonnées, ou parfois dans des donjons."
image:
alignement: Chaotique
ac: 4(15)
hp: 40
hit_dice: 9D8
thaco: 12 (+7)
speed: 36m (12m) / 54m (18m) vol
jds: [8, 9, 10, 10, 12, (9)]
roll_jds: 1d20
roll-moral: 2d6
moral: 9
xp: "2300"
nbr: 1d2 
nbr_dj: 1d4
loot: [[2. Treasure Types#Type F (7 700 po en moyenne)|F]]
forceColumns: true
columns: 1
traits:
  - name: Schéma d’attaque
    desc: "Tête de dragon :  50 (1d100) % de chances de réaliser une attaque de souffle, sinon morsure."
  - name: Souffle
    desc: "Cône de feu : Long de 15 m, large à l’extrémité de 3 m. Peut être utilisé jusqu’à trois fois par jour."
actions:
  - name: "2x griffes"
    desc: D20 jet d'attaque, 2 (1d3) de dégâts
  - name: "1x corne chèvre"
    desc: D20 jet d'attaque, 2 (2d4) de dégâts
  - name: 1x morsure morsure
    desc: D20 jet d'attaque, 2 (2d4) de dégâts
  - name: 1x morsure dragon
    desc: D20 jet d'attaque, 2 (3d4) de dégâts
  - name: 1x souffle dragon
    desc: D20 jet d'attaque, 2 (3d6) de dégâts
source: OSE
```
---