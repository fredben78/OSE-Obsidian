---
JDR: OSE
Type:
  - core

tags:
  - monster
statblock: inline
aliases:
  - Air elemental (lesser)
---
# `=this.file.name`


---
```statblock
layout: OSE
name: "Élémental de l'air Mineur"
subtype: "Prend la forme d'énormes tourbillons d'air."
image:
alignement: Neutre
ac: 2(17)
hp: 36
hit_dice: 8D8
thaco: 12(+7)
speed: 108m (36m) vol
jds: [8, 9, 10, 10, 12, (8)]
roll_jds: 1d20
roll-moral: 2d6
moral: "10"
xp: "1200"
nbr: 1 
nbr_dj: 1
loot: Aucun
traits:
  - name: Taille
    desc: "Hauteur 4,80 m, largeur 1,20 m"
  - name: "Tourbillon"
    desc: "Les créatures ayant moins de 2 DV sont balayées (jet de sauvegarde contre la mort)."
  - name: Immunité aux dégâts normaux
    desc: "Ne peut être blessé que par des attaques magiques."
  - name: Néfaste aux créatures volantes 
    desc: "Inflige 4 (1d8) dégâts supplémentaires à ce type de créature"
actions:
  - name: 1 x coup
    desc: D20 jet d'attaque, 12 (1d8) de dégâts
source: OSE
```
---
