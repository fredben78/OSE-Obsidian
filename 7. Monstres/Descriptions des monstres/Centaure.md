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
name: Centaure
subtype: "Créature fantastique qui possède les jambes et le corps d’un cheval, le torse et la tête d’un humain. Vit en petits groupes familiaux ou tribaux, dans des prairies sauvages et des forêts isolées."
image:
alignement: Neutre
ac: 5(14)
hp: 18
hit_dice: 4D8
thaco: 16 (+3)
speed: 54m (18m)
jds: [10, 11, 12, 13, 14, (4)]
roll_jds: 1d20
roll-moral: 2d6
moral: 8
xp: "75"
nbr: 0 
nbr_dj: 1d6
loot: [[2. Types de trésors#Type A (18 000 po en moyenne)|A]]
forceColumns: true
columns: 1
traits:
  - name: Armes
    desc: "Arcs, gourdins, lances."
  - name: Repaire
    desc: "Caché dans des bois denses, le long de chemins tortueux et gardés."
  - name: Femelles et petits
    desc: "Restent habituellement dans le repaire et fuient s’ils sont attaqués. Les petits ont 2DV 4 (2d8) et font 2 attaques de sabot 1 (1d2) et 1 attaque d’arme 2 (1d4) ou selon l’arme."
actions:
  - name: 2x sabot 
    desc: D20 jet d'attaque, 2 (1d6) de dégâts
  - name: 1x arme
    desc: D20 jet d'attaque, 2 (1d6) de dégâts ou selon arme
source: OSE
```
---