Flotilla
========
(working title)

A game design for a hybrid scrolling shooter and tactics game.

In Flotilla, you control a group of up to ten spaceships fighting level after level of the alien menace.

###Enemies
The game is a scrolling shooter in that enemies appear from the top of the screen and hover on the screen until defeated.

###Ship Grid
At the bottom of the screen is a 5x2 grid of spacecraft. Not all grid tiles have to be filled. Your spacecraft fire automatically, normally at the closest enemy within the firing arc of their weapon.

###Interface
You can reposition the ships by dragging them to a new tile. The movement doesn't happen instantaneously: some ships move faster than others. When possible, ships move horizontally to make space for the incoming ship. When you move a ship into a full row, it instead exchanges places with the other ship. Ships keep firing as they move laterally.

###Shooting and Damage
Compared to normal scrolling shooters, damage is lower: ships can take multiple hits before being destroyed, and may also repair automatically to some degree. Shots have to actually intersect their target, which means it's possible for them to miss, and it's possible to evade shots with careful repositioning. Shots are also comparatively slow-moving to allow for such manoeuvres. Ships' hitboxes are fairly generous and a complete front row tends to block 80-90% of shots.

###Indications
The following information must be visible about your ships:

* Type
* HP/Damage
* Statuses (frozen, etc.)

###Upgrades
Between levels, the player can purchase new ships or possibly upgrade them.

###Possible Ship Types
* Standard/Cruiser: 90&deg; firing arc, semirapid fire, reasonable speed and HP
* Frigate: 120&deg; firing arc, slow weak longrange fire, fastish, low HP
* Lancer: 0&deg; firing arc, slow powerful beam fire, faster but less HP
* Brawler: 120&deg; FA, short-range powerful weapons, slower but more HP
* Missile Boat: homing missiles, slow, low HP
* Laser Boat: 0&deg; FA, quick weak beam fire
* Shielder: like standard, but has 3 tile wide energy shield in front
* Teleporter: 0&deg; FA, slow powerful shots, instantly switches places
* Battleship: 180&deg; FA, slow powerful shots, slow but massive HP
* Healer: no weapon, repairs nearby ships
* ECM: like standard, but lower HP and confuses enemy missiles
* Ion Cannon: 90&deg; FA, slow, shots stun targets
* Kamikaze: 90&deg; FA, semirapid fire, fast, lowish HP, can sacrifice to clear enemies
* Carrier: spawns 4 drones that harass enemies
* Burner: 90&deg; FA flamethrower, slowish, good HP
* Sensors: no weapon, makes shots of adjacent ships faster and more accurate
* Battery: no weapon, doubles fire rate of ship in front

###Possible Upgrades
* Basic stat upgrades: speed, HP, damage, cooldown, shot speed
* Anti-missile turret
* Single-use torpedo
* Emergency teleport (ship vanishes instead of dying, you get it back at the end of the level)
* Scavenger drones: repair from passing debris

###Alien Menace Ship Abilities
(These are hard to do in UI but still fun.)

* Splitting into two on death
* Lobbing immobilizing goo
* Temporary invulnerability
* Larger (2x2 to 5x2) ships
* Mutual HP steal to prevent death
* Cloaking
* Ripening, then releasing drone swarm

###Variants
####Multiplayer
Given the symmetry of the sides, this could be 2-player multiplayer, assuming latency isn't too deadly.
