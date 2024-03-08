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
name: Harpie
subtype: "Cette créature ressemble à un aigle géant doté du torse et de la tête d’une hideuse sorcière. Son chant attire ses victimes vers leur perte."
image:
ac: 7(12)
hit_dice: 3D8
thaco: 17(+2)
speed: 18m (6m) / 45m (15m) vol
jds: [12,13,14,15,16,(3)]
moral: 7
alignement: Chaotique
xp: "50"
nbr: 1d6
nbr_dj: 2d4
loot: [[2. Types de trésors#Type C (1 000 po en moyenne)|C]]
hp: 3
roll_jds: 1d20
roll-moral: 2d6
forceColumns: true
columns: 1
traits:
  - name: Charme
    desc: "Quiconque entend le chant d’un groupe de harpies doit effectuer un jet de sauvegarde contre les sorts. En cas d’échec, la victime est charmée et doit : \n se déplacer en direction des harpies (en résistant à ceux qui essaient de l’en empêcher) \n les défendre \n et obéir à leurs ordres (à condition de les comprendre). \n En outre, elle ne peut ni lancer de sorts, ni utiliser d’objets magiques, ni s’en prendre aux harpies. Un personnage qui résiste au charme est immunisé pour le reste de la rencontre. La mort des harpies rompt le charme."
  - name: Résistance à la magie
    desc: "Bonus de +2 à tous les jets de sauvegarde."
actions:
  - name: 2x Serre
    desc: D20 jet d'attaque, 2 (1d4) de dégâts
  - name: 1x Arme
    desc: D20 jet d'attaque, 2 (1d6) de dégâts ou selon arme
  - name: 1x Chant
    desc: Charme
source: OSE
```
---
