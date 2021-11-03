# Dev Notes

The idea is to combine Druid and Warlock into a single class, allowing PCs to decide how much they want to invest into bindings (e.g. "warlock invocations", summons, and wild shape) vs. spells, and also avoiding a name collision with 5e Warlock.

All Invokers choose a style: Pact, Bond, or Dominance.
+ Pact is Int based, and rewards cleverness, manipulation, and adherence to agreements. Allows the Invoker to learn new spells like a wizard.
+ Bond is Wis based, and rewards faith, harmony, and balance. Bindings are cheaper.
+ Dominance is Cha based, and rewards pure willpower over all. Grants more Mana.

Invokers have their own unique spell list, entirely independent from any other class. This list is divided into Alignments, which are forces the Invoker can align with, gaining access to their power through a Pact or Bond (or just plain Dominance). The Alignments are:

Alignment      | Description                     | Example Powers               |
-------------- | ------------------------------- | ---------------------------- |
Infernal       | Hellfire, brimstone, etc        | Immolate, summon imp         |
Faerie         | You know, faeries?              | Color pool, pixies           |
The Void       | Tentacles, shadowy corruption   | Voidwalker, tentacles        |
The Maelstrom  | Lightning, sea and storm        | Call lightning, gust of wind |
Wild Growth    | Life, plants, healing           | Entangle, treants            |
Deathly Hallow | Cold, death, repose             |                              |



## Bindings

Bindings are separate from the spell list for readability, but are part of the Alignments. Each rank offers one or more Bindings, which permanently reduce Max Mana to grant permanent supernatural abilities. Examples:


### General
+ [Mystic Eyes](): Binds 1 Mana; you can *Detect Magic* at will.



### Fey
+ [Fey Step](): Binds 1 Mana, recharge 33%, move; you teleport to a location you can see within 30 ft.
+ [Summon Pixie](): Binds 1 Mana; at-will, bonus; you summon a pixie servitor.
+ [Glamour](): Binds 2 Mana; you can Disguise Self at will, and have advantage to checks to persuade, seduce, etc.



### Infernal
+ [Born in Flames](): Binds 1 Mana; constant; you are resistant to fire damage.
+ [Summon Imp](): Binds 1 Mana; at-will, bonus; you summon an imp servitor.
+ [Devil's Wing](): Binds 3 Mana; at-will, bonus; you sprout wings, granting a fly speed equal to your walking speed.


### Shadow
+ [Shadow Sight](): Binds 1 Mana; constant; you can see in the dark, even in magical darkness.
+ [Shadow Discorporation](): Binds 2 Mana; recharge 33%, bonus; you become incorporeal and can fly at a speed of 50 feet for 1 round.



### Life / Animals

#### Rank 1
+ [Wild Shape](): Binds 1 Mana; at-will, bonus; you shift into the form of an animal of your CR / 3 (but not one with a special movement type such as flight, swim, or burrow).

#### Rank 2



## Spells

### Infernal

Level | Spell            | Brief
----- | ---------------- | ---------------------------------
0     | Immolate         | Set enemies on fire
1     | Curse of Agony   | Disable enemies with pain
2     | Bolt of Spite    | Poison an enemy
3     | Conflagrate      | Set more enemies on fire
4     | Wave of Pain     | Disable enemies around you with pain
5     | Chaos Bolt       | Enemy suffers a variety of unhappy effects
6     | Inferno          | Meteor crushes enemies, explodes, then unleashes an uncontrolled monster
7     | ?
8     | Hellball         | Massive, uncontrolled eruption of infernal power
9     | Hellmouth        | Portal to Hell unleashes demons, sucks in hapless enemies


### Fey

Level | Spell            | Brief
----- | ---------------- | ---------------------------------



### Air

Level | Spell                | Brief
----- | -------------------- | ---------------------------------
1r    | Whispering Wind      | Send message a long way via wind
0     | Gust of Wind         | Moves subject a small way
0     | Rejuvenation         | Subject can instantly use Hit Dice
*     | Summon Air Elemental | Summons various types of element (add Mana to increase power)
1     | Lightning Strike     | Target is zapped
2     | Control Wind         | Create wind wall, wind tunnel, etc
3     | Lightning Shield     | Zap anyone who tries to touch you
4     | Thunderlance         | Line of lightningy sonic doom
5     | Chain Lightning      | Lightning, but in a chain
6     | Tranquility          |
7     | Wall of Lightning    |

Upgrades:
+ Gust of Wind
  + Slide
  + Boost
  + etc
+ Lightning Strike
  + Static Cling
  + Ball Lightning

Bindings:

Level | Mana | Name          | Effect                                            |
----- | ---- | ------------- | ------------------------------------------------- |
1     | 1    | Windtalker    | Mildly control wind at will                       |
2     | 2    | Pillar of Air | Levitate on a column of air                       |
3     | 3    | Lightning Rod | Resist (lightning), gain temp Mana from lightning |



### Earth

2     | Earth Shaping        | Harden/soften ground, change its texture, manipulate natural stone, etc
?     | Wall of Stone



# Paths

Path            | Description                             |
--------------- | --------------------------------------- |
Channeler       | Manifest your alignments                |
Summoner        | Permanent minions, better summons       |
Bladebound      | Summonable weapons/armor, armiger       |
Shaman          | Merge summons into your body            |
