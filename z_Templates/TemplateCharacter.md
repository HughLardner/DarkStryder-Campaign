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
> ###### Biographical Information
> Homeworld | `=this.Homeworld` |
> ###### Biographical Information
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

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
</head>
<body>
  <div class="infobox">
    <div class="heading">
      <h2>Cute Dog</h2>
    </div>
    <img src="https://images.unsplash.com/photo-1586671267731-da2cf3ceeb80?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=689&q=80" class="infobox-img"
      alt="infobox picture">
    <div class="infobox-group">
      <div class="heading">
        <h3>Biographical Information</h3>
      </div>
      <div class="infobox-data">
	    <div class="infobox-datarow">
          <p class="data-heading">Full name</p>
          <ul class="data-content">
	          <li>Bellus Canis</li>
          </ul>
        </div>
        <div class="infobox-datarow">
          <p class="data-heading">Age</p>
          <ul class="data-content">
	          <li>6 months</li>
          </ul>
        </div>
        <div class="infobox-datarow">
          <p class="data-heading">Status</p>
          <ul class="data-content">
	          <li>Alive</li>
          </ul>
        </div>
        <div class="infobox-datarow">
          <p class="data-heading">Relatives</p>
          <ul class="data-content">
	          <li>Papa</li>
	          <li>Mama</li>
	          <li>Big Sis</li>
	          <li>Angry Cat</li>
          </ul>
        </div>
      </div>
    </div>
    <div class="infobox-group">
      <div class="heading">
        <h3>Physical Description</h3>
      </div>
      <div class="infobox-data">
        <div class="infobox-datarow">
          <p class="data-heading">Hair Color</p>
          <ul class="data-content">
	          <li>Golden Yellow</li>
          </ul>
        </div>
        <div class="infobox-datarow">
          <p class="data-heading">Eye Color</p>
          <ul class="data-content">
	          <li>Brown</li>
          </ul>
        </div>
      </div>
    </div>
    <div class="infobox-group">
      <div class="heading">
        <h3>Social Information</h3>
      </div>
      <div class="infobox-data">
	    <div class="infobox-datarow">
          <p class="data-heading">Nation</p>
          <ul class="data-content">
	          <li>Brazil</li>
          </ul>
        </div>
        <div class="infobox-datarow">
          <p class="data-heading">Occupation</p>
          <ul class="data-content">
	          <li>Being Cute</li>
          </ul>
        </div>
        <div class="infobox-datarow">
          <p class="data-heading">Family</p>
          <ul class="data-content">
	          <li>Hopefully mine</li>
          </ul>
        </div>
      </div>
    </div>
  </div>
</body>
</html>
{{Character
|type=GFFA
|image=[[File:Hansoloprofile.jpg]]
|name=Han Solo
|homeworld=[[Corellia/Legends|Corellia]]<ref name="Han Solo SWE">{{SWE|characters|hansolo|Han Solo}}</ref>
|birth=[[29 BBY/Legends|29 BBY]]<ref name="Star Wars Gamemaster Screen, Revised">''[[Star Wars Gamemaster Screen, Revised]]''</ref> {{C|[[Great ReSynchronization|6]]}},<ref name="Blog-holocron|13/comments">{{Blog|holocron|13/comments|Major Character Birth Years}}</ref> Corellia
|death=
|species=[[Human/Legends|Human]]<ref name="Han Solo SWE" />
|gender=[[Gender/Legends|Male]]<ref name="Han Solo SWE" />
|pronouns=He/him<ref name="Han Solo SWE" />
|height=1.8 [[Meter/Legends|meters]]<ref name="DB">{{DB|character|hansolo|Solo, Han}}</ref>
|mass=80 [[Kilogram/Legends|kilograms]]<ref name="H2H">''[[Star Wars: Head-to-Head Tag Teams]]''</ref>
|hair=[[Color/Legends|Brown]]<ref name="A New Hope">{{Film|IV}}</ref>
|feathers=
|eyes=Brown<ref name="A New Hope" />
|skin=Light<ref name="A New Hope" />
|cyber=
|families=[[Solo family/Legends|Solo family]]<ref name="A New Hope" />
|parents=
*[[Jonash Solo]]<ref name="The Courtship of Princess Leia">''[[The Courtship of Princess Leia]]''</ref>
*[[Jaina (Elder)|Jaina]]<ref name="Routine">{{Tales|2|Routine}}</ref>
|partners=*[[Bria Tharen]] {{C|formerly}}<ref name="TPS">''[[The Paradise Snare]]''</ref>
*[[Leia Organa Solo/Legends|Leia Organa Solo]] {{C|spouse}}<ref name="The Courtship of Princess Leia" />
|siblings=
|children=
*[[Darth Caedus|Jacen Solo]]<ref name="TLC">''[[The Last Command]]''</ref>
*[[Jaina Solo Fel|Jaina Solo]]<ref name="TLC" />
*[[Anakin Solo]]<ref name="DE2">''[[Star Wars: Dark Empire II]]''</ref>
|affiliation=*[[Imperial Marines]]
*[[Galactic Empire/Legends|Galactic Empire]]
*[[Hutt Cartel/Legends|Hutt Cartel]]
*[[Alliance to Restore the Republic/Legends|Alliance to Restore the Republic]]
**[[Renegade Squadron/Legends|Renegade Squadron]]
*[[Alliance of Free Planets]]
*[[New Republic/Legends|New Republic]]
*[[Bright Tree Village/Legends|Bright Tree Village]]<ref name="Star Wars Episode VI: Return of the Jedi">{{Film|VI}}</ref>
*[[Independent Shippers Association]]
*[[Galactic Federation of Free Alliances]]
*[[Five Worlds]], later [[Confederation]]
*[[Jedi Coalition]]
|masters=
|apprentices=
}}
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

