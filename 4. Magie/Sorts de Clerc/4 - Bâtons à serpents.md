---
Type:
  - core
tags:
  - sort
JDR: OSE
niveau: 4
Duree:
  - 6 tours
Portee:
  - 36 mètres
Classe:
  - Clerc
aliases:
  - Sticks to snakes
---
# `=this.file.name`  

[[4. Sorts de clerc|Sorts de clerc]] `=this.niveau`e Niveau

**Durée** : `=this.Duree`

**Portée** : `=this.Portee`

`dice: (2d8)` bouts de bois sont miraculeusement transformés en serpents qui répondent aux ordres du lanceur.

- **Retour** : S’ils sont tués ou à la fin du sort, les serpents retournent à leur forme originelle de bouts de bois.

### Serpents invoqués

```statblock
name: Serpents invoqués 
subtype:
image:
alignement:
ac: 6(13)
hp: 4
hit_dice: 1D8
thaco: 19
speed: 27m (9m)
jds: [12,13,14,15,16,(1)]
roll_jds: 1d20
roll-moral: 2d6
moral: 17
xp: "10"
nbr: Spécial 
loot: Aucun
traits:
  - name: Poison
    desc: "Les serpents ont 50 % de chance d’être venimeux."
  - name: S'ils sont tués
    desc: Retournent à l'état de bâtons.
actions:
  - name: 1x morsure
    desc: D20 jet d'attaque, 2 (1d4) de dégâts
source: OSE
```
