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
name: Cachalot
subtype: "Baleine gigantesque ; mesure jusqu’à 18 m de long et habite dans les grands océans. Chasse les monstres des grands fonds (par ex. les calmars géants)."
image:
ac: 6(13)
hit_dice: 36D8
thaco: 5(+14)
speed: 54m (18m)
jds: [4,5,6,5,8,(15)]
moral: 7
alignement: Neutre
xp: 6250
nbr: 0
nbr_dj: 1d3
loot: [[2. Types de trésors#Type V (330 po en moyenne)|V]]
hp: 3
roll_jds: 1d20
roll-moral: 2d6
traits:
  - name: Gobe entièrement
    desc: "Sur un jet d’attaque de 4 ou plus que le nombre requis pour toucher, toute cible de la taille d’un humain ou inférieure est avalée. Une fois gobée, la cible subit 10 (3d6) points de dégâts par round (jusqu’à ce que le cachalot soit tué ou que la cible meure) ; la cible peut attaquer avec des armes tranchantes en subissant un malus de –4 ; le cadavre de la victime est digéré en 6 tours après la mort."
  - name: Éperonnement d’un navire
    desc: "Environ 10% de chances d’attaquer un navire."
actions:
  - name: 1x Morsure
    desc: D20 jet d'attaque, 2 (3d20) de dégâts
  - name: ou 1x éperonnement
    desc: D20 jet d'attaque, 2 (6d6) de dégâts de structure
source: OSE
```
---
