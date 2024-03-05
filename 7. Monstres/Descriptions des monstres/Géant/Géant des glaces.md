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
name: Géant des glaces
subtype: "Humanoïde, haut de 5,40 m, à la peau et aux cheveux pâles (blonds ou bleus). S’habille dans des fourrures ou une armure en fer. Les mâles ont une longue barbe."
image:
ac: 4(15)
hit_dice: 10D8+1
thaco: 11(+8)
speed: 36m (12m)
jds: [6,7,8,8,10,(10)]
moral: 9
alignement: Chaotique
xp: "900"
nbr: 1d2
nbr_dj: 1d4
loot: [[2. Treasure Types#Type E (2 300 po en moyenne)|E]] + 5000po 
hp: 3
roll_jds: 1d20
roll-moral: 2d6
forceColumns: true
columns: 1
traits:
  - name: Lancer de rochers
    desc: "Jusqu’à 60 m."
  - name: Immunité au froid
    desc: "Immunisé aux dégâts de froid."
  - name: Château
    desc: "Sur les monts enneigés."
  - name: Gardiens
    desc: "20 % de chances d’être accompagné par 9 (3d6) [[Ours polaire|ours polaires]] ; sinon, par 18 (6d6) [[Loup normal|loups]]."
actions:
  - name: 1x Arme
    desc: D20 jet d'attaque, 2 (4d6) de dégâts
  - name: ou 1x Rocher
    desc: D20 jet d'attaque, 2 (3d6) de dégâts
source: OSE
```
---
