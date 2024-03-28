---
JDR: OSE
Type:
  - core

tags:
  - monster
statblock: inline
aliases:
  - Cave locust
---
# `=this.file.name`

---
```statblock
layout: OSE
name: Sauterelle géante
subtype: "Sauterelle géante herbivore, longue de 60 cm à 1 m. Habite dans les cavernes."
image:
alignement: Neutre
ac: 4(15)
hp: 9
hit_dice: 2D8
thaco: 18 (+1)
speed: 18m (6m) / 54m (18m) vol
jds: [12,13,14,15,16,(2)]
roll_jds: 1d20
roll-moral: 2d6
moral: 5
xp: "20"
nbr: 2d10
nbr_dj: 1d10
loot: Aucun
traits:
  - name: Se confond avec la pierre
    desc: "En raison de sa teinte pierreuse, elle peut passer inaperçue ou être confondue avec une statue."
  - name: Cri
    desc: "Si elle est attaquée ou effrayée, elle crie pour avertir les autres, ce qui peut attirer des monstres errants (20 % de chances par tour)."
  - name: Saut
    desc: "Très craintive. Lorsqu’elle subit une attaque, elle fuit généralement en faisant un bond de 18 m, puis s’envole. Il y a 50 % de chances qu’elle saute sur un adversaire pris au hasard, auquel cas il faut traiter le saut comme une attaque."
  - name: Crachat
    desc: "Utilisé défensivement. Portée de 3 m. On considère que la cible a une CA 9 [10]. Le personnage affecté est recouvert d’une projection de matière puante : il est incapable d’agir pendant 1 tour (jet de sauvegarde contre le poison). Jusqu’à ce que cette matière soit nettoyée, les personnes approchant à moins de 1,50 m doivent elles aussi effectuer un jet de sauvegarde contre le poison ou se sentir nauséeuses."
  - name: Immunité aux poisons
    desc: "Immunisée contre la Moisissure jaune et la plupart des poisons, en raison de son habitude à manger des champignons."
actions:
  - name: 1x morsure
    desc: D20 jet d'attaque, 2 (1d2) de dégâts
  - name: 1x saut
    desc: D20 jet d'attaque, 2 (1d4) de dégâts
  - name: 1x crachat
    desc: Puanteur
source: OSE
```
---