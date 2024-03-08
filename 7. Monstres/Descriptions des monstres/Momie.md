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
name: Momie
subtype: "Humanoïde mort-vivant enveloppé de bandages funéraires. On le rencontre dans les ruines hantées et les tombeaux."
image:
ac: 3(16)
hit_dice: 5D8+1
thaco: 14(+5)
speed: 18m (6m)
jds: [10,11,12,13,14,(5)]
moral: 12
alignement: Chaotique
xp: "400"
nbr: 1d4
nbr_dj: 1d12
loot: [[2. Types de trésors#Type D (3 900 po en moyenne)|D]]
hp: 3
roll_jds: 1d20
roll-moral: 2d6
forceColumns: true
columns: 1
traits:
  - name: Paralyser par la terreur
    desc: "Quiconque voit une momie doit effectuer un jet de sauvegarde contre la paralysie ou être paralysé par la terreur. La paralysie est rompue si la momie attaque ou disparaît de la vue."
  - name: Maladie
    desc: "Toute personne touchée contracte une horrible maladie putrescente. La guérison magique des blessures est inefficace ; la guérison naturelle prend dix fois plus de temps. La maladie ne peut être éliminée que par magie."
  - name: Immunité aux dégâts normaux
    desc: "Ne peut être blessée que par le feu ou la magie. Tous les dégâts sont réduits de moitié."
  - name: Mort-vivant
    desc: "Ne fait aucun bruit jusqu’à ce qu’elle attaque. Insensible aux effets affectant les créatures vivantes (par exemple, le poison). Immunisée contre les sorts affectant ou lisant l’esprit (ex. : charme, paralysie, sommeil)."
actions:
  - name: 1x Toucher
    desc: D20 jet d'attaque, 2 (1d12) de dégâts + maladie
source: OSE
```
---
