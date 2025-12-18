# todo

- REFACTOR! need a refactor quite badly now; weapons, inventory, and ECS most of all
- add weapon reloading time for musket, pistol, and blunderbuss
- move descriptions, names, etc to separate config files so the program isn't cluttered with all the hard coded stuff
- add black powder to supplement pistol/musket/blunderbuss ammo
- different types of weapon mod and load (e.g.: blunderbuss with shot vs pebbles vs fire?)
- debug mode
- ECS refactor
- bonus items (health, armor, ammo, etc)
- sound management (play groups of sounds, stop playing sounds over others, central management)
- combat
    - ethereal crossbow
    - hellstaff
    - phoenix rod
    - firemace
    - dragon claw
- when out of ammo switch automatically to next lowest powerful weapon?
- user-specified maps
- wall and floor materials
- make some items only spawn in rooms for corridors
- scripting to define triggers and special events in user-defined maps
- inventory items
- inventory management and item use
- traps
- explosions
- knockback
- make entities a map instead of an array for faster lookups
- control hints on status line (like showing 'use (d) to descend stairs' when player on stairs tile)
- scheduling and processing entity actions
- take entity speed into account in scheduling actions
- points/scoring
- obstacles to add cover
- diagonal movement
- multiple enemy types
- ai behavior for each enemy
- randomly generated enemy/env.player names
- randomly choose from different types of map each map (eg dungeon, cave, arena, etc)
- powerups and conditions that change visibility
- "super dark" maps where fov is very limited, down to a 90 degree arc for example
- light sources other than the player
- enable strict null checking
- make the messages log longer (or keep the rest on the dev console or something?)
- camera support to allow larger maps (dont mess with this until much later)
- automated testing
- determine licensing required to include heretic shareware sound files/graphics/levels (ie: can I redistribute
  the shareware heretic wad file with the copyright notice from that distribution?)
- event loop for processing instead of keyboard input triggering game.turn directly
- sprites
- animations
- lighting effects (blinking, flickering, pulsing, etc -- need animation and event loops for this)

later

- choose random monster position outside some specified distance (dont crowd env.player)
