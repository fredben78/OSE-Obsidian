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
name: Roc Géant
subtype: "Ce gigantesque rapace niche dans les plus hauts sommets de chaînes de montagnes isolées. Attaque les intrus si on l’approche négligemment."
image:
ac: 0(19)
hit_dice: 36D8
thaco: 5(+14)
speed: 18m (6m) / 144m (48m) vol
jds: [2,3,4,3,6,(18)]
moral: 10 (12 dans son repaire)
alignement: Loyal
xp: 6250
nbr: 0
nbr_dj: 1
loot: [[2. Types de trésors#Type I (11 000 po en moyenne)|I]]
hp: 3
roll_jds: 1d20
roll-moral: 2d6
traits:
  - name: Réaction d’alignement
    desc: "Malus de –1 aux jets de réaction contre les personnages neutres; malus de –2 contre les personnages chaotiques."
  - name: Descente en piqué
    desc: "Peut plonger sur les victimes visibles en contrebas. Si la victime est surprise, l’attaque lui inflige doubles dégâts. Sur un jet d’attaque de 18 ou plus, la victime peut être emportée (à condition qu’elle soit de taille appropriée)."
  - name: Œufs
    desc: "50% des nids contiennent 3 (1d6) œufs ou poussins."
  - name: Dressage
    desc: "Peut être dressé s’il est capturé jeune."
actions:
  - name: 2x Serre
    desc: D20 jet d'attaque, 2 (3d6) de dégâts
  - name: 1x Morsure
    desc: D20 jet d'attaque, 2 (8d6) de dégâts
source: OSE
```
---
