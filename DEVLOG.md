## Devlog: From Neon Rift Runner to Neon Rift 2

Neon Rift Runner started as a constraint-driven experiment:
> *How far can a fast, responsive action game go using only a single HTML file, no assets, and no libraries?*

The first version focused almost entirely on **feel**:
- movement responsiveness
- gravity and jumping
- camera follow and scrolling
- simple enemies and shooting
- immediate playability

It was intentionally small and readable — closer to a playable sketch than a “complete” game.

---

### What v1 taught me

Neon Rift Runner answered some important questions early:
- tight movement matters more than visuals
- camera shake and hit feedback carry a lot of weight
- even simple procedural layouts can feel good if pacing is right
- a single-file constraint forces clarity

But it also exposed limitations:
- combat depth was shallow
- enemies were static challenges, not systems
- there was no sense of progression or mastery
- no reason to replay beyond curiosity

---

### Why Neon Rift 2 exists

Neon Rift 2 was not a rewrite — it was a **direct evolution**.

The goal was to keep the same constraints:
- one file
- no assets
- browser-only

…while designing a game that rewarded **skill, aggression, and learning**.

Key changes in v2:
- layered combat (dash, melee, reflect, ranged)
- real enemy behaviors with counterplay
- checkpoints and fair recovery
- miniboss and boss encounters with patterns
- hybrid level design (handcrafted + procedural)
- more deliberate pacing and difficulty ramp

The codebase also evolved:
- clearer separation of systems
- reusable entity logic
- more intentional state handling
- more attention to polish (particles, timing, audio)

---

### What Neon Rift 2 represents

Neon Rift 2 is the point where the project stopped being a demo and became a **game**.

It’s still deliberately constrained and self-contained, but it reflects:
- iteration instead of restarting
- refinement instead of feature creep
- learning from playtesting, not theory

Both versions are kept because they show different stages of the same idea:
- **v1** shows the foundation
- **v2** shows what happens when that foundation is pushed

---

### What’s next (maybe)

There’s no pressure to go further — but if this evolves again, it would likely explore:
- biome variety
- enemy variants per segment
- replay / speedrun modes
- or extracting a minimal “engine core” while preserving the one-file spirit
