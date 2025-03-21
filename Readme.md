# Saradas Magic for BGEE / EET

![Language](https://img.shields.io/static/v1?label=language&message=english%20%7C%20Italian%20%7C%20&color=informational)

**Autor** : **Saradas**

[Link to original Mod Forum](http://www.shsforums.net/topic/58028-mod-saradas-magic/)

[Link to original Mod Download](http://www.shsforums.net/files/file/1120-saradas-magic/)


## What's Saradas Magic :
------------------------

Saradas Magic is a mod that introduces a new non-playable NPC, Saradas the archmage, which interacts in various ways with the Bhaalspawn's group.
You can find him in the temple inside the Friendly Arm Inn.
In addition to having several exclusive dialogues that take place as the plot takes shape, it offers:

- Identification at reduced price
- Cure the party when one or more members of the group are seriously injured
- An advanced artificial intelligence scripted by me that offers an epic fight even to the game's veterans
- A store with exclusive articles

In the latter, you can find 7 brand new arcane spells:

- Flawless Teleport
- Lashing Wind
- Gravitational Field
- Horrid transformation
- Drain Spell
- Spectacular Combustion
- Tenser's Supremacy

(The prices are not very cheap but you can still try to steal from the store :]  )


The aim is to improve the tactical approach to the game as a magician, in the battles of the Sword Coast, creating dozens of new
devastating combinations.

Teleport behind an opponent and turn it into a pathetic zombie.
Summon a demon prince to tear your enemies apart.
Turn yourself into a fearsome Lich and drain the life out of your rivals up to send them into the abyss.
Crush the will of your enemies and then finish them off with a burst of spiritual energy.
Get the appearance of a dragon and lay waste wherever you go!
Turn the most dangerous of wizards to a meek kitten by stealing his spells or wrapping him in a burst of wild magic.



All this is possible thanks to the epic level spells, available for each school of specialization, and taught by Saradas :

- Spiritual Explosion (Invocation)
- Impenetrable Defense (Abjuration)
- Ego's Frailty (Transmutation)
- Summon Devil of Baator (Conjuration)
- Foreseeing the future (Divination)
- Absolute abnegation (Enchantment)
- Legion of shadows (Illusion)
- Deathly Hallows (Necromancy)
- Knowledge of the Scholar (Generalist)
- Shroud of wild magic (Wild magic)
- Dragonborn (Dragon Disciple)

(working on pure mages, multi-classed mages, dual-classed mages)


## Side notes :
---------------------

The mod will introduce heavy imbalances in BG:EE because it has been designed for BG2:EE.
The intention of adapting it to BG:EE is to give an alternative gaming experience to players who enjoy power-play or to those who remove
the experience cap.
It also serves to prove the contents of the mod itself waiting for the release of BG2:EE.
The mod can be installed at any time, without compromising the current save game, and making it still enjoyable at 100% of its contents.
Removing the mod will not cause flaws in the game nor will it corrupt save files.


## How to install the mod :
----------------------------

Extract the folder "Saradas_Magic" (entire folder, not single files) and "setup-saradas_magic.exe" to --->  X:\BGEE\Data\00766.
 
 *You will now have:  X:\BGEE\Data\00766\Saradas_Magic
 *setup-saradas_magic.exe  must be put in  X:\BGEE\Data\00766

-Be sure that there's a "override" folder in that path. If not, create it.   X:\BGEE\Data\00766\override

-Now run the executable file, it will ask you what is the language of your game, select "english" and then [I] - install.
                                                                                                            

At the end of the operations, the program will report a successful statement.


## How to uninstall :
---------------------

It's quite easy, just run "setup-saradas_magic.exe" and select [U]-uninstall
All the mod's related files will be erased from the override folder without corrupting the game's integrity in any way.


## Version History:
----------------

CHANGELOG: V_1.3

* Correct tp2 (missing Autotra)


CHANGELOG: V_1.2

* Add...
`IF
  GlobalGT("ENDOFBG1","GLOBAL",0)
THEN
  RESPONSE #100
    DestroySelf()
END`
...for EET continuity

* Add Readme.md

* Add g3_bgee_cpmvars.tpa and %area_prefix% for EET compatibility

* Change name of files for compatibility with Saradas Magic for BG2

* Change name of variable for compatibility with Saradas Magic for BG2

* Files association for new name of files

* BWP fix change `COMPILE ~saradas_magic/baf/AR2304.baf~` to `EXTEND_BOTTOM ~ar2304.bcs~ ~saradas_magic/baf/AR2304.baf~`

* Add Italiano from original version

* Add Handle Charset and IconV

CHANGELOG: V_1.1

* Gravitational Field spell rebalanced. Saving throw vs spell has been increased to +2, from -1.