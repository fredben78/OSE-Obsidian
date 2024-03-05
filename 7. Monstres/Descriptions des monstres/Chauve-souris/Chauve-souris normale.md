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
name: Chauve-souris
subtype: "Mammifère volant nocturne qui perche dans les cavernes et les ruines."
layout: OSE
image:
alignement: Neutre
ac: 6(13)
hp: 1
hit_dice: 1D1
thaco: 20
speed: 3m (1m) / 36 m (18m) vol
jds: [14, 15, 16, 17, 18 (HN)]
moral: 6
roll_jds: 1d20
roll-moral: 2d6
xp: "5"
nbr: 1d100
nbr_dj: 1d100
loot:  Aucun
forceColumns: true
columns: 1
traits:
  - name: Écholocation
    desc: "Insensible aux effets qui nuisent à, modifient ou dépendent de la vue. Aveuglée par un silence d’origine magique."
  - name: Essaim
    desc: "10 chauves-souris peuvent tourner en essaim autour de la tête d’une cible, la plongeant en pleine confusion : malus de –2 aux jets d’attaques et de sauvegardes ; impossibilité de lancer des sorts."
  - name: Attaques
    desc: "Comme un humain normal."
  - name: Peureux
    desc: "À moins d’être convoquées ou contrôlées magiquement, les chauves-souris normales doivent effectuer un jet de moral chaque round ou fuir."
actions:
  - name: 1x essaim (confusion)
    desc: D20 jet d'attaque, 2 (1d3) de dégâts 
source: OSE
```
---
