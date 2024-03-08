---
JDR: OSE
Type:
  - core

tags:
  - monster
statblock: inline
---
# Basilic

---
```statblock
layout: OSE
name: Basilic
subtype: "Lézard de forme serpentine, long de 3 m, et dépourvu d’intelligence, mais hautement magique. Il niche dans les cavernes et les ronces épineuses."
image:
alignement: Neutre
ac: 4 (15)
hp: 28
hit_dice: 6D8+1
thaco: 13
speed: 18m (6m)
jds: [10, 11, 12, 13, 14, (6)]
roll_jds: 1d20
moral: 9
roll-moral: 2d6
xp: "950"
nbr: 1d6
nbr_dj: 1d6
loot: [[2. Types de trésors#Type F (7 700 po en moyenne)|F]]
forceColumns: true
columns: 2
traits:
  - name: "Surprise"
    desc: "Les personnages surpris par le basilic subissent une attaque de son regard pétrifiant."
  - name : "Toucher pétrifiant"
    desc: "Toute créature touchée par le basilic est transformée en pierre (jet de sauvegarde contre la pétrification)."
  - name: "Regard pétrifiant"
    desc: "Toute créature rencontrant le regard du basilic est transformée en pierre (jet de sauvegarde contre la pétrification). À moins d’éviter son regard ou d’utiliser un miroir, les personnes en mêlée contre le basilic sont affectées chaque round."
  - name: "Éviter son regard"
    desc: "Une personne qui cherche à combattre le basilic en évitant son regard subit un malus de –4 pour toucher, tandis que le basilic bénéficie d’un bonus de (+2)."
  - name: "Utiliser un miroir"
    desc: "Le reflet du basilic est inoffensif. Se battre en regardant dans un miroir inflige un malus de –1 à l’attaque. Si le basilic voit son propre reflet (2 chances sur 6), il doit effectuer un jet de sauvegarde ou être pétrifié."
actions:
  - name: "1x morsure"
    desc: D20 jet d'attaque, 5 (1d10) de dégâts + pétrification
  - name: "1x regard"
    desc: "Pétrification"
source: OSE
```
---


