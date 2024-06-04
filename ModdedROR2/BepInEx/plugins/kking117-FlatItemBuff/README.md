## Overview
The purpose of this mod is to add some level of scaling to (what I believe are) under performing items that don't really scale with the player.
At least that's what it used to be, now I sorta just change things that I think are underwhelming or never hear anything positive about it.

Configs are provided for those that wish to tweak or disable most changes made by this mod.
The default configurations are set within the context of vanilla Risk of Rain 2, so I greatly encourage you to tweak them to better fit whatever balancing mods you're using.

## Common

<details>

### Bison Steak

**Buff**

```
- Gives 10 (+10 per stack) max health.
- Each level gives an additional 3 (+3 per stack) max health.
```

**Rework**

```
- Killing an enemy increases base health regeneration by +1 hp/s for 3s (+3s per stack).
- The effect stacks and kills extend the duration of existing stacks by 1 second.
- Health regen scales with level.
```

<details><summary>Notes</summary>Bison Steak's lack of scaling makes it ineffective as a defensive item and holds it back from worthwhile synergies. We've corrected this by making it scale with level. The rework is designed to be a remake of its older version, Fresh Meat.</details>

### Topaz Brooch

**Buff**

```
- Now gives additional barrier equal to 0.5% (+0.5% per stack) of the user's max health.
```

<details><summary>Notes</summary>Topaz Brooch is already considered a good item, this simply makes it more usable on high health builds/characters without the need for a Forgive Me Please or excessive stacking.</details>

### Roll of Pennies

**Rework**

```
- Gain 5 gold when hit, scaling over time and by the hit's proc coefficient.
- Whenever you collect gold you gain a +5 armor buff.
- The armor buff's duration is 1s (+1s per stack) plus the gold's value.
```

<details><summary>Notes</summary>Keeps its ability to gain quick money but makes it less exploitable and no longer the primary effect.</details>
</details>

## Uncommon

<details>

### Chronobauble

**Buff**

```
- Also reduces attack speed by 30%.
```

<details><summary>Notes</summary>This has been added since it's a fairly common change among many balancing mods, also helps give it an edge against its void counterpart.</details>

### Death Mark

**Rework**

```
- Pinging enemies marks them for death for 6 (+3 per stack) seconds.
- Marked enemies take 50% more damage from all sources.
```

<details><summary>Notes</summary>This is for those that find it too easy to proc Death Mark in modded scenarios. I will admit that ping aim isn't perfect so this may get replaced in the future.</details>

### Hunter's Harpoon

**Buff**

```
- Buff lasts for 1 (+1 per stack) seconds, instead of 1 (+0.5 per stack) seconds.
- Kills extend the duration if you already have the buff.
- Reduces the cooldown of your Secondary skill by 1 second on kill.
```

<details><summary>Notes</summary>Most of these changes mimic its RoRR version. It also reduces Secondary skill cooldown on kill so it's a bit more at a single stack.</details>

### Ignition Tank

**Rework**

```
- Has a 10% chance to burn for 240% base damage on hit.
- Dealing 10 hits of damage with DoTs will cause an explosion.
- The explosion has a radius of 12m (+2.4m per stack) and deals 300% (+200% per stack) total damage.
- The explosion has a proc coefficient of 0 and uses Sweet Spot falloff.
```

<details><summary>Notes</summary>Ignition Tank is infamous for being a hard synergy item, so we're broadening its usage to damage over time in general. The explosion is primarily for boosting the single-target damage of DoTs with the extra AoE being a bonus and extra flavour.</details>

### Infusion

**Buff**

```
- Increases level instead of health.
- Minions inherit the samples you've collected, but still need to have infusions to benefit.
- Elites and Bosses give more samples.
```

<details><summary>Notes</summary>With the changes to Bison Steak this is now redundant so we're broadening its effect.</details>

### Leeching Seed

**Buff**

```
- Hits heal 1.5 (+1.5 per stack) health with 50% of it being affected by proc coefficient. (Basically Withor's LeechingSeedBuff)
```

**Rework**

```
- Heals 4 (+4 per stack) health when dealing damage with a DoT.
- Attacks have a 20% chance to apply a non-stacking DoT called "Leech" for 5s.
- Anyone that deals damage to a target with Leech will heal for 10% of the damage dealt.
```

<details><summary>Notes</summary>Leeching Seed is often compared to Harvester's Scythe and in most cases the latter is considered better. Both these changes are designed to give it a use case that Harvester's Scythe doesn't share.</details>

### Lepton Daisy

**Buff**

```
- Releases the healing nova every 10 seconds during Holdout events, instead of being a limited amount based on the team's stack count.
- The nova heals 10% (+10% per stack), hyperbolically capping at 200% of the target's maximum health.
```

<details><summary>Notes</summary>Lepton Daisy suffers from being unreliable or a dead item half the time. This makes it shine in the situations it can actually be used.</details>

### Old War Stealthkit

```
- Cooldown now stacks similar to Genesis loop. (This is a nerf.)
- Has its own unique buff called "Stealthed" instead of sharing with Bandit's Smokebomb.
- Stealthed increases movement speed by 40% and gives 100 fading armor.
- Upon activation, you are forced out of "Combat" and "Danger" for 1 second.
- Upon activation, removes all damage over time effects.
```

<details><summary>Notes</summary>These changes reinforce its role as a disengagement tool.</details>

### Squid Polyp

**Buff**

````
- Squid Turrets last 25 (+5 per stack) seconds.
- Squid Turrets have 100% (+20% per stack) health.
- Squid Turrets apply tar with their attack.
- The amount of Squid Turrets each player can have is reduced, however newer turrets will replace older ones.
````

<details><summary>Notes</summary>Improves the value of stacking Squid Polyps and also reduces the clutter they can make.</details>

### War Horn

**Buff**

```
- Now gives +60% (+15% per stack) attack speed, instead of 70% attack speed.
- Duration lasts 6 (+3 per stack) seconds, instead of 8 (+4 per stack) seconds.
```

<details><summary>Notes</summary>War Horn is pretty good for a green item but once you have full uptime further stacks don't mean much. This change makes getting extra less of a dead item.</details>

### Wax Quail

**Buff**

```
- Jump boost has been removed from natural air jumps. (Mercenary's double jump for example)
- Jump boost strength is now 12m (+8m per stack), hyperbolically capping at 120m instead of 10m (+10m per stack) with no cap.
- Jump boost also gives a 20% boost to vertical jump height.
- Gives +12% (+8% per stack), hyperbolically capping at 120% movement speed while airborne.
```

<details><summary>Notes</summary>Wax Quail can be annoying to use at even just 10 stacks, these changes make stacking more valuable without ruining movement as quickly.</details>
</details>

## Legendary

<details>

### Aegis

**Buff**

```
- Excess health regen now counts towards barrier gain.
- Increases maximum barrier by 25% (+25% per stack).
```

<details><summary>Notes</summary>Now has the maximum barrier increase from RoRR. It also counts excess regen to match Rejuvenation Rack and to make it slightly less situational.</details>

### Ben's Raincoat

**Buff**

```
- Prevents 2 (+1 per stack) debuffs, instead of 1 (+1 per stack).
- There's also a 0.25s grace period after a stack is consumed where you still block debuffs but don't consume stacks.
- Cooldown now begins when a debuff is blocked instead of when all stacks of the block is consumed.
- Cooldown now lasts 7 seconds, instead of 5 seconds.
```

<details><summary>Notes</summary>Ben's Raincoat's rework in 1.2.3 is more thematically fitting but the nerf left it in a bad spot. The biggest offender is that the cooldown only starts when all stacks of its buff is exhausted which makes the value of stacking poor and unreliable, it also has the problem of stacks being easily depleted in some situations which further ruins its value. All changes made here address these issues.</details>

### Happiest Mask

**Rework**

```
- You summon a ghost of yourself that lasts 30s.
- The ghost has 300% (+150% per stack) damage.
- Any kills or deaths the ghost achieves are credited as your kills.
- You can only have 1 ghost at a time and it does not copy your items.
```

<details><summary>Notes</summary>Happiest Mask is both underwhelming and performance intensive, which is exactly what you don't want in your Legendary item. This change reduces the amount of ghosts and makes the ghost itself much more valuable and disposable than the original item.</details>

### Laser Scope

**Buff**

```
- Gives +5% critical strike chance on the first stack.
```

<details><summary>Notes</summary>This is to keep consistent with other crit items.</details>

### Symbiotic Scorpion

**Rework**

```
- Damage over time deals +1% damage per 1% health the enemy is missing.
- Every 5s Envenom an enemy within 13m for 800% (+800% per stack) base damage.
```

<details><summary>Notes</summary>While its effectiveness is debatable, it's true that there's an overlap with Shattering Justice. We're moving it to a DoT focused Legendary item since the game actually doesn't have one (likely for good reason).</details>
</details>

## Yellow/Boss

<details>

### Defense Nucleus

**Shared Changes**

```
- The projectile that spawns the construct will now replace and kill excess constructs instead of spawning nothing.
- Alpha Construct Ally are now flagged as Mechanical, meaning they're affected by Spare Drone Parts and Captain's passive.
```

**Buff**

```
- Removed "Elite" requirement for kills.
- Limited to 4 Alpha Constructs at all times.
- Constructs have 200% (+100% per stack) health.
- Constructs have 100% (+50% per stack) damage.
```

**Rework**

```
- Activates when using equipment.
- Summons 3 Alpha Constructs on activation.
- Forms a Xi Construct projectile shield on activation for 5s (+2s per stack).
- Constructs have 200% (+100% per stack) health.
- Constructs have 100% (+50% per stack) damage.
```

<details><summary>Notes</summary>This item isn't all that great when considering the requirement to proc and the fact that the stacking doesn't work well. These two options should hopefully make the item exciting to find.</details>

### Planula

**Buff**

```
- Heal from incoming damage for 10 (+10 per stack) plus an additional 2% (+2% per stack) of maximum health.
```

**Rework**

```
- While in combat, all enemies within 15m are burned for 400% (+300% per stack) base damage.
```

<details><summary>Notes</summary>While the effect is neat the lack of scaling plus how late it appears makes it a let down compared to the uncommon items a teleporter could've given instead.</details>

### Titanic Knurl

**Buff**

```
- Health and Regen increase are boosted with level.
```

<details><summary>Notes</summary>Because Bison Steak was buffed like this it only makes sense for Titanic Knurl to get the same buff.</details>

**Rework**

```
- Every 6 seconds (+15% cooldown rate per stack) a Stone Fist attacks an enemy within 60 metres for 800% (+600% per stack) damage.
```

<details><summary>Notes</summary>While Titanic Knurl isn't bad it's effect is boring compared to other boss items. This rework is made to mimic the Stone Titan's Stone Fist ability, which should make it feel more like a boss item than before.</details>
</details>

## Void

<details>

### Lost Seer's Lenses

**Rework**

```
- Has a 0.5% (+0.5% per stack) chance to detain an enemy on hit for 5000% base damage.
```

<details><summary>Notes</summary>After many runs I've found Lost Seer's Lenses to be unenjoyable due to it doing nothing against bosses and completely removing regular enemies, I've yet to see any mods that change this so I'm trying my hand at it.</details>

### Voidsent Flame

**Buff**

```
- Detonates on the user's first hit against an enemy, instead of at 100% or more health.
- Minions do not inherit it.
```

<details><summary>Notes</summary>The method to proc this item is unusual for what it is, this change makes it more reasonable especially in a multiplayer scenario.</details>

### Newly Hatched Zoea

**Rework**

```
- Activating your Special skill will launch a swarm of missiles that deal 300% (+75% per stack) base damage each.
- The swarm contains 12 (+4 per stack) missiles that get reloaded over 30 seconds.
```

<details><summary>Notes</summary>Newly Hatched Zoea is pretty underwhelming for how late it can be obtained. This rework moves it away from being a minion item and gives it the stacking potential of Shurikens, making it fairly strong by the time it's avaliable.</details>
</details>

## Artifacts

<details>

### Artifact of Spite

```
Bomb damage is based on the enemy's level instead of their base damage.
Default scaling is 12 (+2.4 per level) damage.
```

<details><summary>Notes</summary>This is a small thing that personally bugs me. There's no real way to tell how much damage each spite bomb will do so having it based on level makes the damage much more consistent.</details>
</details>

## Known Issues

- The air speed bonus from Wax Quails remains for a single tick when landing, this means if you "Bunny Hop" the jump boost is strengthened by the air speed bonus.
- For some extra notes about mod compatibility check the "Wiki" tab.

## Credits

* **Hopoo Games** - For leaving Bison Steak in its current state.
* **duckduckgreyduck** - Their GreenAlienHead mod was used as reference for some IL code.
* **Risk of Thunder's R2Wiki** - Wouldn't have been able to understand the above mod without this.
* **Moffein/Risky_Lives** - IL code references + Config & SharedHooks code.
* **TeamMoonstorm** - ContagiousItem code.
* **ChrisFeline** - Fake damage number removal for Lost Seer's Lenses effect.
* **Conq#1738** - Benthic Bloom rework concept.
* **Katsuro#1435** - Happiest Mask ideas.

## Contact

You can find me as kking117#0370 on Discord.