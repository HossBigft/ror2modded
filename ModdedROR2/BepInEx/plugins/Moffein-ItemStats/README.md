A lightweight mod that makes item descriptions more detailed.

Unlike the deprecated ItemStatsMod and BetterUI, this does **NOT** calculate stack stats.

Client-side and vanilla-compatible.

Based off of ontrigger's ItemStatsMod (https://thunderstore.io/package/ontrigger/ItemStatsMod/)

## Features

- Full item description is shown on hover and pickup.
- Pinging items shows their description.

Each feature can be enabled/disabled in the config.

## Installation
Place ItemStats.dll in /Risk of Rain 2/BepInEx/plugins/

## Changelog

`1.3.1`

- Increased default Ping Details duration from 2s -> 3s

`1.3.0`

- Reduced duration of Ping Details from 6s -> 2s (can be changed in config)

`1.2.2`

- Fixed pings revealing the contents of Cleansing Pools.

`1.2.1`

- Fixed items without descriptions (ex. Consumed Power Elixir) showing the raw token string.

`1.2.0`

- Fixed pings being able to reveal ? Shop contents.
- Added support for Equipments.
	- For Devs: Added EquipmentDef IgnoreList

`1.1.3`

- Fixed an oversight related to the IgnoreList and Ping Chat Messages.

`1.1.2`

- For Devs:
	- Added an internal ItemDef IgnoreList. Items on this list will not have their short pickup description replaced.

`1.1.1`

- Icon update

`1.1.0`

- Ping info now shows as a HUD Notification.
	- Chat messages can be re-enabled in config.

`1.0.0`

- Release