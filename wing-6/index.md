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

Mythwright Gambit is a straightforward wing with a liberal timer. The ease of clearing this wing varies based on the week: [Mini-Pets] weeks are much harder to clear than [Ooze], though both are possible. Most time gains revolve around an efficient [Conjured Amalgamate], a good transition from [Twin Largos] to [Qadim], and a fast [Qadim] kill.

---

#### Main Points
{: .no_toc}
- [Conjured Amalgamate] is played with a non-standard strategy that is relatively RNG-heavy.
- [Sorting and Appraisal] can be either trivial on [Ooze] weeks or very difficult to optimize on [Mini-Pets] weeks.
- [Twin Largos] is played with a standard strategy, but has a few minor optimizations.
- [Qadim] strategies vary around the handling of [Pyre Guardians].

---

## Composition

Mythwright Gambit requires many specialized roles so composition requirements can be rather strict.

- Two <img class='inline mesmer'> [Mesmers] are ideal for optimizing the transition from [Twin Largos] to [Qadim]. These are best run as heal or boon supports on [Qadim] due to <img class=inline src='https://wiki.guildwars2.com/images/thumb/f/f6/Confounding_Suggestions.png/38px-Confounding_Suggestions.png'> [Vicious Expression](https://wiki.guildwars2.com/wiki/Vicious_Expression) not applying its damage bonus.
- <img class='inline deadeye'> [Deadeye] is hands-down the best kiter for [Qadim], due to its ease in kiting, survivability and general utility. It can also be run as a quickness kite with some minor adaptations.
- <img class='inline scrapper'> [Scrapper] and <img class='inline reaper'> [Reaper] are the best combination for quickly clearing the lamp on [Qadim]. <img class='inline engineer'> [Engineer] has also some unique utilities that make it appreciated in other encounters of the wing.
- <img class='inline warrior'> [Warrior] is a good DPS pick for the wing overall, and can be flexed to <img class='inline spellbreaker'> [Spellbreaker] on [Qadim] for some strategies.

Remember to bring enough sources of <img class='inline aegis'> [Aegis] for [Qadim]: <img class='inline troubadour'> [Troubadour] and <img class='inline guardian'> [Guardian] are excellent picks due to <img class='inline rogue'> [Tale of the Honorable Rogue] and <img class='inline advance'> ["Advance!"] respectively.

---

## Conjured Amalgamate

This boss is played with a strategy that is optimized around <img class='inline ca-swords'> [Conjured Greatswords] and  <img class='inline sword-power'> [Greatsword Power].

---

### Composition

Usually both <img class='inline mesmer'> [Mesmers] are run as healers on this boss. There is little to no advantage to having them play boonDPS here, as the additional concentration is more beneficial when they are collecting off-stack. Both should be running focus for <img class='inline curtain'> [Temporal Curtain] and <img class='inline feedback'> [Feedback] for the lasers.

Once of the <img class='inline mesmer'> [Mesmers] can be a heal <img class='inline chrono'> [Chronomancer] to take advantage of the [interaction](#continuum-split-and-swords) between <img class='inline cs'> [Continuum Split] and <img class='inline ca-swords'> [Conjured Slash].

---

### Continuum Split and Swords

<img class='inline ca-swords'> [Conjured Slash] has some unexpected behaviour that allows players to double-cast it in quick sequence. The way this skill normally works is:
1. Player gather stacks of <img class='inline sword-power'> [Greatsword Power] from adds or orbs.
2. Players cast the skill, resulting in a number of <img class='inline fractured'> [Fractured] stacks on the affected enemies equal to the amount of <img class='inline sword-power'> [Greatsword Power] gathered.
3. The skill goes on cooldown after its animation lasting 0.75 seconds.
4. <img class='inline sword-power'> [Greatsword Power] is removed from the caster around a second after the skill is cast.



<div class="row-container" style="margin-top: 15px">
<div class='adapt-width-50' markdown=block>
Using <img class='inline cs'> [Continuum Split], we can double cast the skill by resetting the cooldown before <img class='inline sword-power'> [Greatsword Power] is removed.

The sequence of skills used is:
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

---

### Strategy

Designate one healer to collect swords and another to collect shields. The sword collector should be a <img class='inline chrono'> [Chronomancer]. Designate an additional DPS or boonDPS to help with the first sword collection.

#### 100% - 50%
{: .no_toc}

Start by triggering the left arm and start damaging it. Use <img class='inline curtain'> [Temporal Curtain] and other <img class='inline pull'> [Pull] skills to group up the [Conjured Greatswords] and cleave them on top of the arm. Everyone should collect the swords on the floor as soon as the adds die.

{: .note}
Damage on this arm is important but not fundamental. DPS players should keep their main burst for the second arm, but still try to leave this one around 50-60%.

Once the left arm goes up again, cross the middle of the platform to bait down the right arm. Everyone should <img class='inline ca-swords'> [Conjured Slash] the arm and burst it down before it goes up again.

{: .note}
Depending on your burst, you need 5 to 6 stacks of <img class='inline fractured'> [Fractured] on the arm to kill it. Since the pattern of [Conjured Greatswords] spawning from the previous arm is random, it can happen that you do not kill enough swords to do this. In this case it's best to `/gg` and reset the boss than continue a botched run.

Once the arm is dead, the main group should group up and kill the remaining [Conjured Greatswords] while moving to the boss. As soon as they die, use <img class='inline ca-swords'> [Conjured Slash] on the boss.

Meanwhile, the two healers should move in position to collect swords and shields. The <img class='inline chrono'> [Chronomancer], after collecting the first five swords, will [<img class='inline cs'> Continuum Split <img class='inline ca-swords'> Conjured Slash](#continuum-split-and-swords) the boss to get ten stacks of <img class='inline fractured'> [Fractured] on for the main burst.

{: .note}
CS-ing swords is not strictly necessary for the strategy to succeed, but it will greatly increase your overall damage.

While the <img class='inline chrono'> [Chronomancer] is using <img class='inline ca-swords'> [Conjured Slash], the second swords collector should gather the next three stacks, after which the <img class='inline chrono'> [Chronomancer] can take over and gather the rest.

{: .note}
When beginning the collection, the <img class='inline chrono'> [Chronomancer] should count out loud the number of stacks they have. This way, the DPS players can time their burst and the secondary collect knows when to take over.

You should ideally phase the boss before the wall attack reaches the main group. Otherwise, use <img class='inline ca-shields'> [Conjured Protection] to save the group.

---

#### 50% - 25%
{: .no_toc}

The secondary collector should use their <img class='inline ca-swords'> [Conjured Slash] on the left arm when it comes down. This arm should be damaged from the previous phase, so 3-4 swords are usually enough to kill it.

Once it dies, the <img class='inline chrono'> [Chronomancer] uses their swords remaining from the previous phase on the boss, and both healers move to collect. Ideally you should phase the boss during the collection once they have gathered 2-3 stacks.

Once the boss has phased, CC and kill any [Conjured Shields] remaining. Group up for the clap and use <img class='inline ca-shields'> [Conjured Protection], healing the group immediately afterwards.

---

#### 25% - 0%
{: .no_toc}

The <img class='inline chrono'> [Chronomancer], having collected in the previous phase, will use <img class='inline ca-swords'> [Conjured Slash] on whichever arm comes down first. Burst the arm down, <img class='inline pull'> [Pulling] together the [Conjured Greatswords] immediately when they spawn and cleaving them down.

One healer should move before the rest of the group to bait the other arm down on the closer platform. The rest of the group can move once the first arm is dead, and everyone who collected a sword should use <img class='inline ca-swords'> [Conjured Slash] on the arm. Cleave down the arm trying to hit the boss at the same time, while the healers perform the final collection.

{: .warning}
If no players are present on one of the platforms of the second arm before killing the first one, the arm may slam down on the further of the two, resulting in the players not reaching it in time for a full burst.

If the boss is still alive after the second arm dies, then and only then should you hit it directly.

---


[< Wing 5](../wing-5/){: .btn } [Return to Home](../index.html){: .btn } [Wing 7 >](../wing-7/){: .btn } [Return to Top](#mythwright-gambit){: .btn .fixed}
{: .center}

<!-- Links to other pages in the guide -->
[Conjured Amalgamate]: #conjured-amalgamate
[Sorting and Appraisal]: #mythwright-gambit
[Mini-Pets]: #mythwright-gambit
[Ooze]: #mythwright-gambit
[Twin Largos]: #mythwright-gambit
[Qadim]: #mythwright-gambit

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
[Chronomancer]: https://wiki.guildwars2.com/wiki/Guardian

<!-- Links to skills -->
["Advance!"]: https://wiki.guildwars2.com/wiki/%22Advance!%22
[Tale of the Honorable Rogue]: https://wiki.guildwars2.com/wiki/Tale_of_the_Honorable_Rogue
[Temporal Curtain]: https://wiki.guildwars2.com/wiki/Temporal_Curtain
[Continuum Split]: https://wiki.guildwars2.com/wiki/Continuum_Split
[Continuum Shift]: https://wiki.guildwars2.com/wiki/Continuum_Shift
[Conjured Slash]: https://wiki.guildwars2.com/wiki/Conjured_Slash
[Conjured Protection]: https://wiki.guildwars2.com/wiki/Conjured_Protection
[Feedback]: https://wiki.guildwars2.com/wiki/Feedback

<!-- Links to buffs and debuffs -->
[Greatsword Power]: https://wiki.guildwars2.com/wiki/Greatsword_Power_(effect)
[Fractured]: https://wiki.guildwars2.com/wiki/Fractured_(effect)
[Pull]: https://wiki.guildwars2.com/wiki/Pull
[Pulls]: https://wiki.guildwars2.com/wiki/Pull
[Pulling]: https://wiki.guildwars2.com/wiki/Pull

<!-- Links to enemies and enemy skills -->
[Pyre Guardian]: https://wiki.guildwars2.com/wiki/Pyre_Guardian
[Pyre Guardians]: https://wiki.guildwars2.com/wiki/Pyre_Guardian
[Conjured Greatsword]: https://wiki.guildwars2.com/wiki/Conjured_Greatsword
[Conjured Greatswords]: https://wiki.guildwars2.com/wiki/Conjured_Greatsword
[Conjured Shields]: https://wiki.guildwars2.com/wiki/Conjured_Shield

<!-- Other -->