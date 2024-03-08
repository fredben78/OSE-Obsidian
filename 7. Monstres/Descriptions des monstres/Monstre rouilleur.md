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
name: Monstre rouilleur
subtype: "Créature magique qui ressemble à un tatou avec une longue queue et deux longues antennes. Se nourrit de métal rouillé."
image:
ac: 2(17)
hit_dice: 5D8
thaco: 15(+4)
speed: 36m (12m)
jds: [12,13,14,15,16,(3)]
moral: 7
alignement: Neutre
xp: 175
nbr: 1d4
nbr_dj: 1d4
loot: Aucun
hp: 3
roll_jds: 1d20
roll-moral: 2d6
traits:
  - name: Rouille
    desc: "Le métal touché par un monstre rouilleur (par exemple, les armes qui le touchent ou l’armure frappée par une antenne) s’effondre instantanément, touché par la rouille. Les objets magiques ont 10% de chances par «plus» de ne pas être affectés à chaque coup réussi. Chaque fois qu’un objet magique est affecté, il perd un «plus»."
  - name: Immunité aux dégâts normaux
    desc: "Ne peut être blessé que par des attaques magiques."
  - name: Sentir le métal
    desc: "Attiré par l’odeur du métal."
actions:
  - name: 1x Antenne
    desc: D20 jet d'attaque, rouille
source: OSE
```
---
