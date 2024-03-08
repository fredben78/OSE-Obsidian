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
name: Dragon de mer
subtype: "Ce dragon aquatique intelligent aux écailles vertes, avec des ailes ressemblant à des nageoires et une crête jaunâtre, habite dans les profondeurs de l’océan, dans des cavernes ou des épaves. Il attaque parfois des navires pour voler leurs trésors et dévorer l’équipage."
image:
alignement: Neutre
ac: 1(18)
hp: 36
hit_dice: 8D8
thaco: 12 (+7)
speed: 54m (18m) nage, 54m (18m) vol plané
jds: [8, 9, 10, 10, 12, (8)]
roll_jds: 1d20
roll-moral: 2d6
moral: 9
nbr_dj: 1d4
xp: "1750"
nbr: 0 
loot: [[2. Types de trésors#Type H (60 000 po en moyenne)|H]]
traits:
  - name: Souffle
    desc: "Crachat de poison de 6 m de diamètre et d’une portée de 30 m. Jet de sauvegarde contre les souffles ou meurt (le poison est inoffensif après 1 round)."
  - name: "Langue et sorts"
    desc: "20% 50 (1d100), 3× 1er niveau, 3× 2e niveau."
  - name: Sommeil
    desc: "30% 50 (1d100)"
  - name: "Vol plané"
    desc: "Le dragon de mer peut sauter hors de l’eau et planer jusqu’à 6 tours."
actions:
  - name: 1x morsure
    desc: D20 jet d'attaque, 2 (3d8) de dégâts
  - name: ou Souffle
    desc: "égal aux points de vie actuel du dragon (jet de sauvegarde contre les souffles divise par deux)"
source: OSE
```
---
