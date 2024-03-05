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
name: Moisissure jaune
subtype: "Ce champignon mortel recouvre les murs, les plafonds et autres surfaces."
image:
ac: Aucun jet requis
hit_dice: 2D8
thaco: 18(+1)
speed: 0m (0m)
jds: [12,13,14,15,16,(2)]
moral: 25
alignement: Neutre
xp: 25
nbr: 1d8
nbr_dj: 1d4
loot: Aucun
hp: 3
roll_jds: 1d20
roll-moral: 2d6
traits:
  - name: Superficie
    desc: "Chaque surface de 1 m² (par exemple, 1m×1m) recouvert de moisissure jaune est traité comme un «individu». Une zone de 3m×3m comprendra donc 9 moisissures individuelles."
  - name: Immunité
    desc: "Immunisée à toutes les attaques hormis le feu (une torche allumée lui inflige 2 (1d4) dégâts)."
  - name: Nuage de spores
    desc: "50% de chances de produire cette attaque si elle est touchée (ou subit des dégâts). Elle libère alors un nuage de spores affectant tout ce qui se trouve dans une zone de 3 m3."
  - name: Étouffement
    desc: "Jet de sauvegarde contre la mort ou mort dans les 6 rounds."
  - name: Corrosion
    desc: "Le bois ou le cuir en contact avec la moisissure sont rongés."
actions:
  - name: 1x Spore
    desc: D20 jet d'attaque, 2 (1d6) de dégâts + étouffement
source: OSE
```
---
