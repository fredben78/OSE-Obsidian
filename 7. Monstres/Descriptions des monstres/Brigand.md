---
JDR: OSE
Type:
  - core

tags:
  - monster
statblock: true
---
# `=this.file.name`

---
```statblock
layout: OSE
name: Brigand
subtype: "Hors-la-loi et mercenaire qui vit de pillages et attaque les voyageurs."
image:
alignement: Chaotique
ac: 6(13)
hp: 4
hit_dice: 1D8
thaco: 19 v(0)
speed: 36m (12m)
jds: [12, 13, 14, 15, 16, (1)]
roll_jds: 1d20
moral: 8
roll-moral: 2d6
xp: "10"
nbr: 0
nbr_dj: 1d4*10
loot: [[2. Types de trésors#Type A (18 000 po en moyenne)|A]]
forceColumns: true
columns: 2
traits:
  - name: Infanterie
    desc: "Une moitié est équipée avec : une armure légère, un bouclier, une épée, et un arc court."
  - name: Cavalerie
    desc: "L’autre moitié monte des chevaux de selle et est équipée avec : une cotte de mailles, un bouclier, et une épée."
  - name: Chefs et commandants
    desc: "Par groupe de 20 brigands, on trouve un chef (guerrier de 2e niveau). Par groupe de 40 brigands, on trouve un commandant (guerrier de 4e niveau). Les chefs montent des chevaux de guerre (avec protections supplémentaires : un caparaçon) et sont équipés avec : une armure de plates, une épée et une lance."
  - name: Camps fortifiés
    desc: Les bandes se regroupent fréquemment et vivent dans des camps fortifiés abritant (5d6) x10 brigands.
  - name: Chefs de camps
    desc: "Les camps issus d’un regroupement sont dirigés par un guerrier de 9e niveau, auquel s’ajoute un guerrier de 5e niveau par groupe de 50 brigands. De plus, il y a 50 % de chances qu’il s’agisse d’un magicien niveau 9 (1d3+8) et 30 % de chance qu’il s’agisse d’un clerc (8e niveau)."
actions:
  - name: 1x arme
    desc: D20 jet d'attaque, 2 (1d6) de dégâts ou selon arme
source: OSE
```
---