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
name: Boucanier
subtype: "Un marin qui vit de raids côtiers et d’abordages de bateaux. Il sillonne les rivières, les lacs et les côtes, plus rarement les océans."
image:
alignement: Neutre
ac: 7(12) ou 5(14)
hp: 4
hit_dice: 1D8
thaco: 19 (0)
speed: 36m (12m)
jds: [12, 13, 14, 15, 16, (1)]
roll_jds: 1d20
moral: 6
roll-moral: 2d6
xp: "10"
nbr: 0 (voir ci dessous) 
loot: [[2. Types de trésors#Type A (18 000 po en moyenne)|A]]
forceColumns: true
columns: 2
traits:
  - name: Bateaux et équipages
    desc: "Ils dépendent de l’endroit où on les rencontre. \n -Sur les rivières et les lacs : 4 (1d8) embarcations fluviales accueillant chacune 10 (1d2) ×10 boucaniers ; \n -Sur les côtes, 3 (1d6) petites galère(s) accueillant chacune 20 (1d3+1) × 10 boucaniers ; \n -Partout : 2 (1d4) drakkar(s) accueillant chacun 3 (1d3+2) ×10 boucaniers ; \n -Océans : 2 (1d4) navires de guerre accueillant chacun 5 (1d5+3) × 10 boucaniers (voir [[7. Embarcations#Navires de haute mer|Embarcations]] pour les détails sur les navires)."
  - name: Armement
    desc: "60 % du groupe est équipé avec : une armure de cuir, une épée ; 30 % est équipé avec : une armure de cuir, une épée, une arbalète ; 10 % est équipé avec : une cotte de mailles, une épée, une arbalète."
  - name: Chefs et capitaines 
    desc: "Par groupe de 30 boucaniers, on trouve un guerrier de 4e niveau. Chaque navire possède un capitaine (guerrier de 7e niveau)."
  - name: Commandant de flotte
    desc: "Guerrier de 9e niveau ; 30 % de chances qu’il s’agisse d’un magicien (niveau 10 (1d2+9)) ; 25 % de chances qu’il s’agisse d’un clerc (8e niveau)."
  - name: Trésor
    desc: "Il est réparti entre les différents navires. Au lieu d’être transporté à bord, il peut y avoir une carte indiquant l’endroit où il est enterré."
  - name: Havres
    desc: "Les villes côtières sans loi et fortifiées peuvent servir de havre pour les boucaniers et les pirates."
actions:
  - name: 1x arme 
    desc: D20 jet d'attaque, 2 (1d6) de dégâts ou selon arme
source: OSE
```
---