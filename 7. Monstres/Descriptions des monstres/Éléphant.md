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
name: "Éléphant"
subtype: "Ces animaux à défenses, massifs, habitent près des forêts subtropicales et se rencontrent soit en individus isolés soit en troupeaux entiers."
image:
alignement: Neutre
ac: 5(14)
hp: 3
hit_dice: 9D8
thaco: 12 (+7)
speed: 27m (9m)
jds: [10 , 11, 12, 13, 14 (5)]
moral: 8
roll_jds: 1d20
roll-moral: 2d6
xp: "900"
nbr: 0
nbr_dj: 1d20
loot: Défenses
traits:
  - name: Charge
    desc: "Au premier round de combat, lorsqu’il n’est pas encore engagé dans la mêlée. Nécessite une trajectoire dégagée d’au moins 20 m entre lui et sa cible. Les défenses infligent alors le double des dégâts."
  - name: Piétinement
    desc: "3-sur-4 chancesde piétiner à chaque round. Bonus de +4 pour toucher les créatures de taille humaine ou plus petites."
  - name: Ivoire
    desc: "Chaque défense vaut 3 (1d6) × 100 po."
actions:
  - name: 2x Défenses
    desc: D20 jet d'attaque, 2 (2d4) de dégâts
  - name: ou 1x Piétinements
    desc: D20 jet d'attaque, 2 (4d8) de dégâts
source: OSE
```
---