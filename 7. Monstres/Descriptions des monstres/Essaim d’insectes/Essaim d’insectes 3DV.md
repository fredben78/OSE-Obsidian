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
name: Essaim d’insectes 2DV
subtype: "Essaim de nombreux insectes minuscules que l’on peut rencontrer protégeant leur nid. Ils peuvent également être attirés par la lumière ou les odeurs inhabituelles."
image:
ac: 7(12)
hit_dice: 3D8
thaco: 17(+2)
speed: 9m (3m) / 18m (6m) vol
jds: [14,15,16,17,18,(HN)]
moral: 11
alignement: Neutre
xp: 35
nbr: 1
nbr_dj: 1d3
loot: Aucun
hp: 3
roll_jds: 1d20
roll-moral: 2d6
traits:
  - name: Type et locomotion
    desc: "Un essaim peut se composer de créatures rampantes (par exemple : araignées, fourmis, mille-pattes) ou volantes (par exemple : abeilles, frelons). Certains essaims possèdent les deux types de mouvement (par exemple : scarabées, sauterelles)."
  - name: Taille
    desc: "Occupe généralement une surface de 3 m × 9 m."
  - name: Immunité
    desc: "Seulement blessé par le feu, le froid extrême, les sortilèges de sommeil (affectant l’essaim entier), la fumée (qui les fait fuir) ou d’autres attaques au souhait de l’arbitre."
  - name: Attaque de l’essaim
    desc: "Blesse automatiquement tout personnage se trouvant dans la zone de l’essaim : 2 points de dégâts si l’on porte une armure, 4 sans."
  - name: Repousser
    desc: "Les personnages à l’intérieur de l’essaim qui se défendent en brandissant une arme (ou similaire) subissent la moitié des dégâts de l’essaim. Une torche brandie blesse l’essaim."
  - name: S’échapper
    desc: "En s’échappant de l’essaim, les personnages continuent de subir la moitié des dégâts jusqu’à ce que 3 rounds soient passés à écraser les insectes restés attachés."
  - name: Plonger dans l’eau
    desc: "Le personnage subit des dégâts pendant un round, puis les insectes attachés se noient."
  - name: Poursuite
    desc: "Un essaim énervé (c’est-à-dire blessé) poursuivra les personnages jusqu’à ce qu’ils soient hors de vue ou inaccessibles."
actions:
  - name: 1x Essaim
    desc: D20 jet d'attaque,  2 points de dégâts si l’on porte une armure, 4 sans.
source: OSE
```
---
