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

*De 1 à 2 DV*

---
```statblock
layout: OSE
name: Petit troupeau
subtype: "Ces animaux sauvages vivent dans les pâturages en grands troupeaux. Le type exact dépend du terrain. Par exemple : antilope, cerf, chèvre."
image:
ac: 7(12)
hit_dice: 1D8 
thaco: 19
speed: 72m (24m)
jds: [12,13,14,15,16,(1)]
moral: 5
alignement: Neutre
xp: "10/20"
nbr: 0
nbr_dj: 3d10
loot: Aucun
hp: 3
roll_jds: 1d20
roll-moral: 2d6
forceColumns: true
columns: 1
traits:
  - name: Débandade
    desc: "Les troupeaux de 20 individus ou plus peuvent piétiner ceux qui se trouvent sur leur passage. 3-sur-4 chances à chaque round. Bonus de +4 pour toucher les créatures de taille humaine ou plus petites. 10 (1d20) points de dégâts."
  - name: Mâles
    desc: "Dans les groupes de 3 individus ou plus, un quart seulement sont des mâles. Ils ont 2 (1d4) points de vie supplémentaires et protègent le troupeau."
  - name: Femelles et petits
    desc: "Ils fuient le danger. Les femelles n’ont pas d’attaque de percussion. Les petits n’ont que la moitié des points de vie."
  - name: Piétinement
    desc: "Les troupeaux de 20 individus ou plus peuvent piétiner ceux qui se trouvent sur leur passage. 3-sur-4 chances à chaque round. Bonus de +4 pour toucher les créatures de taille humaine ou plus petites. 1d20 points de dégâts."
actions:
  - name: 1x percussion
    desc: D20 jet d'attaque, 2 (1d4) de dégâts
source: OSE
```
---
