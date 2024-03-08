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
name: Molosse satanique 7DV
subtype: "Molosse aussi intelligent que vicieux, de la taille d’un petit poney. Crache du feu et adore la chaleur. On le rencontre dans les donjons ou près des volcans."
image:
ac: 4(15)
hit_dice: 7D8
thaco: 13(+6) 
speed: 36m (12m)
jds: [8,9,10,10,12,(7)]
moral: 9
alignement: Chaotique
xp: "850"
nbr: 2d4
nbr_dj: 2d4
loot: [[2. Types de trésors#Type C (1 000 po en moyenne)|C]]
hp: 3
roll_jds: 1d20
roll-moral: 2d6
forceColumns: true
columns: 1
traits:
  - name: Souffle
    desc: "À chaque round, un molosse satanique a 2-sur-6 chances de souffler du feu. Une seule cible. Jet de sauvegarde contre les souffles pour ne subir que la moitié des dégâts."
  - name: Immunité au feu
    desc: "Immunisé au feu non magique."
  - name: Détection de l’invisible
    desc: "75 % de chances par round, à 18 m alentour."
  - name: Adoption
    desc: "On les rencontre parfois en compagnie d’autres créatures liées au feu."
actions:
  - name: 1x Morsure
    desc: D20 jet d'attaque, 2 (1d6) de dégâts
  - name: ou 1x Souffle
    desc: D20 jet d'attaque, 2 (7d6) de dégâts
source: OSE
```
---
