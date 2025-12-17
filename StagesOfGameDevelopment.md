# Stages of Game Development

This is a high-level map of common development stages with best practice recommendations. These stages are **signposts**. Studios may use different names and may merge stages depending on scope, funding, genre, and platform requirements.

---

## Glossary

- **Pre-production:** Discovering what the game *is*, proving it can be built, and de-risking the unknowns.
- **Production:** Building the game *as it is now understood*, at scale, with pipelines and predictable iteration.
- **Prototype:** Fast experiments to learn and verify concepts/fun.
- **Vertical Slice:** A representative chunk of the game that proves quality and pipeline needs (often used for funding/approval).
- **Alpha:** Feature complete (or very close) without polish and stability.
- **Beta:** Content complete with focus on stability, performance, balance, and bug fixing.
- **Release Candidate:** A build that could ship if it passes final checks/certification.
- **Live Ops / Updates:** Post-launch patches, content drops, events, and long-tail marketing beats.

---

# Pre-Production

- **Pre-production is chaotic by nature.** Discovery cannot be scheduled the same way production is scheduled.
- It is best to staff a **small, senior core team** for pre-production, who will be best equipped to determine the core direction and the questions that need to be answered.
- Progress is through **successive “real level prototypes”** (not just mechanics in isolation) with rapid prototyping and iteration.

---

## Phase 0: Concept & Feasibility

**Goal:** Decide the general idea and whether it’s worth pursuing.

**Outputs**
- One-sentence pitch + a slightly longer elevator pitch
- Target platforms, audience, rough scope boundaries
- Initial risks (tech, content, staffing, schedule)

**Exit Criteria**
- Can describe the core experience clearly
- Have a credible path to a playable prototype quickly

**Common Pitfalls**
- Falling in love with a concept before it is proven fun or feasible

---

## Phase 1: Prototype (Exploration)

**Goal:** Learn fast and validate (or kill) assumptions cheaply

**Actions**
- A set of short experiments with clear learnings
- Build small prototypes to test core questions (movement feel, combat loop, puzzle readability, multiplayer feasibility, camera philosophy, etc.)

**Outputs**
- A clear “core loop” hypothesis
- Updated risk list

**Exit Criteria**
- Found at least one “spark” worth pursuing
- Known unknowns (knowing what is not yet fully understood/known and have a plan to test them)

**Common Pitfalls**
- Treating prototypes like production content (over polishing, premature optimization, etc.)
- Being hesistant to throw work away

---

## Phase 2: Vertical Slice

**Goal** 
- Prove small portion of the game that is **polished enough to stand on its own** 
- Prove the concept will succeed *later* in the market
- Prove the team can hit target quality *and* repeat it within technology, time, and budget constraints
- Art, UX, audio, and gameplay quality at intended shipping bar
- Pipeline viability (the team can produce content at the needed pace)
- Performance budget directionally makes sense

**Outputs**
- Vertical Slice
  - Shows:
    - The core experience is compelling, not just “promising”
    - Fundamentals are working (feel, readability, feedback, pacing)
    - The look is strong *in-engine*, not just in concept art
    - The required tech is real (or clearly achievable)
- Macro Design
  - Documents:
    - Player abilities / core verbs
    - Level/encounter structure patterns
    - Progression structure (linear, hub-based, systemic, etc.)
    - The planned variety and how it’s distributed across the game
    - Scope boundaries (what is in, what is explicitly out)
  - **Micro design** (moment-to-moment level details) will be locked down during production.

**Exit Criteria**
- Publishable first playable that convinces the team (and ideally real players)
- The macro design is clear enough to prevent feature creep and guide content teams
- Estimates of production schedules based on tested workflows

**Common Pitfalls**
- Insufficient user testing to thoroughly prove systems and ideas
- Building a one-off “hero slice” that can’t be repeated (special-cased tools, unsustainable handcraft)
- Leaving pre-production without the fundamentals nailed, then “hoping it’ll get better” during production

---

# Production

- **Production** works to build the full game efficiently based on the discoveries and knowledge from pre-production
- Planning becomes meaningful: **executing on a defined vision**
- Teams scale and pipelines matter
- Most work is **repeatable content creation + integration + iteration**
- **Regular internal milestones** (levels, quests, missions, features)
- Increasingly complete game build with real progression

---

## Phase 3: Alpha (Feature Complete)

**Goal:** The game is playable end-to-end with core systems in place.

**Actions**
- Major features are implemented (even if unpolished)
- The game can be played through without “missing chunks”
- Bugs and balance issues are expected
- Market and user testing with expected audience segments

**Exit Criteria**
- All planned systems are developed and integrated

**Common Pitfalls**
- Insufficient user testing and iteration
- Exiting “Alpha” when important systems of the game are missing or unintegrated 

---

## Phase 4: Beta (Content Complete + Stabilization)

**Goal:** Lock content and make it shippable.

**Actions**
- Development on stability, performance, polish, and tuning
- Heavy bug fixing, performance work, balance/tuning
- Platform certification requirements handling for consoles
  - Note: Many platforms require an initial build candidate to pass certification before many of the publishing features are accessible.

**Exit Criteria**
- Content complete (levels, missions, narrative, items, etc.)
- Only fixes and small adjustments remaining; no destabilizing changes
- Build quality is approaching release candidate

**Common Pitfalls**
- Late content churn that reintroduces bugs faster than QA can validate them

---

## Phase 5: Release Candidate (RC) & Certification

**Goal:** Create a build that could ship.

**Actions**
- Certification submissions (console)
- Final regression testing, compliance checks, save migration testing
- Launch readiness: storefront, pricing, depots, day-one patch plan

**Exit Criteria**
- A “gold” build is approved, with a clear day-one patch strategy if needed

**Common Pitfalls**
- Not recognizing and planning for strict platform approval timelines (especially for certification and store publishing)
- Not having risk mitigations for core system failures (such as matchmatching, save systems, etc.)

---

## Phase 6: Launch

**Goal:** Ship a stable product and support players in real time.

**Actions**
- Marketing
- Crash response, hotfix ability, support workflows
- Community and review monitoring
- Clear public communication (known issues, patch notes, roadmap expectations)

**Common Pitfalls**
- Slow, overly corporate, or antagonistic responses to issues and community feedback

---

## Phase 7: Live Ops / Updates (Post-Launch)

**Goal:** Sustain the game and extend its tail.

**Actions**
- Hotfixes and bug patches
- Quality-of-life improvements
- Content updates, events, seasonal beats
- Ports and platform expansions
- Marketing beats tied to updates (festivals, bundles, discounts)

**Common pitfall**
- Shipping updates without a stability gate (can instead use “beta-like” stabilization periods for each patch)

---

## A Note on Playtesting (Across All Stages)

Playtesting is not a single milestone, it is a repeated practice:
- Early: validate feel and comprehension (watch what players do, not just what they say)
- Mid: tune pacing, difficulty, onboarding, readability
- Late: verify end-to-end experience and find “pinch points” where players churn

Playtesting and implementation of playtest feedback should be core to the development schedule. 


