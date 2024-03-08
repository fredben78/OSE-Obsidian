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
name: Ombre
subtype: "Créature incorporelle et intelligente, qui n’est pas morte-vivante, ressemble à une ombre. Sont capables de légèrement changer leur forme pour se camoufler."
image:
ac: 7(12)
hit_dice: 2D8+2
thaco: 17(+2)
speed: 27m (9m)
jds: [12,13,14,15,16,(2)]
moral: 12
alignement: Chaotique
xp: 35
nbr: 1d8
nbr_dj: 1d12
loot: [[2. Types de trésors#Type F (7 700 po en moyenne)|F]]
hp: 3
roll_jds: 1d20
roll-moral: 2d6
traits:
  - name: Surprise 
    desc: "Sur un 1-à-5."
  - name: Absorption de Force
    desc: "Les victimes perdent 1 point de FOR à chaque attaque réussie. Ces points sont récupérés après 8 tours. Si la FOR est réduite à 0, la victime devient une ombre."
  - name: Immunité aux dégâts normaux
    desc: "Ne peut être blessée que par des attaques magiques."
  - name: Immunité aux sorts
    desc: "Immunisée contre les sorts charme et sommeil."
actions:
  - name: 1x Toucher
    desc: D20 jet d'attaque, 2 (1d4) de dégâts + Absorption de force
source: OSE
```
---
