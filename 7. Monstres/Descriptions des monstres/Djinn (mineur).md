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
name: Djinn
subtype: "_Être hautement magique, libre et intelligent, provenant du plan élémentaire de l’air. Grand humanoïde enveloppé de nuages._"
image:
alignement: Neutre
ac: 5(14)
hp: 32
hit_dice: 7D8+1
thaco: 12 (+7)
speed: 27m (9m)
jds: [4, 5, 6, 5, 8, (14)]
roll_jds: 1d20
roll-moral: 2d6
nbr_dj: 1
moral: 12
xp: "850"
nbr: 1
forceColumns: true
columns: 2
loot: Aucun
traits:
  - name: Immunité aux dégâts normaux 
    desc: "Ne peut être blessé que par des attaques magiques."
  - name: Pouvoirs magiques
    desc: "Chaque pouvoir peut être utilisé trois fois par jour:
        \n 1. Forme de tourbillon: Il faut 5 rounds au Djinn pour se transformer (ou reprendre une forme humanoïde). Le tourbillon fait 21 m de haut, 6 m de large à son sommet pour 3 m de large à sa base. Il se déplace à une vitesse de 36 m (12 m) et inflige 3 (2d6) points de dégâts à toute créature se trouvant sur son chemin. Les créatures de moins de 2 DV sont balayées (jet de sauvegarde contre la mort).
        \n 2. Forme gazeuse
        \n 3. Invisibilité
        \n 4. Illusion: Visuelle et auditive. L’illusion ne demande aucune concentration au djinn. Elle persiste jusqu’à ce qu’elle soit touchée ou dissipée.
        \n 5. Création de nourriture et de boisson: Pour 12 humains et leurs montures pendant un jour.
        \n 6. Invoquer des objets métalliques: Jusqu’à un poids de 1 000 pièces. Temporaires: Le type de métal choisi détermine la durée (or: 1 jour; fer: 1 round).
        \n 7. Invoquer des objets usuels/en bois: Jusqu’à un poids de 1 000 pièces. Permanents."
  - name: Capacité de charge
    desc: "Un djinn peut porter 6 000 pièces sans fatigue. Jusqu’à 12 000 pièces pendant 3 tours en marchant / 1 tour en volant. Il doit ensuite se reposer 1 tour."
  - name: "S’il est tué"
    desc: "Il retourne dans le plan de l’air."
actions:
  - name: 1x poings
    desc: D20 jet d'attaque, 2 (2d8) de dégâts magique
source: OSE
```
---