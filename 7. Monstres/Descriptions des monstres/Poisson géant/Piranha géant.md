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
name: Piranha géant
subtype: "Long de 1,50 m, avec des écailles noires et vertes. Vit dans les rivières (parfois les lacs) et attaque tout ce qui se trouve dans l’eau."
image:
alignement: Neutre
ac: 6(13)
hp: 3
hit_dice: 3D8+3
thaco: 16 (+3)
speed: 45m (15m)
jds: [12,13,14,15,16,(2)]
moral: 7
roll_jds: 1d20
roll-moral: 2d6
nbr_dj: 2d4
xp: "50"
nbr: 0
loot: Aucun
traits:
  - name: Encerclement
    desc: "Jusqu’à 8 piranhas géants peuvent attaquer la même cible."
  - name: Moral
    desc: "Lorsqu’il y a des traces de sang dans l’eau, pas de test de moral."
actions:
  - name: 1x Morsure
    desc: D20 jet d'attaque, 2 (1d8) de dégâts
source: OSE
```
---
