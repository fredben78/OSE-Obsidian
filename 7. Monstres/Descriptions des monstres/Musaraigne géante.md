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
name: Musaraigne géante
subtype: "Rongeur insectivore brun au long museau. Creuse des galeries et niche sous terre."
image:
ac: 4(15)
hit_dice: 1D8
thaco: 19(0)
speed: 54m (18m)
jds: [12,13,14,15,16,(1)]
moral: 10
alignement: Neutre
xp: 10
nbr: 1d4
nbr_dj: 1d8
loot: Aucun
hp: 3
roll_jds: 1d20
roll-moral: 2d6
traits:
  - name: Initiative
    desc: "Remporte toujours l’initiative au round de sa première attaque. Au round de sa deuxième attaque, bonus de +1 à l’initiative."
  - name: Férocité
    desc: "Attaque ses adversaires à la tête. Les cibles de 3 DV ou moins doivent effectuer un jet de sauvegarde contre la mort ou s’enfuir."
  - name: Escalade
    desc: "Grimpe avec agilité; peut sauter jusqu’à 1,50 m."
  - name: Territoriale
    desc: "Défend férocement son territoire de chasse contre tout intrus."
  - name: Écholocation
    desc: "Perçoit son environnement jusqu’à 18 m, quelles que soient les conditions d’éclairage. Si elle est rendue sourde (par un sort de silence sur 5 mètres, par ex.), sa CA est réduite à 8 [11], et malus de –4 à l’attaque."
actions:
  - name: 2x Morsure
    desc: D20 jet d'attaque, 2 (1d6) de dégâts
source: OSE
```
---
