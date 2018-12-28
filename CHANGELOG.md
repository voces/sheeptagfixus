## Version 1.13
- Reduce kills for Doom Guard (50 -> 40)
- Fixed bug that allowed shepherds to get gold for killing images/allies
- Removed special effect for "Grim"
- Doubled mana regen per int (0.05 -> 0.1)

## Version 1.12
- Fixed -g x
- Increased range of Power Tower (1000 -> 1250)
- Decreased damage of Power Tower (250 -> 200)
- Decreased HP per Str (1000 -> 500)
- Fixed "Suggested Players" ("7v5 - Best Play" -> "6v3")
- Increased Increase Attack Speed of Gloves of Haste (15% -> 30%)
- Changed abilities of Black Wolf (Critical Strike -> Divine Shield)
- Changed abilities of Doom Guard (Critical Strike -> Divine Shield)
- Increased movement speed of Goom Guard (405 -> 410)
- Increased gold cost of Frost Farm (40 -> 60)
- Decreased build time of Frost Farm (13 -> 5)
- Decreased build time of Aura Farm (5 -> 4)
- Increased gold bounties of various farms (primary farms)
- Sheep are once again removed when player leaves
- Movement speed bonuses now stack
- Fixed issue with -buy and -sell
- Added Claws of Attack +50
- Modified Dagger description
- Tomb of Retraining removed
- Added some Proper Names to Wolves.
- Added Claws of Attack +9 to item list.
- Modified all Claws of Attack Pricings
  - +6: 18
  - +9: 36
  - +12: 60
  - +21: 126
  - +50: 350
- Reduced Sheep Stalker damage (56 -> 23-25)
- Increased movement speed of Rock Golem (330 -> 340)
- Reduced Sheep Stalker movement speed (425 -> 420)
- Doubled Mirror Image duration (60 -> 120)
- Increased Mirror Image split Distance
  - Level 2: (128 -> 192)
  - Level 3: (128 -> 256)
- Increased Scout duration
  - Level 1: (60 -> 90)
  - Level 2: (90 -> 145)
  - Level 3: (120 -> 180)
- Decreased Stun Farm build duration (10 -> 2)
- Decreased Power Tower build duration (5 -> 4)
- Increased Magic Farm hit points (120 -> 200)
- Added Cloak of Shadows
- Fixed buy/sell glitch involving illusions
- Decreased Divine Shield Cooldown (+5 duration, respectful to level)
- Decreased Sheep Stalker Range (40 -> 32)

## Version 1.11
- Made all content RoC-friendly
- Nerfed Battleship
-     Changed to Doom Guard (RoC/TFT reasons)
-     Reduced range to 64
-     Increased movement speed to match Black
-     No longer flying
- Necklace changed to Spell Immunity
- Divine Shield cooldown decreased (+15/+10/+5 of duration)
- Slightly increased range of CoF by 16
- Buffed damage of CoF to 15
- Increased Stack Farm HP to 15
- Decreased sheep cooldown time on attack by .1 seconds
- Decreased backswing by .05
- Decreased damage point by .075
- Increased ward duration by 60 seconds
- Computer gold is distributed when possible (checking every three seconds), only for shepherds
- -buy can now be done on controlled units
- -sell can now be done on controlled units
- Dolly freezes whoever kills her for 60 seconds
- Can now attack other shepherds
- Added Power Tower
- Changed format to 8v4
- Double Jotye Farm's aura
- Removed Spell Immunity from Black and Imba Wolves
- Added Gloves of Haste
- //Can no longer stack on wisp - NOT ENABLED

## Version 1.10
- Updated contact information
- Change shepherd kill return to (sheep+wisp)/shep*10 (+25% for killer)
- If a shepherd leaves during beginning countdown, their shepherd should still spawn
- Price of cheese increased to 2/3
- Wood earned changed to 2
- Claws of Attack +6 is now in the item list (can be -sell and -buy)
- Golem base damaged decreased 28 -> 20
- Shepherd inital mana decreased from 300 to 0
- Shepherd mana regen doubled from .25 to .5
- Stack Farm sight radii increased by 300
- Basically disabled attack pings
- Users with "Grim" in their name get special effects

## Version 1.9
- Game should now end when the last player of a team leaves
- Full shared control is now granded via the allies menu
- Added the Jotye Farm for Silver and Golden Sheep
-     100 gold
-     Inverts point orders in 512 area
-     5 bounty
- Added -d on and -d off along with D ability
- Added the Gem easteregg
- Added the Dolly eastereggs
- Fixed the -c/-uc messages
- Renamed the Silver Sheep to Silv3rSheep
- Renamed the Golden Sheep to GoldenSheep
- Changed Reaction Delay to 0 from .25
- Changed Attack Notification Interval to 1 from 30
- Changed Attack Notification Range to 256 from 1250
- Nerfed the Battleship
-     Changed movement speed to 405 from 522
-     Changed range to 128 from 500
-     Added projectile animation
-     Changed some other stats...
- Dagger now works on RoC

## Version 1.8
- Wards changed back to 1.6 (using SetUnitPosition)
- Lowered shepherd base damage to 12 (to compensate 1.7 changes in damage)
- Sentry Ward True Sight increased from 1100 to 1200
- Fixed the -g text.
- Fixed fatal error on -g command.
- Increased Sentry Farm True Sight range from 900 to 1200.
- Added the battleship.
    
## Version 1.7
- -buy no longer turns shepherds black
- Killing shepherds now only get +25 gold rather than 10 * sheep
- Added some Clan StH spam
- Hopefully fixed some desyncs
- Auras now target structures
- Wards can truly be placed anywhere
- Stun farms have a lot more damage, 20 to 50 base
- Stalkers can now be killed via manaburn
- Removed w3mmd support
- Can no longer gold yourself
- Stacks now have 10 hp as opposed to 50
- Wards die in 180 seconds
- Black Wolves are now spell immune instead of invul
- Buffed Boots of Speed, 5 to 30
- Shepherds are actually killable
-     100 base HP, .5 base regen
-     1000 HP per str, .25 regen per str
-     4.8 str per level
-     9.6 str per level - black
- Tiny farm has standard farm model
- Devotion Aura now adds 3 armor instead of 1
- Added Dolly
- Shepherds are now agility heroes
-     2.4 per level
-     3.6 - black

## Version 1.6
- Ward can no longer be casted across the map
- Wards cost 50 mana to use
- Shepherds can level again

## Version 1.5
- Fixed issue with constant data (item/farm IDs) were completely wrong
-     Fixed -buy, -sell, and kill return

## Version 1.4
- A lot of changes I did not record. --------------------
- Modernized the map a bit, miscGoldTick/X
- Ward works! Full RoC compat.

## Version 1.3
- When a sheep or wisp leaves, their main unit is now removed
- Control is now given to allies when someone leaves
- Resources are now split up when someone leaves
- Cloak of Flames now has an artistic effect on structures
- The icon for the Golden Sheep now comes at 25 saves instead of 20
- Rewarded gold to killing shepherd is now dependent on allies who are still in the game
- Wisp are now flying and can walk over stacks
- A victory message was added for winners
- Added the -sell command
- Structures are now removed instead of killed when mass events occur
- The unit follow distance was changed from 300 to 0
- The unit max movement speed was increased from 500 to 522
- The unit min movement speed was decreased from 150 to 0
- Fixed spelling of Fixus on multiboard
- Fixed issue with not being able to give control

## Version 1.2
- Wisp no longer generate 1 saving gold tick
- Removed fai (have to manually embed)
- Shep now gets a cloak of flames when achieving black
- Can now smart wisp to save
- Fixed issue of showing gold gains as both gold and XP
- Fixed cloak (no longer targets sheep or is effective when worn by image)
- Fixed Low Upkeep status
- Increased cloak range by 80

## Version 1.1
- Fixed camera scroll on saving (would scroll to start location, not spawn location)
- Fixed "140 gold on save" (text displayed 140 instead of 100)
- Fixed Orb of Fire (now corretly targets)
- Fixed Sabre (now correctly targets)
- Shepherds no longer recieve 1000 gold every tick
- Hopefully fixed joining issue by internalizing fai