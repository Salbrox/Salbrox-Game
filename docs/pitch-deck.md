# SALBROX — PITCH DECK
### Episode 1

---

## SLIDE 1 — TITLE

# SALBROX
### Episode 1

*"Some things were buried for a reason."*

---

## SLIDE 2 — THE HOOK

**What if Quake was made today — by people who'd seen too much David Lynch?**

A 90s-style FPS with modern design sensibilities.
Fast. Brutal. Deeply, deliberately weird.

> *"Holy shit that was crazy, and WEIRD."*
> — What we want players to say

---

## SLIDE 3 — THE NAME

**Salbrox** — the Enochian word for Sulfur.

Enochian is the language of angels, used to describe creation.
Salbrox is what Enochian was *trying* to name.

The title refers to:
- The game
- The station
- The compound
- The entity

The player doesn't know which one until the end.

---

## SLIDE 4 — THE PREMISE

**Salbrox Station.**
A deep-core mining operation. An anomalous sulfurous formation. An unidentified compound.

The compound isn't a mineral. It's a *medium*.

Something has been using it to communicate for a very long time.

The drilling cracked open a seal placed there intentionally.

**The station was named before the drilling started. Someone knew.**

---

## SLIDE 5 — THE TONE

**Two things at once — always.**

| Carnage | Atmosphere |
|---------|-----------|
| Fast, brutal FPS combat | Spaces that feel fundamentally wrong |
| Satisfying weapons with depth | Silence used as a tool |
| Enemy encounters with real tension | A world that doesn't explain itself |

**Reference points:**
- Quake (1996) — movement, brutality, flow
- Twin Peaks / Inland Empire — wrongness, dread, the mundane made terrifying
- Half-Life — environmental storytelling, scripted moments that feel alive

---

## SLIDE 6 — THE PLAYER CHARACTER

# D-7

He has a number. Not a name. Not yet.

D-7 doesn't know who he is.
He finds out as he descends.

**The twist:** He's not a victim.
He made a deal with Salbrox.

This reframes the entire game on a second playthrough.

*Voice direction: understated. A person quietly registering that things are very bad.*

---

## SLIDE 7 — MOVEMENT

**90s feel. Modern weight.**

- Slightly slower than Quake — more grounded, more intentional
- Jump feels like a decision, not a reflex
- Momentum preserved — bunny-hop stays, but feels deliberate
- You are descending into something. You move like it.

---

## SLIDE 8 — WEAPONS

**6 weapons. All dual-wieldable in any combination.**

| Weapon | Feel |
|--------|------|
| Compression Pistol | Tight pressure burst. Staggers. Satisfying thud. |
| Extraction Carbine | Auto rifle + scope. The last normal thing. |
| Core Drill | Bits lodge in enemies. Then detonate. |
| Thermal Lance | Slow superheated bolt. Homing option. |
| Resonance Fork | Bounces off geometry. Rewards map knowledge. |
| The Conduit | Channels your Exposure against Salbrox. High risk. |

**Plus:** Ammo variants per weapon. Physical pickups. Changes behavior, not just damage.

---

## SLIDE 9 — THE EXPOSURE SYSTEM

**Sulfur Exposure — the game's core mechanic.**

A second meter alongside health. Builds in sulfur zones. Decays outside them.

| Exposure | What Changes |
|----------|-------------|
| Safe | Normal play |
| Low | Hidden geometry visible. Enemy weak points glow. World goes sulfur-yellow. |
| High | The Conduit charges. Salbrox can now perceive *you*. |

**The loop:** The more you understand Salbrox, the more it understands you.

D-7 reacts to exposure with voice lines — not screaming, just quietly registering that something is very wrong.

---

## SLIDE 10 — THE TESSERACT

**A portal in every map. Through it: the same map, wrong.**

Each Tesseract takes D-7 into an alternate version of the level.
Same geometry. Different everything else.

Inside: a memory fragment. A piece of D-7's identity, returning.

**5 fragments across 5 maps:**
1. He's been here before
2. A name on a door — it's his
3. A face — someone he came with
4. Why he came — it wasn't mining
5. What Salbrox offered. What he said yes to.

*Future episodes: LLM-generated content, procedural variation, player experiences never exactly the same twice.*

---

## SLIDE 11 — ENEMIES

**Two tiers. One transition.**

**Tier 1 — The Translated** *(Maps 1–2)*
Human once. Still move like people. That's the problem.
- The Shuffler — slow until it locks on, then wrong
- The Screamer — calls others, never attacks directly
- The Graft — drilling equipment fused to flesh
- The Supervisor — buffs others, speaks Enochian

**Tier 2 — The Older Things** *(Maps 3–5)*
Were here before the station.
- The Vein Crawler — ceiling hunter, leaves burning patches
- The Hollow — invisible until it attacks
- The Cartographer — rewrites the room while you fight in it
- The First Voice — boss. D-7 understands what it says. He shouldn't.

**The Sentinel** — hackable security drone. Fight it or turn it. Weaponize its self-destruct.

---

## SLIDE 12 — THE 5 MAPS

| Map | Name | Setting |
|-----|------|---------|
| 1 | Surface | The drilling platform. Something came up from below. |
| 2 | The Shaft | Descent. The markings look carved, not drilled. |
| 3 | The Vein | The deposit itself. Physics feel wrong. |
| 4 | The Seal | Something ancient was here first. This was a door. |
| 5 | What's Behind It | You're not in the station anymore. |

**Map 1 opens with a scripted intro sequence** — Half-Life style. D-7's pod approaches the station. Something visible near it that shouldn't be there. No explanation. Player takes control when the interlock door opens.

**Map 1 exit** is a surprise — a visible room draws the player toward it, a trigger pulls them away. That room is revisited maps later, from the other direction.

---

## SLIDE 13 — TECHNICAL

**Built on QuakeSpasm + QuakeC.**

The Quake engine is the perfect foundation:
- Proven movement feel as the baseline
- QuakeC is fast to iterate on
- Community tooling is mature (TrenchBroom, FTEQCC)
- The constraints force creative solutions

**Salbrox-specific systems built so far:**
- Movement tuning (speed, jump)
- Sulfur Exposure skeleton (field, thresholds, decay, voice triggers)

**Planned systems:**
- Full weapon implementations
- Enemy AI
- Tesseract trigger + alternate map loading
- Exposure zone triggers
- HUD / UI

---

## SLIDE 14 — EPISODE 1 SCOPE

**5 maps. One complete arc. A world that points at something larger.**

Episode 1 is self-contained:
- D-7's arc has a resolution
- The Salbrox threat has an encounter (not a defeat)
- The Tesseract is introduced and used meaningfully

Episode 1 is also a foundation:
- Every system is designed to scale
- The Tesseract's LLM future is designed in from day one
- The entity is not defeated — it was never containable

---

## SLIDE 15 — VISION

**Quake made something primal.**
**Half-Life made something human.**
**Salbrox makes something that shouldn't exist.**

A game that plays like a memory you're not sure is yours.
Fast enough to feel free.
Strange enough to stay with you.

---

# SALBROX
### *Episode 1*
### github.com/Salbrox/Salbrox-Game
