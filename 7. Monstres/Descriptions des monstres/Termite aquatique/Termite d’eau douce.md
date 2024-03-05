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
name: Termite aquatique
subtype: "Insecte aquatique géant, faisant entre 30 cm à 1,50 m de longueur, qui se nourrit de bois et muni d’une poche leur permettant d’absorber et de projeter de l’eau. Aime se nourrir des navires qui passent, et n’attaquent des créatures que s’ils sont acculés."
image:
ac: 6(13)
hit_dice: 2D8+1
thaco: 17(+2)
speed: 36m (12m)
jds: [12,13,14,15,16,(2)]
moral: 8
alignement: Neutre
xp: 25
nbr: 0
nbr_dj: 1d3
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
    desc: D20 jet d'attaque, 2 (1d4) de dégâts
  - name: ou 1x Projection
    desc: D20 jet d'attaque, étourdissement
source: OSE
```
---
