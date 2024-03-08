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
name: Nécrophage
subtype: "Cadavre d’humain ou de semi-humain, possédé par un esprit malveillant."
image:
ac: 5(14)
hit_dice: 3D8
thaco: 17(+2)
speed: 27m (9m)
jds: [12,13,14,15,16,(3)]
moral: 12
alignement: Chaotique
xp: 50
nbr: 1d6
nbr_dj: 1d8
loot: [[2. Types de trésors#Type B (2 000 po en moyenne)|B]]
hp: 3
roll_jds: 1d20
roll-moral: 2d6
traits:
  - name: Mort-vivant
    desc: "Ne fait aucun bruit jusqu’à ce qu’il attaque. Immunisé contre les effets affectant les créatures vivantes (par exemple, le poison). Immunisé contre les sorts affectant ou lisant l’esprit (par exemple, charme, paralysie, sommeil)."
  - name: Immunité aux armes normales
    desc: "Uniquement affecté par des armes en argent ou magiques."
  - name: Absorption d’énergie
    desc: "Une cible touchée avec succès perd un niveau d’expérience (ou Dé de vie) de manière permanente. Ceci entraîne la perte de points de vie correspondant au DV de perdu, ainsi que les autres capacités dues aux niveaux perdus (sorts, jets de sauvegarde, etc.). L’XP du personnage est ramenée à mi-chemin entre l’ancien et le nouveau niveau. Une personne qui perd tous ses niveaux devient un nécrophage en 2 (1d4) jours, sous le contrôle du nécrophage qui l’a tuée."
actions:
  - name: 1x Toucher
    desc: D20 jet d'attaque, Absorption d'énergie
source: OSE
```
---
