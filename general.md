---
title: Guides
layout: page
nav_order: 2
---

# Introduction to Infallible
{: .no_toc}

<details>
<summary><b>Table of Contents</b></summary>
<div markdown=block>
1. TOC
{:toc}

---
</div>
</details>

Infallible is a prestigious achievement that requires clearing all major raid instances within a difficult time limit and without any players entering <img class='inline invuln'> [Downstate]. Completing this achievement requires extreme class and encounter knowledge, optimized compositions and strategies, and the coordination and practice required to string everything together smoothly into a single, perfect run while not permitting a single mistake.

{: .warning}
This guide assumes that players are already familiar with raids. Speedrun strategies are not designed for progression, as they sacrifice reliability and simplicity in favour of faster clear times. Players looking for introductions to raid encounters are advised to look elsewhere: various resources to get started can be found [here](credits.html).

---

## Guide Structure

This page contains some general concepts useful for anyone getting into Infallible. The rest of the guide then consists of separate pages for each individual raid instance. Each page is then structured similarly, containing an overview of the wing, some tips on general composition, followed by a more in-depth analysis on individual encounters and transitions.

---

## Achievement Details

Infallible requires completion of eight separate sub-achievements, each linked to a different instance:

- <img class='inline achievement'> <a class='yellow-text' href='./wing-1/index.html'>Down and Out: Spirit Vale</a>
- <img class='inline achievement'> <a class='yellow-text' href='./wing-2/index.html'>Down and Out: Salvation Pass</a>
- <img class='inline achievement'> <a class='yellow-text' href='./wing-3/index.html'>Down and Out: Stronghold of the Faithful</a>
- <img class='inline achievement'> <a class='yellow-text' href='./wing-4/index.html'>Down and Out: Bastion of the Penitent</a>
- <img class='inline achievement'> <a class='yellow-text' href='./wing-5/index.html'>Down and Out: Hall of Chains</a>
- <img class='inline achievement'> <a class='yellow-text' href='./wing-6/index.html'>Down and Out: Mythwright Gambit</a>
- <img class='inline achievement'> <a class='yellow-text' href='./wing-7/index.html'>Down and Out: The Key of Ahdashim</a>
- <img class='inline achievement'> <a class='yellow-text' href='./wing-8/index.html'>Down and Out: Mount Balrior</a>

Each sub-achievement corresponds to its own unique effect. Players will gain this effect at the beginning of each raid instance; killing all bosses in the instance while under this effect will grant the achievement. If any player goes <img class='inline invuln'> [Downstate], everyone in the instance will lose this effect, thus invalidating the run.

{: .warning}
Players who leave the instance will also lose the effect: this limits character swapping, as every player who wishes to gain the achievement will have to remain in the instance continuously from beginning to end.

---

## General Concepts

In this section you will find some generally useful information on Infallible, along with concepts that commonly occur in speedrunning, which are described for reference's sake.

---

### Marker Packs

Marker packs are add-ons that display custom trails, markers and other information visually in-game. They are commonly viewed using [Blish HUD](https://blishhud.com)'s [Pathing Module](https://blishhud.com/modules/?module=bh.community.pathing) or [TaimiHUD](https://taimihud.com/).

<img class='center bordered' width='90%' src='https://pkgs.blishhud.com/metadata/img/profile/197954576-74d723ac-c29f-491c-a0f5-4a39c45b9f96.png'>

Several marker packs contain useful information for the purposes of this guide:

- [HasKha's Markers](https://github.com/HasKha/gw2-markers) contains general raid markers, including for other difficult content such as [Temple of Febe](https://silverhalf.github.io/temple-of-febe) and [Mount Balrior](https://silverhalf.github.io/mount-balrior).
- [PEAK Infallible Markers](https://github.com/AersiaNightingale/PEAK-Infallible-Markers) contains information on skips, jumping puzzles and skips for infallible.

It is *highly recommended* to use one or both of these packs. They enable clear callouts and easily display information that would be otherwise difficult to communicate.

{: .note}
This guide will assume that you have installed PEAK's markers and reference them accordingly.

---

### Solo-Healing

This is the practice of bringing only one healer for an encounter.

Boons and healing abilities are almost always capped to a maximum of five targets, prioritizing players in their source's subgroup. For this reason, in a 10-man group, it's standard practice to bring two healers, with each supporting their own sub.

However, the damage pressure in some encounters is low enough that it is possible to bring only one healer. This is because of the overhealing mechanic, wherein if a player's own subgroup is full health, any additional healing will transfer over to the other subgroup. This is called solo-healing.

Solo-healing is extremely advantageous for speedrunning groups, as it generally results in 10-15% increased damage. Sometimes, if incoming damage is low enough (on bosses such as [Keep Construct](./wing-3/index.html#keep-construct-1)) or affects some part of the squad predominantly (such as on [Xera](./wing-3/index.html#xera-1)), this singular healer can even bring a hybrid celestial build, resulting in even more damage. Sometimes, on especially low-damage fights such as [Mursaat Overseer](./wing-4/index.html#mursaat-overseer-1), it is even possible to run no healers at all.

The disadvantage is the inherent risk of bringing one less healer: misplays are more likely to lead to <img class='inline invuln'> [Downstates], requiring everyone in the squad to pay more attention.

Groups that are solo-healing must additionally pay careful attention to the subgroup without a healer, as it will often have less support. BoonDPS in this sub should be able to cover all boons that a healer normally would. <img class='inline protection'> [Protection] is especially important to mitigate incoming damage. Any classes that can provide passive healing or barrier are also extremely valuable. 

---

### Role Compression

Role compression is an important concept in all Guild Wars 2 instanced content. It consists in trying to concentrate an encounter's overall mechanical responsibilities into the smallest number of players possible.

Mechanics almost always results in a DPS loss for players that have to cover them. By having a healer or other support take care of as many mechanics as possible, the DPS players can run more aggressive setups and focus on dealing damage.

For this reason, groups will also try to concentrate things such as <img class='inline stability'> [Stability] and <img class='inline aegis'> [Aegis], additional [defiance damage], and other encounter-specific utility (such as <img class='inline pull'> [Pulls] and <img class='inline portal'> [Portals]) on supports instead of on DPS.


[Stability]: https://wiki.guildwars2.com/wiki/Stability
[Aegis]: https://wiki.guildwars2.com/wiki/Aegis
[Protection]: https://wiki.guildwars2.com/wiki/Protection
[Downstate]: https://wiki.guildwars2.com/wiki/Downed
[Downstates]: https://wiki.guildwars2.com/wiki/Downed
[Pulls]: https://wiki.guildwars2.com/wiki/Pull
[Portals]: https://wiki.guildwars2.com/wiki/Portal
[Defiance Damage]: https://wiki.guildwars2.com/wiki/Control_effect