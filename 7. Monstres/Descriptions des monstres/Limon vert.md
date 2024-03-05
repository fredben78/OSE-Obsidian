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
name: Limon vert
layout: OSE
subtype: "Gelée verdâtre, dégoulinante, qui grimpe aux murs et au plafond."
image:
ac: aucun jet de toucher nécessaire
hit_dice: 2D8
thaco: 18(+1)
speed: 1m (30cm)
jds: [12,13,14,15,16,(1)]
moral: 12
alignement: Neutre
xp: "25"
nbr: 1
nbr_dj: 0
loot: Aucun
hp: 3
roll_jds: 1d20
roll-moral: 2d6
forceColumns: true
columns: 1
traits:
  - name: Surprise
    desc: "Se laisse tomber sur les personnages surpris."
  - name: Acide
    desc: "Lorsqu’en contact avec sa victime, se colle à elle et exsude un acide détruisant le bois et le métal (y compris les armures) en 6 rounds, mais n’affectant pas la pierre."
  - name: Dévorer la chair
    desc: "Après 6 rounds en contact avec la chair de sa victime, cette dernière est transformée en limon vert au bout de 2 (1d4) rounds supplémentaires."
  - name: Retirer
    desc: "Une fois collé à sa victime, il ne se détache que s’il est détruit par le feu. Les dégâts sont en ce cas partagés équitablement entre le limon et la victime."
  - name: Immunité
    desc: "Seules les attaques de froid et de feu peuvent blesser le limon."
actions:
  - name: 1x Toucher
    desc: D20 jet d'attaque, Dévorer la chair
  - name:
    desc: D20 jet d'attaque, 2 (1d3) de dégâts
source: OSE
```
---
