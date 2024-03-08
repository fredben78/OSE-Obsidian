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
name: Loup normal
subtype: "Trouvé le plus souvent dans les contrées sauvages, mais niche parfois dans des grottes."
image:
ac: 7(12)
hit_dice: 2D8+2
thaco: 17(+2)
speed: 54m (18m)
jds: [12,13,14,15,16,(1)]
moral: "6 (8 pour une meute importante)" 
alignement: Neutre
xp: "25"
nbr: 2d6
nbr_dj: 3d6
loot: Aucun
hp: 3
roll_jds: 1d20
roll-moral: 2d6
forceColumns: true
columns: 1
traits:
  - name: Dressage
    desc: "À la discrétion de l’arbitre, les louveteaux capturés peuvent être dressés comme des chiens. Les loups adultes ne se laissent pas dresser facilement."
  - name: L’union fait la force
    desc: "Les meutes de 4 loups ou plus ont un moral de 8. Ce bonus est perdu si la meute est réduite de moitié."
actions:
  - name: 1x Morsure
    desc: D20 jet d'attaque, 2 (1d6) de dégâts
source: OSE
```
---
