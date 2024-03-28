---
JDR: OSE
Type:
  - core

tags:
  - monster
statblock: inline
aliases:
  - Saltwater termite
---
# `=this.file.name`


---
```statblock
layout: OSE
name: Termite d’eau salée
subtype: "Insecte aquatique géant, faisant entre 30 cm à 1,50 m de longueur, qui se nourrit de bois et muni d’une poche leur permettant d’absorber et de projeter de l’eau. Aime se nourrir des navires qui passent, et n’attaquent des créatures que s’ils sont acculés."
image:
ac: 5(14)
hit_dice: 4D8
thaco: 16(+3)
speed: 54m (18m)
jds: [12,13,14,15,16,(3)]
moral: 11
alignement: Neutre
xp: 75
nbr: 0
nbr_dj: 1d6+1
loot: Aucun
hp: 3
roll_jds: 1d20
roll-moral: 2d6
traits:
  - name: Projection irritante
    desc: "Utilisable en surface; maximum une fois par tour. Peut projeter sur une cible, qui doit effectuer un jet de sauvegarde contre le poison ou être étourdie pendant 1 tour."
  - name: Nuage d’encre
    desc: "Utilisable sous l’eau et au maximum une fois par tour. En s’échappant, le termite aquatique peut émettre un nuage d’encre noire afin de troubler ses ennemis."
  - name: Mange les navires
    desc: "Elles s’accrochent sous la coque. Chaque individu inflige 1 (1d3) points de dégâts de structure, puis se décolle.\n Remarquer les dégâts sur un navire: 50% de chances par round de détecter des voies d’eau."
actions:
  - name: 1x Morsure
    desc: D20 jet d'attaque, 2 (1d6) de dégâts
  - name: ou 1x Projection
    desc: D20 jet d'attaque, étourdissement
source: OSE
```
---
