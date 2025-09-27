---
Homeworld:
Species:
Gender:
Pronouns: Male
Rank:
Role:
Affiliation:
Age: "1"
Career:
Speciality:
Location:
NoteIcon: npc
Vitality: Deceased
Player:
---

<% await tp.file.move("/3-Mechanics/NPCs/" + tp.file.title) %>

<%*
const hasTitle = !tp.file.title.startsWith("NewNPC");
let title;
if (!hasTitle) {
    title = await tp.system.prompt("Enter NPC Name");
    await tp.file.rename(title);
} else {
    title = tp.file.title;
}
_%>

> [!infobox]
> # `=this.file.name`
> ![[ImagePlaceholder.png|cover hsmall]]
> [[ImagePlaceholder.png|Full size image]]
> ###### Basic Information
> Type |  Stat |
> ---|---|
> Homeworld | `=this.Homeworld` |
> Species | `=this.Species` |
> Affiliation(s) | `=this.Affiliation` 
> Gender | `=this.Gender` |
> Pronouns | `=this.pronouns` |
> Rank | `=this.Rank` |
> Role | `=this.Role` |
> Condition | Healthy |
> ###### Rules Info
> Type |  Stat |
> ---|---|
> Career | `=this.Career` |
> Speciality | `=this.speciality` |
> Character Role | `=this.character-role` |

# `=this.file.name`
## Profile

**<Add description here, extend it with AI Text Generator using Ctrl J>**

> [!info] Statblock
> ```statblock
> name: Individual
> monster: Commoner
> columns: 1
> ```

```encounter-table
name: Individual
creatures:
 - 1: Commoner
```

