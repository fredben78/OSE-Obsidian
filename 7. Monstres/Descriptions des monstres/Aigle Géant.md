---
JDR: OSE
Type:
  - core

tags:
  - monster
statblock: inline
---

## Aigle géant

----
```statblock
layout: OSE
name: Aigle Géant
subtype: "Oiseau de proie qui plane dans les courants d’air chauds et chasse ses proies au sol. "
other:
  - name: Dressage
    desc: Peut être dressé en tant qu’animal gardien ou de chasse."
image: 
alignement: Neutre
ac: 6 (13)
hp: 16
hit_dice: 3D6+3
thaco: 16 [+3]
speed: 135m (45m) vol
jds: [12, 13, 14, 15, 16, (2)]
roll_jds: 1d20
roll-moral: 2d6
moral: 8
xp: "50"
nbr: 0 
nbr_dj: 1d3
loot: Aucun
forceColumns: true
columns: 1
traits:
  - name: Descente en piqué
    desc: Peut plonger sur les victimes visibles en contrebas. Si la victime est surprise, l’attaque lui inflige le double de dégâts. Sur un jet d’attaque de 18 ou plus, la victime peut être emportée (à condition qu’elle soit de taille appropriée).
  - name: Transport de proies
    desc: Jusqu’à la taille d’un tinigens.
actions:
  - name: 1x Serre ou bec
    desc: D20 jet d'attaque, 3 (1d6) de dégâts
source: OSE
```
----