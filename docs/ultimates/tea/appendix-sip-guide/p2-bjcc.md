---
title: Sip P2. Brute Justice and Cruise Chaser
layout: default
grand_parent: The Epic of Alexander
parent: Appendix - Sippy Edition
nav_order: 3
---

<!-- prettier-ignore-start -->

{: .highlight-title }
> Pinned
>
> Aether PUG TEA Pastebin Strats: [Oldbin](https://pastebin.com/Xqa1zsPy)
>
> Tank Cooldown Usage: [Google Doc](https://docs.google.com/spreadsheets/d/1zB5NpvIR0J5uAybtYkqAn_gglnmYcSCo0b0mgSZagUg)
<!-- prettier-ignore-end -->

# P2. Brute Justice and Cruise Chaser

P2 Toolbox: [Link](https://ff14.toolboxgaming.space/?id=340414049443951&preview=1)

## 2m Buff Windows

- #2: At the start.
- #3: Off cooldown, during Gavel cast.

## Pot Windows

None.

## Invulns

No invulns are used here.

## Healing 🩹

Tanks will be taking high amounts of damage, from auto attacks and from mechanics. Both healers should cooperate with each other to keep tanks (and the party) alive. GCD healing is very necessary here.

## Nisi Basics

{: .important }

> A Nisi is a debuff with a very minor DoT.

- It can be passed by touching another player.
- There are four kinds of debuffs based on the color or letter.
- It lasts for 35 seconds.
- When you pass a Nisi to another player, the receiving player receives the full duration of the Nisi.

| Final Decree Alpha |Final Decree Beta | Final Decree Delta | Final Decree Gamma |
| ![FinalDecreeAlpha](/assets/images/tea/FinalDecreeAlpha.png) | ![FinalDecreeBeta](/assets/images/tea/FinalDecreeBeta.png) | ![FinalDecreeDelta](/assets/images/tea/FinalDecreeDelta.png) | ![FinalDecreeGamma](/assets/images/tea/FinalDecreeGamma.png) |

![sip-p2-01](/assets/images/tea/sip-p2-01.png)

{: .warning }

> If you pass a Nisi to another player who has a different Nisi color, both players will **die**.
>
> Movement and passing is very strict in this phase, as an incorrect pass will lead to a wipe.

## Verdict / Gavel

Verdict is cast by Brute Justice, which places an additional debuff on each player.

These debuffs are **Final Judgment: Decree Nisi** debuffs:

| Final Judgement Decree Alpha |Final Judgement Decree Beta | Final Judgement Decree Delta | Final Judgement Decree Gamma |
| ![FinalJudgementDecreeAlpha](/assets/images/tea/FinalJudgementDecreeAlpha.png) | ![FinalJudgementDecreeBeta](/assets/images/tea/FinalJudgementDecreeBeta.png) | ![FinalJudgementDecreeDelta](/assets/images/tea/FinalJudgementDecreeDelta.png) | ![FinalJudgementDecreeGamma](/assets/images/tea/FinalJudgementDecreeGamma.png) |

{: .warning }

> This debuff essentially requires a player to have a specific Nisi before the phase ends, or it guarantees a wipe.
>
> ![FinalJudgementDecreeAlpha](/assets/images/tea/FinalJudgementDecreeAlpha.png) means you must have ![FinalDecreeAlpha](/assets/images/tea/FinalDecreeAlpha.png) at the end of the phase
>
> ![FinalJudgementDecreeBeta](/assets/images/tea/FinalJudgementDecreeBeta.png) means you must have ![FinalDecreeBeta](/assets/images/tea/FinalDecreeBeta.png) at the end of the phase
>
> ![FinalJudgementDecreeDelta](/assets/images/tea/FinalJudgementDecreeDelta.png) means you must have ![FinalDecreeDelta](/assets/images/tea/FinalDecreeDelta.png) at the end of the phase
>
> ![FinalJudgementDecreeGamma](/assets/images/tea/FinalJudgementDecreeGamma.png) means you must have ![FinalDecreeGamma](/assets/images/tea/FinalDecreeGamma.png) at the end of the phase

When Brute Justice casts Gavel, all players Nisis are checked. If any of these conditions are met, Brute Justice will wipe the party.

- A player has incorrect Nisi (e.g. needs purple <img src="/assets/images/tea/FinalJudgementDecreeGamma.png" width="20px"> but has blue <img src="/assets/images/tea/FinalDecreeBeta.png" width="20px">)
- A player has no Nisi
- A player is missing a <img src="/assets/images/tea/FinalJudgmentPenalty3.png" width="20px"> Penalty III debuff (from dying after Verdict)
- A player is <img src="/assets/images/tea/Confused.png" width="20px"> Confused (being hit by Cruise Chaser's Propeller Wind)
- A player is dead

## Link-up and Water / Lightning

Throughout this phase, players will have to resolve 💧 Compressed Water and ⚡ Compressed Lightning stack mechanics.

- These debuffs are placed on a random healer and a random DPS respectively.
- The water and lightning stacks will occur at the same time.
- When the stacks occur, the debuff is "passed" to another player in the stack. (If there is no one else in the stack, the party will wipe)

Additionally, the person with the original debuff will get a vuln debuff for that element, which means they can't be in the next stack for that element. For example, the healer who places 1st Water stack cannot be in the 2nd Water stack.

### 💧 Compressed Water

A stack that occurs on the player with the debuff. 3 or more players required, or 2 with heavy mitigation. Starts on a random healer. Spawns a water tornado that must be neutralized (frozen) or removed (fire). Being too close to the water tornado will kill you and nearby people. Move away from it after the stack occurs.

- Stack 1: 🩹 both healers and 🏹 🧙 both ranged (except if one of them has ⚡ lightning).
- Stack 2: 🩹 healer without debuff, 🏹 🧙 both ranged
- Stack 3: 🩹 🏹 🧙 healer/ranged without debuff, 🛡 MT and/or ⚔️ melee

### ⚡ Compressed Lightning

A stack that occurs on the player with the debuff. **ONLY 2 PLAYERS**. More players will do more damage. Starts on a random DPS.

- Stack 1: ⚔️🏹🧙 DPS passes to 🛡 MT
- Stack 2: 🛡 MT passes to healer 🩹 with debuff <img src="/assets/images/tea/WaterResistanceDown.png" width="20px"> (Water 1 healer)
- Stack 3: 🩹 healer passes to 🛡 OT
