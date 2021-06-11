# Rise Up!
Action-adventure game

# Changelog

## BETA  v1.0.0
___

### What's new?

- More sounds was added (More sounds will be added in the next update)
- New menu and in-game music

___

### Changes

- Some of the light sources in level 01 was deleted
- FadeIn delay for music at the start of the level was increased from 0.2 -> 0.4s
- Some of the hints was changed
  - Some of the mechanics should be described in more detail 
- Removed half of unused assets for optimization purposes 
- Collect sound was changed for a better one

___

### Bug Fixes

- Checkpoint collider in level 01
  - Apparently, under some circumstances, it may not appear. We fixed that (Let us know, if for some reason it doesn't appear again)
- Adaptivity bugs was fixed

___

## v0.4.0 - May 27, 2021
___

### What's new?

- This new version brings some UI elements and effects
- New improved menu
- About page
- Options Menu UI
- Main Menu UI
- Quit Stopper UI
- Pause Menu UI
___

### Changes

- Skeleton health was increased from 30 -> 40
- Pick up system was slightly changed, which brings some improvements and fixes most of the bugs associated with this mechanic 

___

### Bug Fixes

- Fixed UI buttons animations 
- PickUp system deals double damage to all enemies except minotaur
  - Now works like it should
- Save button in options menu doesn't work on level 02 and level 03.
  - Problem solved, design improved 

___

## v0.3.0 - May 10, 2021
___

### What's new?

- The "Final" level is ready and open to all players
- New in-game and menu music
- New hotkey for restart the level. Use "TAB" key to restart the level

___

### Changes

- Pick up object system was slightly changed (u don't recognized any difference, but just know this;
- Fireball "twirl" effect was removed
  - Due to your feedback, it was decided to abandon this idea. 

___

### Bug Fixes

- Save button doesn't work on level 02 and level 03
  - Now it works fine

- Sphere on level 01 has an incorrect light.
  - The correct color is being used now  

- Object deals damage to enemy when he walk on it
  - Previously, objects around did damage to enemies when they touched them. Problem has been terminated (Maybe not).  

- And bunch of little fixes

___

## v0.2.1 - May 01, 2021
___

### What's new?

- Banner Hint.
  - Dynamic hint that will help player find some stuff. (For those type of players that still can't find the button at level 03)
___

### Changes

- Enemies health was decreased for create more casually type of gameplay 
  - Bes health from 30 to 20
  - Demon health from 60 to 40
  - Skeleton health from 45 to 30
  - Spirit health from 30 to 25
- A quarter of the enemies were removed in the third level 
- Level 02 now have a hint after player picking up a scroll. 
___

## v0.2.0 - April 28, 2021
___

### What's new?

- Path Notes! Oh, wow!
- Royal stash now open to explore 
- Options menu.
  - Now u can modify some settings. (You can't customize the controls at the moment, but it's temporary (maybe not)). 
- Music!
  - If u catch a bug with overriding music just press "M" on your keyboard, music should be restarted without overriding.
- Enemies Improvements.
  - All enemies' animations now play correctly. Enemy behavior has also been changed. (Some of them still got animation bugs, we fix them someday. Maybe) 
- Adaptive UI
  - Now all UI elements adapt to your screen size 
- The level selection screen now looks more presentable
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
