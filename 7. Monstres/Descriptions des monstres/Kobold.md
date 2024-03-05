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
layout: OSE
name: Kobold
subtype: "Petit humanoïde à l’aspect canin et dont la peau écailleuse est couleur rouille. Cette créature mauvaise et vicieuse vit sous terre."
image:
ac: 7(12)
hit_dice: 1D4
thaco: 19(0)
speed: 18m (6m)
jds: [14,15,16,17,18,(HN)]
moral: "6 (8 avec un chef de tribu)"
alignement: Chaotique
xp: "5 (garde du corps : 15, chef de tribu : 20)"
nbr: 4d4
nbr_dj: 6d10
loot: [[2. Treasure Types#Type P (0,1 po en moyenne)|P]] ([[2. Treasure Types#Type J (25 po en moyenne)|J]])
hp: 3
roll_jds: 1d20
roll-moral: 2d6
traits:
  - name: Embuscade 
    desc: "Préfèrent attaquer par surprise."
  - name: Infravision
    desc: "27m"
  - name: Haine des gnomes
    desc: "Le kobold les attaque à vue."
  - name: Chef et gardes du corps
    desc: "Dans leur repaire vivent un chef de tribu avec 2 DV (9 pv) et 1d6 gardes du corps avec 1+1 DV (6 pv)."
  - name: Butin
    desc: "Dans les contrées sauvages ou dans leur repaire, seul le trésor de type J est présent."
actions:
  - name: 1x Arme 
    desc: D20 jet d'attaque, 2 (1d4-1) de dégâts ouselon l'arme -1
source: OSE
```
---
