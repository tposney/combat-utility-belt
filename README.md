![https://img.shields.io/badge/Foundry%20VTT-0.4.0%2B-green](https://img.shields.io/badge/Foundry%20VTT-0.4.0%2B-green)

# Combat Utility Belt **Beta**
**Authors**: Evan Clarke (errational#2007 on Foundry discord) & Jordan Williams (Reaver#4634 on Foundry discord)

[Installation](#Installation)    
[Module Manifest](https://raw.githubusercontent.com/death-save/combat-utility-belt/beta/module.json)

 Every ~~hero~~ GM needs gadgets to keep their game safe from dastardly players up to no good!

 And where better to store those gadget than on your very own Combat Utility Belt!

 This handy-dandy combat aid comes packed with 4 gadgets to ensure you get a TPK every time.

 ## Reroll Initiative

![reroll-initiative](https://github.com/death-save/media/blob/master/combat-utility-belt/reroll-initiative.gif)

 The BBEG rolled a 2 for initiative? Not anymore! This gadget rerolls initiative for all combatants each round.

 Glorious chaos!

 ### Compatible Systems

 - [X] D&D5e
 - [X] PF2E
 - [X] WFRP4E
 - [ ] 13th Age (untested)
 - [ ] Simple/Other

 ## Hide NPC Names

![hide-npc-names](https://github.com/death-save/media/blob/master/combat-utility-belt/hide-npc-names.gif)

 Maybe you forgot that your NPC's name reveals a dark secret about their past, or maybe you forgot to give them a name.

 Fret no more, for this gadget replaces NPC names with a replacement of your choice. Personally, I'm a fan of Melvin.

 ### Compatible Systems

 - [X] D&D5e
 - [X] PF2E
 - [X] WFRP
 - [ ] 13th Age (untested)
 - [X] Simple/Other

 ## Enhanced Conditions

 ![enhanced-conditions](https://github.com/death-save/media/blob/master/combat-utility-belt/enhanced-conditions.gif)

 It's not enough to *show* your players when their poisoned, you want to really drive it  home by linking the condition so they can wallow in misery as they fail their ability checks.

 This gadget creates a dynamo-powered link between token status icons and journal entries with further info on that status effect.

 ### Condition Lab

 In here you can mix up your ~~nefarious~~ heroic combination of status icons and condition names.

 *I like the Deadly STD one!*

 ### Compatible Systems

 - [X] D&D5e
 - [X] PF2E
 - [X] WFRP
 - [ ] 13th Age (untested)
 - [X] Simple/Other

 ## Mark Injured/Dead Tokens

![mark-injured-dead](https://github.com/death-save/media/blob/master/combat-utility-belt/mark-injured-dead.gif)

 Ack! Gasp! I'm bloodied! What does that even mean? Who knows?!

 Well, now *you* do! With this gadget you can define a threshold (% of hp) that marks a token as injured. This gadget can also mark tokens as dead when their hp reaches 0. Outstanding! Now my players will have no doubt that I am the most ~~evil~~ heroic GM there was!

 ### Compatible Systems

 - [X] D&D5e
 - [X] PF2E
 - [X] WFRP
 - [ ] 13th Age (untested)
 - [X] Simple/Other

## Pan/Select Token
*full write up coming soon*

## Calculate Encounter XP
*full write up coming soon*

## Auto Roll Token HP
*full write up coming soon*
 
 
 ---

 ## Installation

 ~~Simply wrap the belt around your waist and affix the clasp.~~

 1. Navigate to the Foundry Setup screen and click on the Modules tab
 2. Click Install Module and paste in the following link: https://raw.githubusercontent.com/death-save/combat-utility-belt/beta/module.json
 3. Once the Combat Utility Belt is installed, open your desired world and ~~wreak havoc on your players~~ navigate to the Settings > Module Settings and enable the settings you want!
 
 ### Enhanced Conditions Post-Install Setup for:
 #### D&D 5e & PF2e
 To ensure you can link to journal entries to the desired condition, copy the journal entries from the included Conditions compendium into your world's journal.
 
 #### Other Game Systems
Create the relevant condition journal entries and ensure players have `Observer` permission

 ## To do
 See [Issue Log](https://github.com/death-save/combat-utility-belt/issues) 
 
 ### Top 3 Open Issues
- [ ] `Hide NPC Names` Create a flag on actors to track what PCs know about that NPC - [Issue #15](https://github.com/death-save/combat-utility-belt/issues/15)
- [X] `Mark Dead` should also mark combatant defeated - [Issue #11](https://github.com/death-save/combat-utility-belt/issues/11)
- [ ] `Enhanced Conditions` Allow linking directly to compendium entries - [Issue #19](https://github.com/death-save/combat-utility-belt/issues/19)

 ## Known Bugs
 ~~None, the Combat Utility Belt is perfect~~
~~1. `Hide NPC Names` When changing the setting for `Hide NPC Names`, the Chat Log will be rendered in whatever sidebar tab the user currently has open. This is a known issue in FVTT (https://gitlab.com/foundrynet/foundryvtt/issues/1471). -- [Issue #18](https://github.com/death-save/combat-utility-belt/issues/18)~~
~~2. `Reroll Initiative` when this is enabled and initiative is rolled from D&D Beyond using the Beyond20 extension, the combat encounter will become corrupt. **WORKAROUND**: Do not roll initiative using Beyond20, or disable `Reroll Initiative` -- [Issue #5](https://github.com/death-save/combat-utility-belt/issues/5)~~

## Thanks/Attribution
Firstly thanks to everyone who has downloaded the mod, and a special thank you to everyone who provided bug reports or feedback!

I need to acknowledge that many of the functions found in the Combat Utility Belt are inspired by API scripts for Roll20 written by Robin Kuiper (namely the Combat Tracker, Death Tracker and StatusInfo ones).

A big thanks to trdischat#2123 on the Foundry Discord for the awesome set of condition icons used in the `Dungeons & Dragons 5th Edition` mapping.
Thanks to hooking#0492 for the Pathfinder 2nd Edition condition mapping for use with his Pathfinder 2nd Edition system!

## Donations
Evan: [![paypal](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.me/evanc)

Jordan: [![paypal](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.me/reaver01)
