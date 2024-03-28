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
<% tp.file.title %>
<% await tp.file.move("/OSE/7. Monsters/Monster Stats/" + tp.file.title) %>

<%*
const hasTitle = !tp.file.title.startsWith("NewMonstre");
let title;
if (!hasTitle) {
    title = await tp.system.prompt("Saisir le nom de votre monstre");
    await tp.file.rename(title);
} else {
    title = tp.file.title;
}
_%>
---
```statblock
layout: OSE
name: 
subtype:
image:
ac: ()
hit_dice: 1D8
thaco:
speed: m (m)
jds: [,,,,,]
moral:
alignement:
xp: ""
nbr: 1d6
nbr_dj: 1d6
loot: [[2. Treasure Types]]
hp: 3
roll_jds: 1d20
roll-moral: 2d6
forceColumns: true
columns: 1
traits:
  - name:
    desc:
  - name:
    desc:
  - name:
    desc:
  - name:
    desc:
actions:
  - name:
    desc: D20 jet d'attaque, 2 (1d3) de dégâts
  - name:
    desc: D20 jet d'attaque, 2 (1d3) de dégâts
source: OSE
```
---
