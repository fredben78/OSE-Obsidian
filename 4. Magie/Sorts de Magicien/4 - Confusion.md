---
Type:
  - core
tags:
  - sort
JDR: OSE
niveau: 4
Duree:
  - 12 tours
Portee:
  - 36 mètres
Classe:
  - Magicien

---
# `=this.file.name`  

[[5. Sorts de magicien|Sorts de magicien]] `=this.niveau`e Niveau

**Durée** : `=this.Duree` 

**Portée** : `=this.Portee`

Ce sort rend confuses `dice: (3d6)` cibles dans un rayon de 18 m, incapables par elles-mêmes de décider de leur action.

- **Cibles de 2+1 DV ou plus** : Elles peuvent effectuer un jet de sauvegarde contre les sorts chaque round pour résister à l’effet du sort, agissant librement ce round-ci en cas de réussite.
- **Cibles de 2 DV ou moins** : Elles ne peuvent pas effectuer de jet de sauvegarde.
- **Comportement** : Effectuez à chaque round un jet sur le tableau suivant pour chaque cible afin de voir ce qu’elle fait ce round-ci :

### Confusion : comportement de la cible

| `dice: (2d6)`  | Comportement              |
| :--: | :--------------------- |
| 2-5  | Attaque le groupe du lanceur  |
| 6-8  | Aucune action              |
| 9-12 | Attaque le groupe de la cible |