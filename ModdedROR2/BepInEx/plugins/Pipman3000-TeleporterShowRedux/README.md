# Teleporter Show Redux

This mod gives the ability to mark the teleporter with a few different options:

* The player is close enough to the teleporter (This distance can be adjusted in `BepInEx/config/com.Pipman3000.TeleShowRedux`)
* The player has pinged the teleporter (this can be turned off in `BepInEx/config/com.Pipman3000.TeleShowRedux`)
* All the time (this can be turned on in `BepInEx/config/com.Pipman3000.TeleShowRedux `)

## Change Log

--1.0.4--  
Everyone doesn't have to have this mod installed in a multiplayer lobby anymore.

--1.0.3--  
Fixed a NullReferenceException spam that would happen in certain scenarios in multiplayer.

--1.0.2--  
Changed how the 'Always Show' option works.  Before, if anyone in a multiplayer lobby had Always Show on, it would immediately reveal the teleporter to all other players.  This doesn't make much sense because in practice, this means it will override everyone else's settings.

Instead, players who have the Always Show option enabled in a multiplayer lobby will still be shown the teleporter's location immediately, but the teleporter will only be revealed to other players when that player would have revealed it normally (through ping or discovery).

If both ping and discovery are disabled in the config, then that player won't be able to reveal the location to anyone else.

--1.0.1--  
Fixed a typo in the README.

--1.0.0--  
Reworked the original TeleShow mod (added some settings and some small optimizations), also fixed the NullReferenceException spam when you died in multiplayer.  Additionally, Teleporter indicator status is now sync'ed across all multiplayer clients.