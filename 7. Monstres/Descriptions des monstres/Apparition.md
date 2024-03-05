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
name: Apparition
subtype: "Monstre mort-vivant incorporel qui apparaît comme une forme pâle et humaine de brume regroupée. Habite dans les régions désertiques ou dans les maisons ayant appartenu à d’anciennes victimes."
image:
ac: 3(16)
hit_dice: 4D8
thaco: 16(+3)
speed: 36m (12m) / 72m (24m) vol
jds: [10,11,12,13,14,(4)]
moral: 12
alignement: Chaotique
xp: 175
nbr: 1d4
nbr_dj: 1d6
loot: [[2. Treasure Types#Type E (2 300 po en moyenne)|E]]
hp: 3
roll_jds: 1d20
roll-moral: 2d6
traits:
  - name: Mort-vivant
    desc: "Ne fait aucun bruit jusqu’à ce qu’elle porte son attaque. Immunisée contre les effets affectant les créatures vivantes (par ex., le poison). Immunisée contre les sorts affectant ou lisant l’esprit (par ex., charme, paralysie, sommeil)."
  - name: Immunité aux armes normales
    desc: "Uniquement affectée par des armes en argent ou magiques."
  - name: Réduction des dégâts
    desc: "Ne reçoit que la moitié des dégâts des armes en argent."
  - name: Absorption d’énergie
    desc: "Une cible touchée avec succès perd un niveau d’expérience (ou Dé de vie) de manière permanente. Ceci entraîne la perte de points de vie correspondant au DV de perdu, ainsi que les autres capacités dues aux niveaux perdus (sorts, jets de sauvegarde, etc.). L’XP du personnage est réduite au minimum du nouveau niveau. Une personne qui perd tous ses niveaux devient une apparition en une journée, sous le contrôle de celle qui l’a tuée."
actions:
  - name: 1x toucher
    desc: D20 jet d'attaque, 2 (1d6) de dégâts + absorption d'énergie
source: OSE
```
---
