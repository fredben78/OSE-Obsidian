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
name: Vampire 9DV
subtype: "Monstre mort-vivant très redouté qui vit en buvant le sang des mortels. Habite dans les ruines, les tombes et les lieux désertés."
image:
ac: 2(17)
hit_dice: 9D8
thaco: 12(+7)
speed: 36m (12m)
jds: [8,9,10,10,12,(9)]
moral: 11
alignement: Chaotique
xp: 2300
nbr: 1d4
nbr_dj: 1d6
loot: [[2. Treasure Types#Type F (7 700 po en moyenne)|F]]
hp: 3
roll_jds: 1d20
roll-moral: 2d6
traits:
  - name: Mort-vivant
    desc: "Ne fait aucun bruit jusqu’à ce qu’il attaque. Immunisé contre les effets affectant les créatures vivantes (par exemple, le poison). Immunisé contre les sorts affectant ou lisant l’esprit (par exemple, charme, paralysie, sommeil)."
  - name: Immunité aux dégâts normaux
    desc: "Ne peut être blessé que par des attaques magiques."
  - name: Absorption d’énergie
    desc: "Une cible touchée avec succès perd deux niveaux d’expérience (ou Dés de vie) de manière permanente. Ceci entraîne la perte de points de vie correspondant aux DV de perdus, ainsi que les autres capacités dues aux niveaux perdus (sorts, jets de sauvegarde, etc.). L’XP du personnage est réduite au minimum du nouveau niveau. Une personne qui perd tous ses niveaux devient un vampire en 3 jours."
  - name: Regard (charme)
    desc: "Quiconque croise le regard du vampire doit effectuer un jet de sauvegarde contre les sorts avec un malus de –2. En cas d’échec, la victime est charmée et doit:\n Se déplacer en direction du vampire (en résistant à ceux qui essaient de l’en empêcher)\n Le défendre\n Et obéir à ses ordres (à condition de les comprendre).\n Incapable de lancer de sorts, ou d’utiliser d’objets magiques, ou s’en prendre au vampire. La mort du vampire rompt le charme."
  - name: Régénération
    desc: "Un vampire ayant subi des dégâts regagne 3 pv au début de chaque round, tant qu’il est vivant. À 0 pv: Il passe en forme gazeuse et fuit en direction de son cercueil."
  - name: Changeur de forme
    desc: "À volonté; prend 1 round \n 1. Humanoïde: Forme standard.\n 2. [[Loup géant|Loup géant]]: Att 1 × morsure (2d4), DP 45 m (15 m), CA, DV, Ml: Comme ceux du vampire \n 3. [[Chauve-souris géante|Chauve-souris géante]]: Att 1× morsure (1d4), DP 9 m (3 m) / 54 m (18 m) vol, CA, DV, Ml: Comme ceux du vampire \n 4.Nuage gazeux: DP 54 m (18 m) vol. Immunisé aux dégâts normaux. Ne peut pas attaquer."
  - name: Convocation de bêtes
    desc: "Sous sa forme humaine uniquement, le vampire peut faire venir à lui des créatures des environs: \n 5 (1d10) ×10 [[Rat|rats]]\n 10 (5d4) [[Rat géant|rats géants]]\n 5 (1d10) ×10 [[Chauve-souris normale|chauves-souris]]\n 10 (3d6) [[Chauve-souris géante|chauves-souris géantes]] \n 10 (3d6) [[Loup normal|loups communs]]\n ou 4 (2d4) [[Loup géant|loups géants]]."
  - name: Cercueils
    desc: "Doit se reposer durant la journée dans un cercueil ou perdre 6 (2d6) pv (uniquement régénérés en se reposant une journée complète). Ne peut pas se reposer dans un cercueil béni. Garde toujours plusieurs cercueils dans des endroits cachés."
  - name: Vulnérabilités
    desc: "\n 1. Ail: L’odeur le repousse : jet de sauvegarde contre le poison ou incapacité à attaquer ce round.\n 2.Symboles sacrés: S’ils sont présentés, ils gardent le vampire à distance (3 m). Peut attaquer le porteur à partir d’une autre direction.\n 3. Eau vive: Ne peut la traverser (sous aucune forme), sauf au moyen d’un pont ou s’il est transporté à l’intérieur d’un cercueil.\n 4. Miroirs: Les évite ; on n’y voit pas son reflet.\n 5. Lumière éternelle: Partiellement aveuglé par la lumière de ce sort (malus de –4 aux attaques)."
  - name: Destruction
    desc: "\n 1. Lumière du soleil: Doit effectuer un jet de sauvegarde contre la mort à chaque round où il y est exposé ou est désintégré.\n 2. Pieu dans le cœur: Tue le vampire définitivement.\n 3. Immersion dans l’eau: Pendant 1 tour, le tue définitivement.\n 4.Détruire les cercueils: Le vampire est tué de façon permanente si tous ses points de vie sont perdus et qu’il est incapable de se reposer (voir cercueils)."
actions:
  - name: 1x Toucher
    desc: D20 jet d'attaque, 2 (1d10) de dégâts + absorption d'énergie
  - name: ou 1x Regard
    desc: D20 jet d'attaque, charme
source: OSE
```
---
