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
name: Loup-garou
subtype: "Créature semi-intelligente qui chasse en meute."
image:
ac: 5(14) (9 (10) sous forme humaine)
hit_dice: D48
thaco: 16(+3)
speed: 54m (18m)
jds: [10,11,12,13,14,(4)]
moral: 8
alignement: Chaotique
xp: 12 (chef:300)
nbr: 1d6
nbr_dj: 2d6
loot: [[2. Types de trésors#Type C (1 000 po en moyenne)|C]]
hp: 3
roll_jds: 1d20
roll-moral: 2d6
traits:
  - name: Meneur
    desc: "Les groupes de cinq individus et plus sont dirigés par un loup-garou avec 5 DV (30 pv). Le chef reçoit un bonus de +2 à ses jets de dégâts."
  - name: Forme humaine
    desc: "Possède des caractéristiques physiques qui rappellent sa nature animale."
  - name: Immunité aux dégâts normaux
    desc: "Sous sa forme animale, ne peut être blessé que par les armes en argent ou la magie."
  - name: Langues
    desc: "Sous sa forme humaine, il parle normalement, mais sous forme animale, il ne peut communiquer qu’avec les animaux du même type."
  - name: Armure
    desc: "Les armures gênent la transformation d’un lycanthrope ; il n’en porte jamais."
  - name: Appel d’animaux
    desc: "Peut convoquer 1 ou 2 animaux de son espèce présents dans les alentours ([[Loup normal]]) . Ils arrivent en 2 (1d4) rounds."
  - name: Herbe au loup
    desc: "Un lycanthrope touché par de l’herbe au loup doit effectuer un jet de sauvegarde contre le poison ou s’enfuir, terrorisé."
  - name: Retour
    desc: "À sa mort, le lycanthrope reprend sa forme humaine."
  - name: Odeur
    desc: "Les chevaux et certains autres animaux sentent les lycanthropes et peuvent prendre peur."
  - name: Infection
    desc: "Un personnage qui perd plus de la moitié de ses points de vie à cause des attaques naturelles d’un lycanthrope (morsure, griffes…) contracte la lycanthropie. Les humains deviennent des créatures-garous du même type et passent sous le contrôle de l’arbitre ; les non-humains meurent. La maladie se déclare après 6 (2d12) jours, des signes d’infection étant déjà visibles à la moitié de ce temps."
actions:
  - name: 1x Morsure
    desc: D20 jet d'attaque, 2 (2d4) de dégâts
source: OSE
```
---
