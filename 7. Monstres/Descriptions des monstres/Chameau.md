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
name: Chameau
subtype: "Animal irascible adapté à la vie dans les climats secs et souvent employé pour le transport dans les déserts."
image:
alignement: Neutre
ac: 7(12)
hp: 9
hit_dice: 2D8
thaco: 18 (+1)
speed: 45m (15m)
jds: [12, 13, 14, 15, 16, (1)]
moral: 7
roll_jds: 1d20
roll-moral: 2d6
xp: "20"
nbr: 0
nbr_dj: 2d4
loot: Aucun
forceColumns: true
columns: 1
traits:
  - name: De mauvaise humeur
    desc: " Il mord ou donne un coup de pied aux créatures sur son chemin, y compris ses propriétaires."
  - name: Eau
    desc: "Après avoir bien bu, il peut survivre 2 semaines sans eau."
  - name: Voyage dans le désert
    desc: "Se déplace à pleine vitesse à travers les terres ravagées et les déserts."
  - name: Bête de somme 
    desc: "Peut transporter jusqu’à 3 000 pièces en charge normale et jusqu’à 6 000 pièces surchargé et à la moitié de sa vitesse."
  - name: Charge
    desc: "Il n’est pas possible de charger lorsqu’on est monté sur un chameau."
actions:
  - name: 1x morsure et 1x sabot
    desc: D20 jet d'attaque, 1 (1d1) de dégâts
  - name: 1x sabot
    desc: D20 jet d'attaque, 2 (1d4) de dégâts
source: OSE
```
---
