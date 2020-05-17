# Between the Bubbles collaboration conventions

## Collaboration model

The `master` branch should be left untouched and we can contribute to its changes from separate branches.

## Branch names conventions

feat_* - for features  
fix_* - for corrections  
morph_* - for tasks on code other than feat or fix. Examples: refactor, comment, readability improvement  
docs_* - for documentation  
chore_* - for maintenance stuff  

## Game feedback and discussions

Feedback and discussions are shared with the [ThinBasic community](https://www.thinbasic.com/community/forum.php "ThinBasic's community forum")

## BTB Glossary

### E

#### ECS
[Entity component system](https://en.wikipedia.org/wiki/Entity_component_system)


### G

#### gameZone
A gameZone is one elemental square that constitute a world. Many gameZones are necessary to represent a world. All the game happens in gameZones. Outside gameZone is called the void. GameZones are constituted by tiles and contains items, characters..


### I

#### item
An item is an object that can be seen while in-game in a gameZone. It is placed on a tile.


### L

#### level (lvl)
A level is an aera composed by _minimum_ one world. The player must have achieved all pre-set requirement to access the next level.


### P

#### Pilgrim
The Pilgrim is the main character controlled by the player.


### T

#### the Pilgrim
see **P**ilgrim

#### tile
A tile is a decorative shape (usually a square) that can be seen while in game. Many tiles are necessary to draw a gameZone.


### U

#### universe
The Between The Bubbles (BTB) universe is all that compose the game (rules, worlds, characters...)


### V

#### void
The void is the space of the map that is between gameZones. It is not part of the game.


### W

#### world
A world is an aera of the game composed by many gameZones of the same theme ("Countryside", "The city", "A calm pool" ...)
