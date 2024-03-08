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
name: Serpent de mer
subtype: "Serpent de 1,80 m de long, vivant sous l’eau. Ne remonte pour respirer qu’une fois par heure et peut attaquer les humains."
image:
ac: 6(13)
hit_dice: 3D8
thaco: 17(+2)
speed: 27m (9m)
jds: [12,13,14,15,16,(2)]
moral: 7
alignement: Neutre
xp: 50
nbr: 1d8
nbr_dj: 1d8
loot: Aucun
hp: 3
roll_jds: 1d20
roll-moral: 2d6
traits:
  - name: Morsure minuscule
    desc: "50% de chances de passer inaperçue."
  - name: Poison, Action lente
    desc: "les effets sont ressentis après 4 (1d4+2) tours. Jet de sauvegarde contre le poison ou mort 1 tour plus tard. À ce stade, le sort contre-poison a 25% de chances de ne pas fonctionner."
  - name: Grands individus
    desc: "Il est possible de rencontrer des serpents de mer avec plus de 3 DV. Ils mesurent alors 1,80 m de long pour chaque tranche de 3 DV."
actions:
  - name: 1x Morsure
    desc: D20 jet d'attaque, 1 (1d1) de dégâts + poison
source: OSE
```
---
