---
JDR: OSE
Type:
  - core

tags:
  - monster
statblock: inline
aliases:
  - Gorgon
---
# `=this.file.name`


---
```statblock
name: Gorgone
layout: OSE
subtype: "Monstre magique ressemble à un taureau couvert d’écailles. Il habite dans les plaines ou les collines."
image:
ac: 2(17)
hit_dice: 8D8
thaco: 12(+7)
speed: 36m (12m)
jds: [8,9,10,10,12,(8)]
moral: 8
alignement: Chaotique
xp: "1200"
nbr: 1d2
nbr_dj: 1d4
loot: [[2. Types de trésors#Type E (2 300 po en moyenne)|E]]
hp: 3
roll_jds: 1d20
roll-moral: 2d6
forceColumns: true
columns: 1
traits:
  - name: Charge
    desc: "Lorsqu’elle n’est pas encore engagée en mêlée. Nécessite une trajectoire dégagée d’au moins 20 m entre elle et sa cible. Ses cornes infligent alors le double de dégâts."
  - name: Souffle pétrifiant
    desc: "Nuage de 18 m de long et de 3 m de large. Tout créature prise dedans est transformée en pierre (Jet de sauvegarde contre la pétrification pour l’éviter). Pas affectée par son propre souffle."
actions:
  - name: 1x Corne
    desc: D20 jet d'attaque, 2 (2d6) de dégâts
  - name: 1x Souffle
    desc: D20 jet d'attaque, Pétrification
source: OSE
```
---
