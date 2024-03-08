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
name: Géant des tempêtes
subtype: "Humanoïde, haut de 6,60 m, a la peau aux reflets bronze et les cheveux d’une couleur criarde (rouges ou blonds)."
image:
ac: 2(17)
hit_dice: 15D8
thaco: 9(+10)
speed: 45m (15m)
jds: [4,5,6,5,8,(15)]
moral: 10
alignement: Loyal
xp: "1350"
nbr: 1
nbr_dj: 1d3
loot: [[2. Types de trésors|E]]
hp: 3
roll_jds: 1d20
roll-moral: 2d6
forceColumns: true
columns: 1
traits:
  - name: Convocation de tempête
    desc: "Prend 1 tour."
  - name: Éclairs
    desc: "Dans une tempête, le géant peut, une fois tous les 5 rounds, \n Lancer des éclairs: de 18 m de long, et 1,50 m de large \n Inflige des dégâts égaux à ses points de vie actuels (jet de sauvegarde contre les sorts pour ne subir que la moitié des dégâts) \n Rebondit sur les surfaces dures se trouvant sur son chemin."
  - name: Immunité à la foudre
    desc: "Immunisé contre la foudre. Se complaît dans les tempêtes."
  - name: Château
    desc: "Situé sur les sommets de montagne, au-dessus des bancs de nuages ​​ou dans les profondeurs sous-marines."
  - name: Gardiens
    desc: "Accompagné par 4 (2d4) [[Griffon|griffons]]. Sous l’eau : 9 (3d6) [[Crabe géant|crabes géants]]."
actions:
  - name: 1x Arme
    desc: D20 jet d'attaque, 2 (8d6) de dégâts
  - name: 1x éclair
    desc: D20 jet d'attaque, inflige des dégâts égaux à ses points de vie actuels (jet de sauvegarde contre les sorts pour ne subir que la moitié des dégâts)
source: OSE
```
---
