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
name: Pirate
subtype: "Ces marins gagnent leur vie en attaquant les villages côtiers, en volant d’autres navires et en faisant commerce illégal d’esclaves. On les croise généralement en haute mer. Réputés pour leur conduite mauvaise, ils sont impitoyables."
image:
ac: 7(12) ou 5
hit_dice: 1D8
thaco: 19(0)
speed: 36m (12m)
jds: [12,13,14,15,16,(1)]
moral: 7
alignement: Chaotique
xp: 10 
nbr: 0
nbr_dj: (voir ci-dessous)
loot: [[2. Treasure Types#Type A (18 000 po en moyenne)|A]]
hp: 3
roll_jds: 1d20
roll-moral: 2d6
traits:
  - name: Navires et équipage
    desc: "Ils dépendent de l’endroit où on rencontre les pirates. \n Rivières ou lacs: 4 (1d8) bateaux fluviaux avec chacun 1 (1d2) × 10 pirates \n Eaux côtières: 3 (1d6) petites galères avec chacune 2 (1d3+1) × 10 pirates \n Tous: drakkars 2 (1d4) avec chacun 2 (1d3+2) × 10 pirates \n Océan:  1 (1d3) petits navires de guerre avec chacun 4 (1d5+3) × 10 pirates."
  - name: Armes
    desc: "50 % du groupe est équipé avec : une armure de cuir et une épée \n 35 % est équipé avec : une armure de cuir, une épée et une arbalète \n 15 % est équipé avec : une cotte de mailles et une épée."
  - name: Chefs
    desc: "Par groupe de 30 pirates, on trouve un guerrier de 4e niveau. \n Par groupe de 50 pirates et pour chaque navire, un guerrier de 5e niveau. \n Par groupe de 100 pirates et par flotte, un guerrier de 8e niveau."
  - name: Commandant de flotte
    desc: "Les flottes de 300 pirates ou plus sont dirigées par un seigneur pirate (guerrier de 11eniveau). 75 % de chances qu’il y ait un magicien de niveau 10 (1d2+8)."
  - name: Traître
    desc: "Les pirates n’hésitent pas à attaquer d’autres pirates, s’ils y trouvent leur profit."
  - name: Prisonniers
    desc: "Il y a 25 % de chances de demandes de rançons pour 1 (1d3) de leurs prisonniers."
  - name: Trésor
    desc: "Réparti entre les vaisseaux de la flotte. Au lieu de l’avoir à bord, ils peuvent avoir une carte de l’endroit où il est enterré."
  - name: Havres
    desc: "Les villes côtières fortifiées où aucune loi n’a cours peuvent constituer un refuge pour les pirates."
actions:
  - name: 1x Arme
    desc: D20 jet d'attaque, 2 (1d) de dégâts ou selon l'arme
source: OSE
```
---
