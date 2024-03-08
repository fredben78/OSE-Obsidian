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
name: Cyclope
subtype: "Humanoïdes hauts de 6 m, qui possèdent un unique œil central et habitent dans les grottes, seuls ou en petits groupes. Cultivent la vigne et élèvent des moutons."
image:
alignement: Chaotique
ac: 5(14)
hp: 58
hit_dice: 13D8
thaco: 10 (+9)
speed: 27m (9m)
jds: [4, 5, 6, 5, 8, (13)]
roll_jds: 1d20
roll-moral: 2d6
moral: 9
xp: "2300"
nbr: 1  
nbr_dj: 1d4
loot: [[2. Types de trésors#Type E (2 300 po en moyenne)|E]] + 5000 PO
forceColumns: true
columns: 1
traits:
  - name: Malus à l’attaque
    desc: "Malus de –2 sur tous les jets pour toucher, à cause de leur difficulté à estimer les distances"
  - name: Lancer de pierres
    desc: "Jusqu’à 60 m."
  - name: Esprit lent 
    desc: "Peut être trompé par des PJ intelligents."
  - name: Malédiction 
    desc: "1 cyclope sur 20 a la capacité de jeter des malédictions. Il peut le faire une fois par semaine. La cible doit réussir un jet de sauvegarde contre les sorts ou être affligée par une malédiction choisie par l’arbitre. \n Effets possibles maximums Malus de –2 aux jets de sauvegardes, malus de –4 pour toucher, une caractéristique réduite de 50%."
actions:
  - name: 1x gourdin
    desc: D20 jet d'attaque, 2 (3d10) de dégâts
  - name: ou 1x rocher
    desc: D20 jet d'attaque, 2 (3d6) de dégâts
source: OSE
```

---
