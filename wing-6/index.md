---
title: 6. Mythwright Gambit
layout: page
nav_order: 6
parent: Guides
---

[< Wing 5](../wing-5/){: .btn } [Return to Home](../index.html){: .btn } [Wing 7 >](../wing-7/){: .btn } 
{: .center}

# Mythwright Gambit
{: .no_toc}

| **Timer** |  16 minutes 30 seconds |
| **Timer Start** |  On entering combat with Conjured Amalgamate. |

<details>
<summary><b>Table of Contents</b></summary>
<div markdown=block>
1. TOC
{:toc}

---
</div>
</details>

Mythwright Gambit speedrunning varies greatly based on the week, as [Minipets] takes much longer to clear than [Ooze]. Most time gains revolve around an efficient [Conjured Amalgamate], a good transition from [Twin Largos] to [Qadim], and a fast [Qadim] kill. The Infallible timer for this wing is very liberal on [Ooze] weeks, but can become tight with bad [Minipets] RNG.

---

#### Main Points
{: .no_toc}
- [Conjured Amalgamate] is played with a non-standard strategy that depends somewhat on RNG.
- [Sorting and Appraisal] can be either trivial on [Ooze] weeks or difficult to optimize and RNG-heavy on [Minipets] weeks.
- [Twin Largos] is played with a standard strategy with a few minor optimizations.
- The transition between [Twin Largos] and [Qadim] can be heavily optimized.
- [Qadim] strategies vary around the handling of [Pyre Guardians].

---

## Composition

Mythwright Gambit requires many specialized roles so composition requirements can be rather strict.

Two <img class='inline mesmer'> [Mesmers] are often run since they bring great utility and can vastly speed up the transition from [Twin Largos] to [Qadim].

---

#### Conjured Amalgamate
{: .no_toc}
- Even though damage pressure is low, it is worthwhile to run two healers since they are often off-stack.
- Since <img class='inline pull'> [Pull] and projectile management are very strong here, both healers are often <img class='inline mesmer'> [Mesmers] running <img class='inline curtain'> [Temporal Curtain] and <img class='inline feedback'> [Feedback].
- <img class='inline chrono'> [Chronomancer] can take advantage of the [interaction](#continuum-split-and-swords) between <img class='inline cs'> [Continuum Split] and <img class='inline ca-swords'> [Conjured Slash] to massively boost group DPS.

#### Sorting and Appraisal
{: .no_toc}
- Bring as many <img class='inline pull'> [Pull] skills as possible if you are doing [Minipets]. [Ooze] and the [Dreg Shark](#dreg-shark) do not require any special utility.

#### Twin Largos
{: .no_toc}
- It's convenient to bring two healers as you will need one per subgroup when splitting up.
- The subgroup going to [Nikare] should bring a form of <img class='inline stunbreak'> [Stunbreak](https://wiki.guildwars2.com/wiki/Stun_break) for players caught in bubbles.
- The subgroup going to [Kenut] should bring <img class='inline aegis'> [Aegis] for her boonstrips and <img class='inline stability'> [Stability] for her shockwave.
- <img class='inline amalgam'> [Amalgam]'s <img class=inline src='https://wiki.guildwars2.com/images/thumb/2/29/Offensive_Protocol-_Obliterate.png/50px-Offensive_Protocol-_Obliterate.png'> [Offensive Protocol: Obliterate](https://wiki.guildwars2.com/wiki/Offensive_Protocol:_Obliterate) can remove [Barrier] from the bosses, greatly benefiting any <img class='inline condition'> Condition builds.


#### Qadim
{: .no_toc}
- Any <img class='inline mesmer'> [Mesmers] are best run as heal or boon supports due to <img class=inline src='https://wiki.guildwars2.com/images/thumb/f/f6/Confounding_Suggestions.png/38px-Confounding_Suggestions.png'> [Vicious Expression](https://wiki.guildwars2.com/wiki/Vicious_Expression) not applying its damage bonus.
- <img class='inline deadeye'> [Deadeye] is hands-down the best kiter, due to its ease in kiting, survivability and general utility.
- <img class='inline scrapper'> [Scrapper] and <img class='inline reaper'> [Reaper] are a common combination for quickly and safely clearing the lamp. Other viable classes include <img class='inline mirage'> [Mirage] and <img class='inline daredevil'> [Daredevil].
- <img class='inline spellbreaker'> [Spellbreaker] enables ignoring the <img class='inline stability'> [Stability] pyre when running <img class=inline src='https://wiki.guildwars2.com/images/thumb/e/e1/Winds_of_Disenchantment.png/50px-Winds_of_Disenchantment.png'> [Winds of Disenchantment](https://wiki.guildwars2.com/wiki/Winds_of_Disenchantment).
- Bring sources of <img class='inline aegis'> [Aegis]: <img class='inline troubadour'> [Troubadour] and <img class='inline guardian'> [Guardian] are excellent picks due to <img class='inline rogue'> [Tale of the Honorable Rogue] and <img class='inline advance'> ["Advance!"] respectively.

---

## Conjured Amalgamate

This boss is played with a strategy optimized around <img class='inline ca-swords'> [Conjured Greatswords] and  <img class='inline sword-power'> [Greatsword Power]. The strategy has some randomness involved, but is not very punishing overall as it's the first boss in the wing.

---

### Continuum Split and Swords

<img class='inline ca-swords'> [Conjured Slash] has some unexpected behaviour that allows players to double-cast it in quick sequence. The way this skill normally works is:
1. Player gather stacks of <img class='inline sword-power'> [Greatsword Power] from adds or orbs.
2. Players cast the skill, resulting in a number of <img class='inline fractured'> [Fractured] stacks on the affected enemies equal to the amount of <img class='inline sword-power'> [Greatsword Power] gathered.
3. The skill goes on cooldown after its animation lasting 0.75 seconds.
4. <img class='inline sword-power'> [Greatsword Power] is removed from the caster around a second after the skill is cast.



<div class="row-container" style="margin-top: 15px">
<div class='adapt-width-50' markdown=block>
Using <img class='inline cs'> [Continuum Split], we can double cast this skill by resetting its cooldown before <img class='inline sword-power'> [Greatsword Power] is removed.

The resulting sequence is:
1. Cast <img class='inline ca-swords'> [Conjured Slash] and <img class='inline cs'> [Continuum Split].
2. Once <img class='inline ca-swords'> [Conjured Slash] goes on cooldown, <img class='inline cs-exit'> [Continuum Shift].
3. Re-cast <img class='inline ca-swords'> [Conjured Slash] immediately.

If done correctly, this will double the number of <img class='inline fractured'> [Fractured] stacks on all enemies hit.

</div>
<div class='center adapt-width' style="margin-top: 15px">
<video class="bordered center" width='100%' controls>
  <source src="ca/cs_swords.mp4" type="video/mp4">
</video>
</div>
</div>

The timing can be quite tricky to perform correctly in the middle of a run, as you need to activate <img class='inline cs-exit'> [Continuum Shift] late enough that <img class='inline ca-swords'> [Conjured Slash] goes on cooldown, yet early enough to have time to recast the skill before <img class='inline sword-power'> [Greatsword Power] is removed.

{: .note}
This can be practiced easily in a solo instance by killing a [Conjured Greatsword] from the first smash and using it on the second one.

{: .note}
With <img class='inline quickness'> [Quickness], this trick becomes much more difficult to perform. This is due to <img class='inline ca-swords'> [Conjured Slash]'s cast time becoming similar to the time it takes for <img class='inline sword-power'> [Greatsword Power] to be stripped.

---

### Strategy

This strategy requires three roles overall:
- A healer to collect <img class='inline ca-shields'> shields.
- Another healer (usually a <img class='inline chrono'> [Chronomancer]) to collect <img class='inline ca-swords'> swords.
- A secondary sword collector.

#### 100% - 50%
{: .no_toc}

Trigger the left arm and start damaging it. Use <img class='inline curtain'> [Temporal Curtain] and other <img class='inline pull'> [Pull] skills to group up the [Conjured Greatswords] and cleave them on top of the arm. Everyone should collect the swords on the floor as soon as the adds die.

Damage on this arm is important but not fundamental. DPS players should keep their main burst for the second arm, but still try to leave this one around 50-60%.

Once the left arm goes up, cross the middle of the platform to bait down the right arm. Everyone should <img class='inline ca-swords'> [Conjured Slash] the arm and burst it down before it goes up again.

{: .note}
Depending on your burst, you need 5 to 6 stacks of <img class='inline fractured'> [Fractured] on the arm to kill it. Since the pattern of [Conjured Greatswords] spawning from the previous arm is random, it can happen that you do not kill enough swords to do this. In this case it's best to `/gg` and reset the boss than continue a botched run.

Once the arm is dead, the main group should group up and kill the remaining [Conjured Greatswords] while moving to the boss. As soon as they die, use <img class='inline ca-swords'> [Conjured Slash] on the boss.

Meanwhile, the two healers should move in position to collect swords and shields. The swords collector can use <img class='inline ca-swords'> [Conjured Slash] on the boss after collecting five swords. If they are playing <img class='inline chrono'> [Chronomancer], they can additionally [use <img class='inline cs'> Continuum Split](#continuum-split-and-swords) to get ten stacks of <img class='inline fractured'> [Fractured] on it for the main burst.

{: .note}
CS-ing swords is not strictly necessary for the strategy to succeed, but it will greatly increase your overall damage.

While the primary swords collector is using <img class='inline ca-swords'> [Conjured Slash], the secondary swords collector should gather the next three stacks, after which the primary can take over again and gather the rest.

{: .note}
When beginning the collection, the primary collector should count out loud the number of stacks they have. This way, the DPS players can time their burst and the secondary collector knows when to take over.

You should ideally phase the boss before the wall attack reaches the main group. Otherwise, use <img class='inline ca-shields'> [Conjured Protection] to save the group.

---

#### 50% - 25%
{: .no_toc}

The secondary collector should use their <img class='inline ca-swords'> [Conjured Slash] on the left arm when it comes down. This arm should be damaged from the previous phase, so 3-4 swords are usually enough to kill it.

Once it dies, the primary uses their swords remaining from the previous phase on the boss, and both healers move to collect. Ideally you should phase the boss during the collection once they have gathered 2-3 stacks.

Once the boss has phased, CC and kill any [Conjured Shields] remaining. Group up for the clap and use <img class='inline ca-shields'> [Conjured Protection], healing the group immediately afterwards.

---

#### 25% - 0%
{: .no_toc}

The primary, having collected swords in the previous phase, will use <img class='inline ca-swords'> [Conjured Slash] on whichever arm comes down first. Burst the arm down, <img class='inline pull'> [Pulling] together the [Conjured Greatswords] immediately when they spawn and cleaving them.

One player (usually the shields collector) should move before the rest of the group to bait the other arm down on the closer platform. The rest of the group can move once the first arm is dead, and everyone who collected a sword should use <img class='inline ca-swords'> [Conjured Slash] on the arm. Cleave down the arm trying to hit the boss at the same time, while the healers perform the final collection.

{: .warning}
If no players are present on one of the second arm's platforms before killing the first one, the arm will randomly choose which platform to slam down on. This could be the further of the two, resulting in the players not reaching it in time for a full burst.

If the boss is still alive after the second arm dies, then and only then should you hit it directly.

{: .note}
Remember that each time one of the arms dies, the boss loses 10% of its maximum HP!

---

## Sorting and Appraisal

These events can be either very fast or potentially run-ending based on the week. Most groups will attempt to kill on an Ooze week, but it's definitely possible to kill on Minipets with good RNG.

---

### Initial Dialogue Skip

After [Conjured Amalgamate] is dead, everyone should glide backwards off the platform and <img class='inline skyscale'> [Skyscale] back to the ley rift at the beginning of the instance. Use the ley rift to get to Sorting and Appraisal, then talk to [Zomorros], selecting the final option to skip the rest of the dialogue. Afterwards, your path will diverge based on whether you have to complete [Minipets] or [Ooze].

---

### Minipets

This encounter can be made much faster by using <img class='inline pull'> [Pulls] to quickly reposition the minipets. The only way this can go wrong is if you get the [Mega Maraca Choya Pinata](https://wiki.guildwars2.com/wiki/Mega_Maraca_Choya_Pinata), which cannot be moved around. In this case, cry and scream at the unfairness of it all.

Good skills for this encounter include:
- <img class='inline thief'> [Thief]: <img class=inline src='https://wiki.guildwars2.com/images/thumb/c/c8/Scorpion_Wire.png/72px-Scorpion_Wire.png'> [Scorpion Wire](https://wiki.guildwars2.com/wiki/Scorpion_Wire) and <img class=inline src='https://wiki.guildwars2.com/images/thumb/e/e7/Throw_Magnetic_Bomb.png/72px-Throw_Magnetic_Bomb.png'> [Throw Magnetic Bomb](https://wiki.guildwars2.com/wiki/Throw_Magnetic_Bomb), which can be stolen from all four mini-bosses.
- <img class='inline necromancer'> [Necromancer]: <img class='inline' src='https://wiki.guildwars2.com/images/thumb/3/35/Spectral_Grasp.png/50px-Spectral_Grasp.png'> [Spectral Grasp](https://wiki.guildwars2.com/wiki/Spectral_Grasp) and <img class=inline src='https://wiki.guildwars2.com/images/thumb/0/0c/Grasping_Darkness.png/50px-Grasping_Darkness.png'> [Grasping Darkness](https://wiki.guildwars2.com/wiki/Grasping_Darkness).
- <img class='inline mesmer'> [Mesmer]: <img class='inline curtain'> [Temporal Curtain].
- <img class='inline guardian'> [Guardian]: <img class='inline binding-blade'> [Binding Blade](https://wiki.guildwars2.com/wiki/Binding_Blade) and <img class=inline src='https://wiki.guildwars2.com/images/thumb/f/f1/Spear_of_Justice.png/50px-Spear_of_Justice.png'> [Spear of Justice](https://wiki.guildwars2.com/wiki/Spear_of_Justice).
- <img class='inline engineer'> [Engineer]: <img class=inline src='https://wiki.guildwars2.com/images/thumb/8/8c/Magnet.png/72px-Magnet.png'> [Magnet](https://wiki.guildwars2.com/wiki/Magnet) in <img class='inline' src='https://wiki.guildwars2.com/images/thumb/2/2a/Tool_Kit.png/41px-Tool_Kit.png'> [Tool Kit](https://wiki.guildwars2.com/wiki/Tool_Kit).

Announce when you are using a pull skill. *DO NOT* hit any bosses while they're being pulled, as this will interrupt their movement. Sheathe your weapon or de-target to avoid accidental auto-attacks.

---

### Ooze

A straightforward fight. Hit the [Ectoplasmic Conglomeration](https://wiki.guildwars2.com/wiki/Ectoplasmic_Conglomeration) in the center, then hit whatever add is bouncing, going clockwise.

If you're still reading this after that exciting summary, you can use <img class='inline jackal'> [Jackal](https://wiki.guildwars2.com/wiki/Jackal)'s <img class='inline' src='https://wiki.guildwars2.com/images/thumb/9/97/Pounce_%28Jackal%29.png/50px-Pounce_%28Jackal%29.png'> [Pounce](https://wiki.guildwars2.com/wiki/Pounce_(Jackal)) to give [Barrier] at the beginning of the fight and avoid embarrassing downstates.

---

### Dreg Shark

The trick to completing this encounter quickly is to kill the miniboss in one long, continuous phase. This can be done by throwing a second [Dreg Shark Extractor](https://wiki.guildwars2.com/wiki/Dreg_Shark_Extractor) at the shark while it's still vulnerable in the center of the arena. For maximum results, count 8 seconds before throwing the second bomb.

---

## Twin Largos

This boss is played with the standard PUG strat, splitting the squad between [Nikare] and [Kenut] after phasing both to 50%.

Both <img class='inline power'> Power and <img class='inline condition'> Condition builds are viable, with power being better on the first two platforms with their shorter phases, and condition improving on the final two and on [Nikare] due to his movement.

Ideally you should try to kill both bosses at the same time. The subgroup on [Nikare] will often deal less damage overall due to the boss's movement, so it's convenient to have a player from the other subgroup join them on the last platform. This transfer can happen as early as when the [Nikare] group reaches the platform, or as late as after the <img class='inline defiance'> [Defiance Bar], depending on the disparity between the two groups' damage.

---

### Starting Early

It is possible to start the boss earlier than normal in a couple of ways. These usually require players to */gg*, so they are not applicable to infallible runs.
- Once the bosses spawn on the platform, you can hit them with a <img class='inline skyscale'> [Skyscale] <img class=inline src='https://wiki.guildwars2.com/images/thumb/b/b7/Fireball_Skyscale.png/72px-Fireball_Skyscale.png'> [Fireball](https://wiki.guildwars2.com/wiki/Fireball_(skyscale))while the dialogue is still ongoing. This will begin the fight early: you should then */gg* and respawn. You can jump on the platform as soon as you see "Engage Qadim's final challenge" pop up.
- You can "platform start" the boss. Trigger the fight, then */gg*. The boss will not respawn immediately, giving you a 15-20 seconds to preposition on the first platform before spawning in.
- The length of the dialogue depends on the players' client language. The dialogue will last as long as the longest duration between all languages used by players in the instance.

| Language | Duration |
|---|---|
|French| 54 seconds|
|English| 1 minute 2 seconds|
|German| 1 minute 16 seconds|

---

## Transition to Qadim

This transition takes advantage of the dialogue occurring immediately after [Twin Largos] to quickly kill the three [Pyre Guardians] necessary to unlock [Qadim]'s arena.

{: .warning}
This transition cannot be emulated by opening a fresh wing on Qadim, as this dialogue will not be present. It only works after killing [Twin Largos].

{: .note}
It is recommended to run a [marker pack] to show trails for this transition.

After [Twin Largos] die, use your <img class='inline skyscale'> [Skyscale] or <img class='inline skimmer'> [Skimmer] to go back to the ley rift at the entrance of the water room. Change templates while flying so that you are ready for the transition.

Once you are somewhat grouped up, take the ley rift to the Grand Causeway. From when the first person comes through, you will have a limited amount of time to kill the first [Pyre Guardian], found at the bottom of the stairway. If done fast enough, the guardian should respawn shortly after the dialogue between [Qadim] and [Zomorros] ends.

The easiest way to get to the Pyre quickly is with <img class='inline skimmer'> [Skimmer]'s <img class='inline slipstream'> [Slipstream Boost]. If your group is struggling with this DPS check, try waiting for everyone to be ready before taking the ley rift together.

While the main group is killing the first pyre, a <img class='inline mesmer'> [Mesmer] can use a combination of <img class='inline skimmer'> [Skimmer] and <img class='inline skyscale'> [Skyscale] abilities to quickly get to the top of the stairway. They can then prepare a <img class='inline portal'> [Portal Entre] next to one of the topmost [Pyre Guardians] and drop down to join the rest of the group.

{: .note}
It is highly recommended that this player has the relevant mount masteries maxed out.

Based on how fast you killed the first pyre, you can then either: 

- (Fast) Take the <img class='inline portal'> portal, kill the topmost pyre and then take it back down to kill the first one again once it re-spawns.
- (Safe) Wait for the bottom pyre to respawn, kill it and then take the <img class='inline portal'> portal up to kill the last one.

In both cases, the second <img class='inline mesmer'> [Mesmer] (or the first one running <img class='inline mimic'> [Mimic]) should open a portal from the pyre to the entrance of [Qadim]'s arena.

---

## Qadim

Qadim is a long, complicated boss with many moving parts and opportunities for mistakes. Optimized Qadim runs focus mainly on two points:
- Fast lamp clears.
- Killing a single [Pyre Guardian].

---

### Lamp Strategy

In a speedrun setting, the lamp clear becomes the bottleneck for the add phases. Therefore, fast lamps are extremely important in order to get a faster overall kill.

The first and second lamp are often done by either a <img class='inline reaper'> [Reaper] solo, or by a <img class='inline reaper'> [Reaper] and <img class='inline scrapper'> [Scrapper] duo.
- <img class='inline reaper'> [Reaper] has more than enough damage to quickly kill all of the adds, and great survivability and self-boons to boot.
- <img class='inline scrapper'> [Scrapper] is used to speed the <img class='inline reaper'> [Reaper] via <img class='inline gyro-accel'> [Gyroscopic Acceleration](https://wiki.guildwars2.com/wiki/Gyroscopic_Acceleration), often running an additional gyro to maintain <img class='inline superspeed'> [Superspeed] uptime.

Other common lamp classes include:
- <img class='inline power'> <img class='inline mirage'> [Mirage] - technically the fastest solo lamp class, but not often seen due to a high skill floor and sub-optimal phase DPS.
- <img class='inline daredevil'> [Daredevil] - very good mobility, but can struggle to solo in CM due to lower damage and no self boons. Often run as a pair for extremely fast clears. Uniquely, can open its own lamp with <img class=inline src='https://wiki.guildwars2.com/images/thumb/b/b8/Prepare_Pitfall.png/72px-Prepare_Pitfall.png'> [Prepare Pitfall](https://wiki.guildwars2.com/wiki/Prepare_Pitfall).

The last lamp is best done by at least three players, one of which should be able to provide <img class='inline aegis'> [Stability] or <img class='inline resistance'> [Resistance] for the Giants. <img class='inline reaper'> [Reaper] can also <img class='inline blind'> [Blind](https://wiki.guildwars2.com/wiki/Blinded) them using <img class='inline well-darkness'> [Well of Darkness](https://wiki.guildwars2.com/wiki/Well_of_Darkness).

---

### Single Pyre Strategy

Most groups speedrunning Qadim will only kill the [Pyre Guardian] providing <img class='inline protection'> [Protection]. This is done with the following sequence at the beginning of the two burn phases:

1. Once the lamp is opened, a <img class='inline mesmer'> [Mesmer] prepares their <img class='inline portal'> [Portal Entre] next to Qadim's spawn position and runs to the <img class='inline protection'> [Protection] pyre.
2. Once the platform spawns in, they move onto it and open their <img class='inline portal'> portal in front of the [Pyre Guardian].
3. One subgroup (usually the one with the kiter) takes the portal, kills the [Pyre Guardian] and takes it back.

The advantages this brings are:
- The entire squad starts DPSing Qadim early, without having to go out and kill pyres at the beginning of the phase.
- Half the squad remains on Qadim even while killing the pyre.

If you have enough DPS to consistently phase Qadim before he gains his <img class='inline defiance'> [Defiance Bar], you can use this strategy with no additional adjustments. Otherwise, it is highly recommended to run a <img class='inline spellbreaker'> [Spellbreaker] with <img class=inline src='https://wiki.guildwars2.com/images/thumb/e/e1/Winds_of_Disenchantment.png/50px-Winds_of_Disenchantment.png'> [Winds of Disenchantment](https://wiki.guildwars2.com/wiki/Winds_of_Disenchantment). They can use this skill to prevent Qadim from re-gaining <img class='inline stability'> [Stability] while his <img class='inline defiance'> [Defiance Bar] is up, allowing the squad to strip and CC him.

---

### Additional Tips

- Put both lamp players in a subgroup where the supports can give them good boons at the start of the encounter. Alternatively, have them stack with a few boon providers on top of the lamp before taking it down.
- <img class='inline troubadour'> [Troubadour]'s <img class='inline august-queen'> [Tale of the August Queen](https://wiki.guildwars2.com/wiki/Tale_of_the_August_Queen) is excellent for when <img class='inline aegis'> [Aegis] would otherwise be unreliable, such as at the beginning of the Apocalypse phase when you're getting hit by the reapers.
- The safest approach to the bouncing orbs is moving to the unaffected spots on the platform.
- Have a second <img class='inline portal'> [Portal Entre] (or use <img class='inline mimic'> [Mimic]) for when Qadim teleports during the final burst phase.
- Your kiter can be a boon provider if you put them in a subgroup with the lamp players and the tank. Make sure the single remaining DPS does not suffer excessively due to the missing boon (example: <img class='inline quickness'> [Quickness](https://wiki.guildwars2.com/wiki/Quickness) kite <img class='inline deadeye'> [Deadeye] with a DPS <img class='inline bladesworn'> [Bladesworn](https://wiki.guildwars2.com/wiki/Bladesworn)).
- Qadim can be solo-healed by your main tank as long as your off-tank is comfortable with their role.

---

## Additional Resources

#### PoVs

{: .note}
This is a non-comprehensive list meant to display a diverse selection of perspectives and roles. You can find additional PoVs and logs in the [Infallible Archive](https://docs.google.com/spreadsheets/d/1tzWg6KYGTGpCYCy4qBt0X9t7H2RzEM7MRKooh_gXCno).

| Classes | Link | Date | Notes |
| <img class='inline troubadour'> Heal | <img class='inline youtube'> [PoV](https://youtu.be/CvuIh262cAU) | March 2026 | Fast Qadim transition |
| <img class='inline reaper'> DPS, Lamp | <img class='inline youtube'> [PoV](https://youtu.be/ty_aDadUSBc) | May 2026 | Solo lamp |
| <img class='inline deadeye'> QuickDPS, Kiter | <img class='inline youtube'> [PoV](https://youtu.be/TrI35vb5DnA) | March 2026 | F1 F2 F1 F2 F1 F2 |
| <img class='inline virtuoso'> <img class='inline mirage'> DPS, Lamp | <img class='inline youtube'> [PoV](https://youtu.be/0ZC8zsOlRYY) | April 2026 | Transition portal PoV |

#### Other Useful Links

- <img class='inline build'> <img class='inline deadeye'> [Kite Deadeye](https://snowcrows.com/builds/raids/thief/kite-deadeye-q-spear-dagger-dagger) build and [gameplay guide](https://snowcrows.com/guides/builds/kite-deadeye-gameplay-guide) by Snowcrows. Replace <img class=inline src='https://wiki.guildwars2.com/images/thumb/e/e4/Dagger_Training.png/60px-Dagger_Training.png'> [Dagger Training](https://wiki.guildwars2.com/wiki/Dagger_Training) with <img class=inline src='https://wiki.guildwars2.com/images/thumb/2/28/Mug.png/60px-Mug.png'> [Mug](https://wiki.guildwars2.com/wiki/Mug) for easier kiting and sustain. Run rifle instead of daggers if you don't want to teleport every time you use <img class='inline' src='https://wiki.guildwars2.com/images/thumb/7/78/Deadeye%27s_Mark.png/72px-Deadeye%27s_Mark.png'> [Deadeye's Mark](https://wiki.guildwars2.com/wiki/Deadeye's_Mark).

[< Wing 5](../wing-5/){: .btn } [Return to Home](../index.html){: .btn } [Wing 7 >](../wing-7/){: .btn } [Return to Top](#mythwright-gambit){: .btn .fixed}
{: .center}

<!-- Links to other pages in the guide -->
[Conjured Amalgamate]: #conjured-amalgamate-1
[Sorting and Appraisal]: #sorting-and-appraisal-1
[Minipets]: #minipets
[Ooze]: #ooze
[Twin Largos]: #twin-largos-1
[Qadim]: #qadim-1
[marker pack]: ../general.html#marker-packs

<!-- Links to classes and specializations -->
[Mesmer]: https://wiki.guildwars2.com/wiki/Mesmer
[Mesmers]: https://wiki.guildwars2.com/wiki/Mesmer
[Deadeye]: https://snowcrows.com/builds/raids/thief/kite-deadeye-q-spear-dagger-dagger
[Scrapper]: https://wiki.guildwars2.com/wiki/Scrapper
[Engineer]: https://wiki.guildwars2.com/wiki/Engineer
[Reaper]: https://wiki.guildwars2.com/wiki/Reaper
[Warrior]: https://wiki.guildwars2.com/wiki/Warrior
[Spellbreaker]: https://wiki.guildwars2.com/wiki/Spellbreaker
[Troubadour]: https://wiki.guildwars2.com/wiki/Troubadour
[Guardian]: https://wiki.guildwars2.com/wiki/Guardian
[Chronomancer]: https://wiki.guildwars2.com/wiki/Chronomancer
[Thief]: https://wiki.guildwars2.com/wiki/Thief
[Necromancer]: https://wiki.guildwars2.com/wiki/Necromancer
[Amalgam]: https://wiki.guildwars2.com/wiki/Amalgam
[Mirage]: https://wiki.guildwars2.com/wiki/Mirage
[Daredevil]: https://wiki.guildwars2.com/wiki/Daredevil

<!-- Links to skills -->
["Advance!"]: https://wiki.guildwars2.com/wiki/%22Advance!%22
[Tale of the Honorable Rogue]: https://wiki.guildwars2.com/wiki/Tale_of_the_Honorable_Rogue
[Temporal Curtain]: https://wiki.guildwars2.com/wiki/Temporal_Curtain
[Continuum Split]: https://wiki.guildwars2.com/wiki/Continuum_Split
[Continuum Shift]: https://wiki.guildwars2.com/wiki/Continuum_Shift
[Conjured Slash]: https://wiki.guildwars2.com/wiki/Conjured_Slash
[Conjured Protection]: https://wiki.guildwars2.com/wiki/Conjured_Protection
[Feedback]: https://wiki.guildwars2.com/wiki/Feedback
[Slipstream Boost]: https://wiki.guildwars2.com/wiki/Slipstream_Boost
[Portal Entre]: https://wiki.guildwars2.com/wiki/Portal_Entre
[Mimic]: https://wiki.guildwars2.com/wiki/Mimic

<!-- Links to buffs and debuffs -->
[Greatsword Power]: https://wiki.guildwars2.com/wiki/Greatsword_Power_(effect)
[Fractured]: https://wiki.guildwars2.com/wiki/Fractured_(effect)
[Pull]: https://wiki.guildwars2.com/wiki/Pull
[Pulls]: https://wiki.guildwars2.com/wiki/Pull
[Pulling]: https://wiki.guildwars2.com/wiki/Pull
[Barrier]: https://wiki.guildwars2.com/wiki/Barrier
[Aegis]: https://wiki.guildwars2.com/wiki/Aegis
[Superspeed]: https://wiki.guildwars2.com/wiki/Superspeed
[Stability]: https://wiki.guildwars2.com/wiki/Stability
[Resistance]: https://wiki.guildwars2.com/wiki/Resistance
[Protection]: https://wiki.guildwars2.com/wiki/Protection
[Quickness]: https://wiki.guildwars2.com/wiki/Protection

<!-- Links to enemies and enemy skills -->
[Pyre Guardian]: https://wiki.guildwars2.com/wiki/Pyre_Guardian
[Pyre Guardians]: https://wiki.guildwars2.com/wiki/Pyre_Guardian
[Conjured Greatsword]: https://wiki.guildwars2.com/wiki/Conjured_Greatsword
[Conjured Greatswords]: https://wiki.guildwars2.com/wiki/Conjured_Greatsword
[Conjured Shields]: https://wiki.guildwars2.com/wiki/Conjured_Shield
[Nikare]: https://wiki.guildwars2.com/wiki/Nikare
[Kenut]: https://wiki.guildwars2.com/wiki/Kenut

<!-- Other -->
[Skyscale]: https://wiki.guildwars2.com/wiki/Skyscale
[Skimmer]: https://wiki.guildwars2.com/wiki/Skimmer
[Zomorros]: https://wiki.guildwars2.com/wiki/Zommoros
[Defiance Bar]: https://wiki.guildwars2.com/wiki/Defiance_bar