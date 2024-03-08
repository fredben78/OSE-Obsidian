---
Type:
  - core
tags:
  - sort
JDR: OSE
niveau: 5
Duree:
  - Instantanée
Portee:
  - 3 mètres
Classe:
  - Magicien

---
# `=this.file.name`  

[[5. Sorts de magicien|Sorts de magicien]] `=this.niveau`e Niveau

**Durée** : `=this.Duree` 

**Portée** : `=this.Portee`

Le lanceur ou une créature choisie disparaît et réapparaît à un endroit choisi par le lanceur.

- **Équipement** : La cible est téléportée avec tout son équipement, jusqu'à sa charge maximale.
- **Cible réticente** : Si la cible ne souhaite pas partir, elle peut effectuer un jet de sauvegarde contre les sorts afin d’empêcher la téléportation.
- **Destination** : Elle peut se trouver à n'importe quelle distance, mais doit être connue du lanceur. La destination doit être un espace libre au niveau du sol. Il n'est pas possible de téléporter intentionnellement la cible dans les airs ou dans une matière solide.
- **Risque** : Il existe un risque, lors de la téléportation, d'arriver accidentellement au-dessus ou au-dessous du niveau du sol. Les chances de réussite de la téléportation dépendent de la connaissance qu’a le lanceur de la destination (voir à droite). Lancez un dé de pourcentage et consultez le tableau ci-dessous.

## Résultat de la téléportation
Test de téléportation : `dice: 1d100`
| Connaissance de la dest. | Niveau du sol | Trop haut | Trop bas |
| :--- | ---- | ---- | ---- |
| Faible | 01–50 | 51–75 | 76–00 |
| Moyenne | 01–80 | 81–90 | 91–00 |
| Exacte | 01–95 | 96–99 | 0 |

**Niveau du sol** : La cible apparaît à la destination souhaitée.

**Trop haut** : La cible apparaît `dice: (1d10*3)` m au-dessus de la destination prévue. Si cet endroit est déjà occupé par de la matière solide, la cible meurt immédiatement. Sinon, elle tombe de cette hauteur.

**Trop bas** : La cible apparaît dans le sol et meurt instantanément.

**Connaissance de la destination** : La connaissance qu’a le lanceur de la destination est évaluée comme suit :

- **Faible** : Un endroit où le lanceur s’est rendu une ou deux fois, qu’il a vu par scrutation magique ou dont il a entendu parler.
- **Moyenne** : Un endroit où le lanceur s’est souvent rendu ou qu’il a étudié par scrutation pendant plusieurs semaines.
- **Exacte** : Un endroit dont le lanceur a fait une étude détaillée et en personne.