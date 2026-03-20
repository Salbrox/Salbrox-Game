# SALBROX — EPISODE 1
## Game Concept Document
### Version 1.0

---

## 1. OVERVIEW

**Title:** Salbrox — Episode 1
**Genre:** First-person shooter
**Engine:** QuakeSpasm (modified)
**Game Logic:** QuakeC
**Target Scope:** 5 maps, single episode
**Tone:** Lynchean strangeness meets sci-fi brutality. Carnage and atmosphere in equal measure.

**Tagline:** *"Some things were buried for a reason."*

**What we want players to say:** *"Holy shit that was crazy, and WEIRD."*

---

## 2. TITLE & LORE

**Salbrox** is the Enochian word for Sulfur.

The name refers to four things simultaneously — the game, the station, the compound, and the entity. The player does not know which one the title refers to until the end. This ambiguity is intentional.

**Enochian** is the language of angels, used to describe creation. Salbrox is something that predates the description. It isn't named by Enochian — Enochian was attempting to name *it*.

---

## 3. PREMISE

**Salbrox Station** is a deep-core industrial mining operation drilling into an anomalous geological formation rich in an unidentified sulfurous compound. The compound isn't simply a mineral. It is a *medium*. Something has been using it to communicate — or to bleed through — for a very long time.

The drilling cracked open a seal that was placed there intentionally.

The station was named *before* the drilling started. Someone knew.

---

## 4. THE ENTITY — SALBROX

Salbrox is not a monster. It is not a god, exactly. It is something that *is* sulfur the way fire *is* heat — it doesn't use it, it doesn't live in it, it simply *is* it. It has been here since before the planet cooled.

- The miners didn't discover it. They gave it a door.
- You never fully see Salbrox. The final encounter destroys the conduit, the seal, the *word* — not the thing itself.
- Enemies aren't possessed or corrupted. They have been *translated* into something closer to what Salbrox actually is.
- Alchemists believed sulfur was one of the three primal substances — the soul of matter. The compound doesn't just burn, it *transforms*.

---

## 5. PLAYER CHARACTER — D-7

The player character has a number, not a name. His designation is clinical and dehumanizing by design.

**D-7 does not know his name.** He finds out who he is as the game progresses — through Tesseract memory fragments, environmental details, and his own voice reactions to what he encounters.

**The twist:** D-7 is not simply a victim. He made a deal with Salbrox. This reframes the entire game on a second playthrough.

### Voice Direction
Understated. Not screaming — a person quietly registering that things are very bad. Controlled fear is more unsettling than panic.

### Exposure Voice Lines

**Low Exposure / Ambient sulfur:**
- *"God, what is that smell."*
- *"It's getting thicker down here."*
- *"Smells like something's burning. Or rotting. Both."*

**Mid Exposure — physical discomfort:**
- *"My eyes are watering. Not good."*
- *"Can't breathe through my nose anymore."*
- *"Head's starting to pound."*

**High Exposure — fear creeping in:**
- *"Something's wrong with me."*
- *"I can see— I don't want to talk about what I can see."*
- *"It's inside me now. Isn't it."*

**Near Salbrox surfaces/enemies:**
- *"Whatever died here, it didn't die clean."*
- *"Don't touch it. Don't touch anything."*

**Memory fragment reactions:**
- *"I know this smell. I've been here before."*
- *"That's— that's my handwriting on the wall."*
- *"Why do I know how to operate this?"*

---

## 6. MOVEMENT

- Slightly slower than Quake (Quake: 320 u/s → Salbrox: 270 u/s)
- More weight and intention — grounded, not sluggish
- Jump height reduced (Quake: 270 → Salbrox: 230)
- Momentum/bunny-hop preserved but feels more deliberate
- No speed penalty for looking — fluidity stays, top speed is reduced

The player is a person descending into something, not a marine on stimulants.

---

## 7. WEAPONS

All weapons support dual wield in any combination. Edge cases caught during testing.

### 7.1 Weapon Roster

| # | Name | Analog | Description |
|---|------|--------|-------------|
| 1 | **Compression Pistol** | Shotgun | Concentrated pressure burst. Tight spread, staggers enemies, satisfying thud. |
| 2 | **Extraction Carbine** | Auto Rifle | Full-auto station crew weapon. Scope = held-breath zoom. Feels human and familiar amid everything wrong. |
| 3 | **Core Drill** | Nailgun | Spinning drill bits that penetrate and lodge in enemies before detonating. |
| 4 | **Thermal Lance** | Rocket Launcher | Slow-moving superheated bolt. Can arc. Accepts homing fuel rods. |
| 5 | **Resonance Fork** | Lightning Gun | Emits a wave that bounces off geometry. Rewards map knowledge. |
| 6 | **The Conduit** | Unique | Channels Sulfur Exposure as a weapon — Salbrox's own nature used against itself. High risk, high reward. |

### 7.2 Ammo Variations

Physical pickups in the world. Slot into the relevant weapon on pickup.

| Weapon | Primary | Alt A | Alt B |
|--------|---------|-------|-------|
| Compression Pistol | Pressure canisters | **Incendiary** — leaves burning patch | **Void** — penetrates, no stagger |
| Core Drill | Drill bits | **Barbed** — lodges deeper, bleed damage | **Charged** — longer fuse, bigger pop |
| Thermal Lance | Fuel rods | **Homing** — locks onto last targeted enemy | **Cluster** — splits into three on impact |
| Extraction Carbine | Rifle rounds | **Armor Piercing** — ignores enemy defense | **Tracer** — every 5th round marks enemy for increased damage |
| Resonance Fork | Resonance cells | **Focused** — no bounce, pure beam | **Overcharged** — wider wave, faster drain |

### 7.3 Dual Wield Notes

All combinations are legal. Some pairings have emergent behavior:

| Pair | Emergent Effect |
|------|----------------|
| Compression Pistol × 2 | Alternating fire, faster stagger |
| Pistol + Core Drill | Off-hand suppression while drill lodges |
| Conduit × 2 | Extremely dangerous. Theoretically possible. |

---

## 8. CORE MECHANIC — SULFUR EXPOSURE

A second meter alongside health, ranging 0.0 to 1.0.

**How it builds:** Passively in sulfur zones. Faster near Salbrox-touched enemies or marked surfaces.
**How it decays:** Slowly when outside sulfur zones.

### Thresholds

| Level | Range | Effects |
|-------|-------|---------|
| **Safe** | 0.0 – 0.33 | Normal play |
| **Low Exposure** | 0.33 – 0.66 | Hidden geometry becomes visible. Enemy weak points glow. World desaturates except sulfur-yellow highlights. |
| **High Exposure** | 0.66 – 1.0 | The Conduit charges. Salbrox can now perceive *you* — enemies more aggressive, behaviors change. |

At high exposure The Conduit is devastating but D-7 is at maximum vulnerability. The mechanic creates a risk/reward loop that is both mechanical and narrative: the more you understand Salbrox, the more it understands you.

---

## 9. THE TESSERACT

A recurring object found in each of the 5 maps. When the player passes through it, they enter an **alternate version of the same map** — same geometry, but wrong.

### Episode 1 Implementation
- Hand-built alternates per map (same BSP, different textures, lighting, entities, ambience)
- Each alternate contains a fixed memory fragment for D-7 (voice line + environmental detail)
- 5 fragments form an incomplete picture — enough to intrigue, not enough to resolve

### The 5 Memory Fragments

| Map | Fragment |
|-----|---------|
| 1 | He recognizes the station. He's been here before. |
| 2 | A name on a door. It's his. He had a different one. |
| 3 | A face. Someone he came here with. |
| 4 | Why he came. It wasn't mining. |
| 5 | What Salbrox offered him. And what he said yes to. |

Fragment 5 reframes the entire game on a second playthrough.

### Future Episodes
- **Ep2:** LLM-generated text fragments, journal entries, variable Enochian translations
- **Ep3:** LLM influences enemy population in alternates — different every run
- **Ep4+:** True procedural variation within pre-authored spaces

---

## 10. ENEMIES

### Tier 1 — The Translated (Human, Maps 1–2)

These were crew. The sulfur didn't possess them — it *rewrote* them. They still move like people. That's what's wrong with them.

| Enemy | Was | Now | Behavior |
|-------|-----|-----|---------|
| **The Shuffler** | Miner | Moves in wrong directions, takes indirect paths. Locks on at proximity — accelerates in stuttery bursts, not smoothly. Slows if you create distance. | Starts slow (disarming), snaps to dangerous speed at close range. Audio has two states: ambient when slow, sharp/wrong when locked. |
| **The Screamer** | Communications officer | Jaw unhinged, emits signal that draws others. | Doesn't attack directly — calls reinforcements, panics nearby enemies. Priority target. |
| **The Graft** | Security | Drilling equipment fused to body. | Mid-range, aggressive. Drill arm functions as both melee and projectile. |
| **The Supervisor** | Station manager | Pristine uniform, blank face, gives orders in Enochian. | Mini-boss tier. Buffs nearby enemies. Encountered 2–3 times total. |

### Tier 2 — The Older Things (Maps 3–5)

Never human. Were here before the station. The drilling woke — or released — them.

| Enemy | Nature | Behavior |
|-------|--------|---------|
| **The Vein Crawler** | Sulfur deposit given locomotion. | Clings to walls and ceilings. Drops onto player. Leaves burning sulfur patches on the ground. |
| **The Hollow** | A shape with nothing inside. | Invisible until it attacks. Leaves a geometric distortion trail. |
| **The Cartographer** | Maps spaces that shouldn't exist. | Triggers pre-placed door/brush entities to rearrange arena geometry mid-fight. Maps are designed around it — every wall a door, every corridor has a sealed twin. Confined to purpose-built arenas (Map 4). |
| **The First Voice** | Salbrox's oldest signal. | Boss-tier. Speaks in Enochian. D-7 understands it. He shouldn't. |

### The Transition Enemy (Map 3)

One enemy that began as human and is halfway through becoming an Older Thing. Still has a nametag. You can read it. Name TBD.

### The Sentinel (All Maps)

A pre-drilling era security drone. Still running patrol loops. Now serving Salbrox.

- Floating, ranged attacker (energy bolts / compressed air)
- Patrols until detection, then engages
- **Hackable:** hold interact on a damaged Sentinel to breach it
  - Full-health Sentinels reject the hack and alert nearby units
  - Hacked Sentinel fights for you temporarily, then self-destructs
  - Self-destruct can be weaponized — walk it into a group
  - Max one hacked Sentinel at a time (tunable)
- **Hardened variant:** cannot be hacked — player must identify type before engaging

---

## 11. EPISODE MAP ARC

### Map 1 — Surface

**Setting:** The drilling platform. Industrial, cold, wrong.

**Intro sequence (Half-Life style):** D-7's transport pod approaches the station. Through the viewport: the station lights are wrong. Something is visible near the station that shouldn't be there. No explanation. Pod docks. Interlock chamber pressurizes. Player takes control the moment the interlock door opens.

First thing they see: a body. Sitting against the wall. No blood. Like it just stopped.

**Layout:** Cramped corridors and grand open spaces in alternation. A loop-back that the player recognizes. The Tesseract appears in the second half — tucked in an unremarkable maintenance alcove with no fanfare.

**Key beats:**
1. Interlock exit → first grand space (atrium/ops floor). First Shuffler — alone, far away, moving wrong.
2. Tight maintenance section. Sentinel patrol. Hack or kill decision.
3. Second grand space — the drill head. Still running. No one operating it. Something coming up from below — heard, not seen.
4. Loop-back corridor — something has changed since the player was last here. They're being tracked.
5. The Tesseract — Memory Fragment 1: *"I know this smell. I've been here before."*
6. A visible room across a gap with a clear item and enemy. Natural instinct to go there. The path toward it triggers the exit.
7. **Exit:** Not a slipgate. The floor gives, a grate drops, something pulls D-7 down. Fast. No warning. Cut to black.

**Note:** The visible room from Map 1's exit is revisited in Map 2 or 3 — the player arrives from the other direction and recognizes it.

**Music:** Cool but not overt. Curious, uneasy. Builds to nothing — the silence is more unsettling than a swell.

**Enemies:** Shufflers, Sentinels, one Screamer.

**Existing asset note:** A pre-existing Quake deathmatch map themed around a Shambler research lab (industrial facility, wrong things inside) may be raided for geometry and layout reference.

---

### Map 2 — The Shaft

**Setting:** The descent. The walls show markings that look carved, not drilled.

---

### Map 3 — The Vein

**Setting:** The sulfur deposit itself. Physics feel wrong. Enemies are wrong.

**Contains:** The Transition Enemy. The Cartographer's arena. Tesseract is closer to mid-map.

---

### Map 4 — The Seal

**Setting:** Something ancient was down here first. This was a door, not a formation.

**Contains:** The Cartographer arena — a room designed entirely around its geometry-shifting behavior.

---

### Map 5 — What's Behind It

**Setting:** The boss map. The player is not in the station anymore.

**Boss:** The First Voice. The encounter destroys the conduit/seal/word. Not the thing itself.

**Memory Fragment 5:** What Salbrox offered D-7. And what he said yes to.

---

## 12. HUD & UI (DIRECTION)

- Exposure meter displayed alongside health — visual language TBD
- Ammo type indicator shows current variant loaded per weapon
- Dual wield shows both weapon slots
- At mid-exposure: world desaturates except sulfur-yellow highlights (engine-level effect, planned for future implementation)

---

## 13. TECHNICAL FOUNDATION

| System | Status |
|--------|--------|
| Movement tuning (speed + jump) | Complete |
| Sulfur Exposure field + thresholds | Complete (skeleton) |
| Exposure passive decay | Complete |
| Exposure voice lines (text) | Complete (audio TBD) |
| Exposure zone triggers | Planned |
| Weapons | Planned |
| Enemies | Planned |
| Tesseract trigger | Planned |
| HUD | Planned |

---

## 14. SCOPE — EPISODE 1

Episode 1 is the proof of concept. If it lands, further episodes expand the systems:

- Ep1: Establish world, mechanics, D-7's arc, the Tesseract as a concept
- Ep2+: LLM-driven Tesseract content, expanded enemy roster, deeper exposure effects

Everything in Episode 1 is designed to be self-contained but to point at something larger.
