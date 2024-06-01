## Overview

This mod makes consumable items more useful by having their consumed version provide small bonuses. These bonuses are designed to soften the blow of losing the original item.
This is technically the successor to my older DioToTougherTimes mod.

Configs are provided for those that wish to tweak or disable most changes made by this mod.

## Item Changes

**Delicate Watch (Broken)**

```
- Every 12th hit procs the item.
- Every 12th proc doubles the effect.
- Deal an additional 20% (+20% per stack) damage on proc.
- Applies a 1s (+0.25s per stack) 60% Slow on proc.
```

_With Tentabauble replacing Chronobauble, this effect is actually quite nice for getting Death Mark online._

**Power Elixir/Empty Bottle**

```
- Grants the Regenerative Buff for 2.5s when consumed. (For reference it heals at 10%/second.)
- Gives 1 hp/s (+1 per stack) regen.
```

_I found Power Elixir's heal to be very underwhelming in many situations, the regen buff should help it feel impactful especially in more hectic situations._

**Dio's Best Friend (Consumed)**

```
- Grants a 15% (+15% per stack) chance to block damage.
```

_This is a callback to an older mod of mine, Dio's Best Friend doesn't really need it._

**Pluripotent Larva (Consumed)**

```
- Corrupts all new items collected not just the items you had when it was consumed.
- Blocks a single instance of damage, recharges after 15 (-10% per stack) seconds.
- Has a 10% (+10% per stack) chance to apply Collapse on hit dealing 400% base damage.
- Gives -10%(-10% per stack) Max health in the form of a curse.
```

_The "Get a corrupted extra life." flavour text sounded a lot cooler than what it actually does so I decided to make it more interesting. This is also somewhat meant to mimic the abilities of Void Touched elites._

## Known Issues

- None for now.

## Change Log

**1.2.4**

```
Pluripotent Larva (Consumed):
- Fixed on hit code blocking later ServerDamageDealt hooks.
```

**1.2.3**

```
Pluripotent Larva (Consumed):
- Redone code so it's less prone to break with mods that change Safer Spacers or Needle Ticks.
- Added "Collapse Chance", "Collapse Damage", "Collapse Total Damage" and "Block Cooldown" configurations.

Dio's Best Friend (Consumed):
- Redone code so it's less prone to break with mods that change Tougher Times.
- Added "Block Chance" configuration.

Empty Bottle:
- Changed "Passive Regen" default value. (0.6 -> 1.0)
```

**1.2.2**

```
Delicate Watch (Broken):
- Fixed it applying Symbiotic Scorpion's debuff instead of dealing bonus damage.

Misc:
- Added Delicate Watch (Broken) and Empty Bottle's descriptions to all languages as a fall back.
```

**1.2.1**

```
Pluripotent Larva (Consumed):
- Updated the item corruption to reflect the changes made in Patch 1.2.3.

Misc:
- Empty Bottle's modified description is now English only, so it overwrites WolfoQualityOfLife's description.
- Delicate Watch (Broken)'s modified description is now English only, for the above reason.
```

**1.2.0**

```
Configs:
- Basically renamed all the categories so they reference the actual item instead of its unconsumed version.

Delicate Watch:
- Added a buff indicator to track hits.
- Hits on the same frame are now counted, previously it didn't, this was intentional but I've changed it for simplicity.
- This also means you can't proc the watch multiple times in a single frame, meaning you won't hear a loud breaking sound from hitting 10 enemies at once.
- No longer counts hits that deal 0 damage, before it only ignored hits that were blocked/rejected.
- Renamed "Hits To Proc" configuration to "Hit To Proc".
- Renamed "Hits To Proc Super" configuration to "Proc to Double Proc".
- Default value for the above changed. (144 -> 12)
- "Stack Slow On Proc" configuration now doesn't count the first item in the stack.
- Changed "Base Slow On Proc" default value. (0.75 -> 1)

Power Elixir:
- Fixed "Regen Buff Duration" not actually changing the buff's duration.
- Changed "Regen Buff Duration" default value. (1.25 -> 2.5) (It was intended to heal the last 25% Elixir would miss, the old value was actually too low.)
```

**1.1.0**

```
- Changed "Damage On Proc" to change the damage bonus it gives.
- Changed "Passive Regen" default value. (1 -> 0.5)
```

**1.0.0**

```
- Public release.
```

## Credits

* **Hopoo Games** - For this cool DLC.

## Contact

You can find me as kking117#0370 on Discord.