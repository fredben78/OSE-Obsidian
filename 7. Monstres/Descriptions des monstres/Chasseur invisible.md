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
name: Chasseur invisible
subtype: "Créature magique très intelligente convoquée depuis un autre plan d’existence pour servir un puissant magicien."
image:
alignement: Neutre
ac: 3(16)
hp: 3
hit_dice: 8D8
thaco: 12(+7)
speed: 36m (12m)
jds: [8, 9, 10, 10, 12, (8)]
roll_jds: 1d20
roll-moral: 2d6
moral: 12
xp: "1200"
nbr: 1
nbr_dj: 1
loot: Aucun
forceColumns: true
columns: 1
traits:
  - name: Pistage
    desc: "Sans défaillance"
  - name: Surprise
    desc: "Sur un résultat de 1-à-5, à moins que la cible ne détecte l’invisibilité."
  - name: S'il es tué
    desc: "Retourne dans son plan d’origine."
actions:
  - name: 1x coup
    desc: D20 jet d'attaque, 2 (4d4) de dégâts
source: OSE
```
---