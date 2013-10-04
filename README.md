1D_Ants_vs_Bees
===============
     ants_gui.py

Runs the program with a cool graphical interface with sprites!

     ants.py

Runs without the graphics

Summon some Ants to defend against the Bees! Very much like a Tower Defense/Plants vs. Zombies type game
but in one-dimension. In Real-Time. Different Ants have different properties:

A Bee moves from place to place, following exits and stinging ants.

An Ant occupies a place and does work for the colony.

HarvesterAnt produces 1 additional food per turn for the colony.

ThrowerAnt throws a leaf each turn at the nearest Bee in its range.

LongThrowerAnt only throws leaves at Bees at least 3 places away.

ShortThrowerAnt only throws leaves at Bees within 3 places.

FireAnt cooks any Bee in its Place when it expires.

WallAnt is an Ant which has a large amount of armor.

NinjaAnt is an Ant which does not block the path and does 1 damage to
    all Bees in the exact same Place.

Water is a place that can only hold 'watersafe' insects.

ScubaThrower is a ThrowerAnt which is watersafe.

Bees and most Ants are not watersafe. 

HungryAnt will take three "turns" to eat a Bee in the same space as it.
    While eating, the HungryAnt can't eat another Bee.

BodyguardAnt provides protection to other Ants.


The Queen Ant is the Queen of the colony.  The game is over if a bee enters her place.
