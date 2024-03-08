---
JDR: OSE
Type:
  - core

tags:
  - monster
statblock: inline
---
# Abeille Tueuse
----
```statblock
layout: OSE
name: Abeille tueuse
subtype: Abeilles géantes, longues de 30 cm, au tempérament agressif. Installent leurs ruches dans les souterrains.
image:
alignement: Neutre
ac: 7 (12)
hp: 2
thaco: 19
hit_dice: 1D3
speed: 45m (15m) vol
jds: [12, 13, 14, 15, 16, 1]
roll_jds: 1d20
moral: 9
roll-moral: 2d6
xp: "6 (garde : 13, reine : 25)"
nbr: 1d6
nbr_dj: 5d6
loot: Miel
forceColumns: true
columns: 2
traits:
  - name: Agressive
    desc: Malus de –1 à ses attaques en plein jour.
  - name: Agressive
    desc: Attaque en général à vue. Attaque toujours un intrus se trouvant à moins de 9 m de la ruche.
  - name: Meurt après l’attaque
    desc: Sur une attaque de dard réussie, l’abeille tueuse meurt.
  - name: Poison
    desc: Provoque la mort (jet de sauvegarde contre le poison).
  - name: Dard fiché
    desc: Reçoit 1 dégât par round à cause du dard qui pénètre plus profondément dans la blessure. Le retirer prend un round.
  - name: Reine
    desc: Une reine avec 2 DV vit dans la ruche. Elle ne meurt pas après avoir piqué.
  - name: Gardes
    desc: Au moins 10 abeilles (dont 4 ou plus ont 1 DV) sont toujours présentes dans ou à proximité de la ruche pour veiller sur la reine.
  - name: Miel
    desc: La ruche contient environ un litre de miel magique. Quiconque mange cette quantité regagne (1d4) points de vie.
actions:
  - name: Dard
    desc: D20 jet d'attaque, 2 (1d3) de dégâts
source: OSE
```

____
