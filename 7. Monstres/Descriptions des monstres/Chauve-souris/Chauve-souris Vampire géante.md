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
name: Chauve-souris vampire géante
layout: OSE
subtype: 
columns: 1
image:
alignement: Neutre
ac: 6(13)
hp: 9
hit_dice: 2D6
thaco: 18
speed: 9m (3m) / 54m (18m) vol
jds: [12, 13, 14, 15, 16, (1)]
moral: 8
roll_jds: 1d20
roll-moral: 2d6
xp: "20"
nbr: 1d10
nbr_dj: 1d10
loot:  Aucun
forceColumns: true
columns: 1
traits:
  - name: Écholocation
    desc: "Insensible aux effets qui nuisent à, modifient ou dépendent de la vue. Aveuglée par un silence d’origine magique."
  - name: Inconscience
    desc: "Pour 5 (1d10) rounds (jet de sauvegarde contre la paralysie)."
  - name: Absorption de sang
    desc: "Une chauve-souris vampire peut boire le sang d’une victime inconsciente : 2 (1d4) points de dégâts automatiques par round. Une victime qui meurt de cette absorption de sang devient un mort-vivant (peut-être un vampire) au bout de 24 h (jet de sauvegarde contre les sorts)."
actions:
  - name: 1x morsure
    desc: D20 jet d'attaque, 2 (1d4) de dégâts + inconscience
source: OSE>)
```
---
