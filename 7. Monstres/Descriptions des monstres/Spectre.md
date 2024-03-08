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
name: Spectre
subtype: "Fantôme incorporel — l’un des monstres morts-vivants les plus puissants qui soient."
image:
ac: 2(17)
hit_dice: 6D8
thaco: 14(+5)
speed: 45m (15m) / 90m (30m) vol
jds: [10,11,12,13,14,(6)]
moral: 11
alignement: Chaotique
xp: 725
nbr: 1d4
nbr_dj: 1d8
loot: [[2. Types de trésors#Type E (2 300 po en moyenne)|E]]
hp: 3
roll_jds: 1d20
roll-moral: 2d6
traits:
  - name: Mort-vivant
    desc: "Ne fait aucun bruit, jusqu’à ce qu’il attaque. Immunisé contre les effets affectant les créatures vivantes (par exemple, le poison). Immunisé contre les sorts affectant ou lisant l’esprit (ex: charme, paralysie, sommeil)."
  - name: Immunité aux dégâts normaux
    desc: "Ne peut être blessé que par des attaques magiques."
  - name: Absorption d’énergie
    desc: "Une cible touchée avec succès perd deux niveaux d’expérience (ou Dés de vie) de manière permanente. Ceci entraîne la perte de points de vie correspondant aux DV de perdus, ainsi que les autres capacités dues aux niveaux perdus (sorts, jets de sauvegarde, etc.). \n L’XP du personnage est réduite au minimum du nouveau niveau. Une personne qui perd tous ses niveaux devient un spectre la nuit suivante, sous le contrôle du spectre qui l’a tuée."
actions:
  - name: 1x Toucher
    desc: D20 jet d'attaque, 2 (1d8) de dégâts + Absorption d'énergie
source: OSE
```
---
