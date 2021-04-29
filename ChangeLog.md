# Rise Up!
Action-adventure game

# Changelog

## v0.2.0 - April 28, 2021
___

### What's new?

- Path Notes! Oh, wow!
- Royal stash now open to explore 
- Options menu.
  - Now u can modify some settings. (You can't customize the controls at the moment, but it's temporary (maybe not)). 
- Enemies Improvements.
  - All enemies' animations now play correctly. Enemy behavior has also been changed. (Some of them still got animation bugs, we fix them someday. Maybe) 
- Adaptive UI
  - Now all UI elements adapt to your screen size 
___

### Changes

- Enemies now have slightly increased health.
  - They dying really fast, so we increased their health to make them more dangerous.
- if you hit the enemy by throwing an object at him, he will have an increased detection radius (it works only once on the enemy);
- Box model.
  - The old box didn't fit well into the game, so we replaced it with a new model. 
- Melee enemies now run faster. (Enemies run speed was increased from 100% to 150%)
  - Melee enemies are not particularly dangerous at the moment. We're increasing their speed to make it easier for them to corner the player. 
- Barrel collider
  - We deleted a mesh collider and replace it with a box. It will make jumping and control slightly easier 
- Player movement speed was too fast for enemies, so we slightly decrease it (walking from 10 to 8, running from 16 to 14)
- Materials of the most objects has been slightly changed.
- Doors will no longer push you away if you stand too close to them.
- Secret (purple) shards can only be picked up 
- Damage from most throwable items has been reduced
- Object pick up distance increased from 2 to 2.5
- Increased brightness in environment lighting on level 2
- Ledge system was slightly reworked
- Level 02 was slightly reworked
___

### Bug Fixes

- Objects deal double or triple damage when collide with enemy.
  - Now it deals damage only once per collide;
- Enemy playing "die" animation when player damage them over and over.
  - Enemies will no longer detecting collision after death, which makes the enemy invulnerable to damage. That should fix this problem;
- CheckPoint ladder in Prologue now appears properly
- Door will no longer freezing if player spamming "Use Button" (which is "E" by default)
- "Fireball Upgrade book" now increases your damage as it should  
- "Strange book" in "Uninvited Guest" level. 
  - No more flying books in our house
- Menu button doesn't work at all
  - Now works as it should
- Some of the walls doesn't appear after find a secret or collecting all shards
  - Now It's looking as it should
- After throwing an object, enemies who stumbled upon it received damage and died
  - We fixed this issue and everything should work smoothly now 
- Portal Gate Mesh collider problems.
  - We changed the portal model to match the player so as not to cause problems with the collider 
- And much more little fixes
