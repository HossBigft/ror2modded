# Silly Items

Stack items when you stack items!
___

![epic screenshot!!!!!!!!](https://i.imgur.com/yBAKCkJ.png)
Feel like a badass on your 20-round run before you obliterate yourself because you have work tomorrow.

![cool stuff](https://i.imgur.com/wb4Xpty.png)

___

Ping me (`thetimesweeper`) on the ror2 modding discord or the enforcer discord (https://discord.gg/csaEQDnMH8) if you have any horrible crashes or other issues I didn't catch 
or if you wanna send some screenshots c:

___
More I'd like to do:
- Create some SillyItemDisplayRules for tweaks on how stacking behavior should be for certain items/characters.
- Make a setting where the items get bigger instead of multiplying

___
~~Plans (in order):~~
- ~~Add config max so your game doesn't lag to fuck when you have 150 teddy bears (true story (shrine of order ftw))~~
- ~~Make it work on Mul-T and Engi's turrets~~
- ~~Make it work better on Mul-T and Engi's turrets~~
- ~~Remove items when they're removed~~
- ~~Fix limb attaching issue~~
- ~~Make it work on Scavengers~~
- ~~Make items hide so the sniper scope isn't covered by crowbars~~
- ~~make it work on big moon guy~~

___

### Changelog:
`1.3.2`
 - pushed a fix to an issue where all enemies are invisible
   - I couldn't reproduce this myself so I'm fixing the recent change that I assume is the cause. If you still run into this issue, please send a log.

`1.3.1`
 - reverted some code that might be causing issues

`1.3.0`
 - updated dependencies 
   - truthfully hookgenpatcher dependency was needed for a year now but everyone always has it so it wasn't an issue, hee hee
   - don't do that, btw. I shouldn't be forgiven
 - Stacking now works for LimbMatcher item displays (namely razorwire)

`1.2.2`
  - fixed for gupdate
  - reverted default stacking behavior
  - SillyItemDisplayRules coming soon maybe

`1.2.1`
  - removed r2api dependency for now, still needs the mmhook file.
  - reach out to me if this is a bust anyways

`1.2.0`
  - changed the stacking direction to go generally outwards from the character, rather than whatever the "forward" direction of the item's model was.
  - added config to revert stacking direction to how it was before

`1.1.0`
  - made moonman spikes more spikey
  - fixed an issue with stack limit not working when you tp

`1.0.1`
  - updated for 1.0 (made it not required for multiplayer sync)

`1.0.0`
  - made extra displays properly change materials when faded/stealthed/disappeared/etc. 
  - the big one point oh, baybee

`0.5.0`
  - made it work on scavengers 
  - exposed Engi Turrets' stack distance and Scavengers' stack distance in config. Have fun!

`0.4.1`
  - removed the apostrophe in my config section "hope you're having a wonderful day" that was destroying everything 
  - this meant resetting the config file to a new one. If you had your own settings, look for the duplicated file the old cfg it should still be there thanks thanks have a lovely evening

`0.4.0`
  - fixed items attaching to wrong limbs. commandos with magazines rejoice!
  - separated my code from the game's code by using events instead of running my code directly. 
  - This means hopefully if there's something wrong in my code the entire chain doesn't horribly explode

`0.3.1`
  - fixed an error with custom items (sorry BitterestRoot we should be gucci now)

`0.3.0`
  - removed items now get removed
  - almost there bois

`0.2.4`
  - fixed an issue that was breaking BiggerBazaar
  - which spurred me to make my code more not retarded
  - sorry and thanks c:

`0.2.3`
  - oshitofuckoshitImSorry. there was a rare bug preventing Dio's from working. Pushed a fix.

`0.2.2`
  - removed logs.

`0.2.1`
  - fixed distance issue on engi's turrets and mul-t.
  - changed default distance from 0.0369 to 0.0420. Feel free to update your config.

`0.2.0`
  - now works on engi's turrets (worked on mul-t the whole time who knew)
  - removed cheats that were conflicting with others' f-key keybinds

`0.1.1`
  - fixed a small issue with itemLib 
  - learned how to make a config
  - fixed some items scaling differently

`0.1.0` 
  - c:

___

may the day treat you well