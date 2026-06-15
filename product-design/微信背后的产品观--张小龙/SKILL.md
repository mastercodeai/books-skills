# SKILL: Zhang Xiaolong's Product Philosophy

> Based on "微信背后的产品观" by Zhang Xiaolong (Allen Zhang), creator of WeChat.

---

## When to Use
When designing products, analyzing user needs, making product decisions, evaluating features, or when facing product strategy questions. This skill applies Zhang Xiaolong's human-nature-driven product thinking methodology.

---

## Scene Routing

Route incoming product questions to the appropriate decision framework:

| Scene | Trigger Signals | Go To |
|---|---|---|
| **Requirement Analysis** | "Should we build X?", "Users are asking for…", "The data shows…" | → §Requirements Analysis |
| **Product Design** | "How should this work?", "What's the structure?", "Design review" | → §Design Methodology |
| **User Psychology** | "Why aren't users engaging?", "What motivates them?", "Group behavior" | → §User Psychology & Human Nature |
| **Feature Decisions** | "Add or remove?", "Prioritize A vs B?", "Ship or wait?" | → §Decision Framework |

If multiple scenes apply, start with **User Psychology** (the root layer), then move outward.

---

## Core Principles

### 1. Users Are People, Not Data
- Never abstract users into numbers, personas, or segments (high/mid/low-end is immoral)
- Understand human nature: laziness, impatience, dislike of learning, herd mentality, desire for existence and validation
- Use **self-empathy** (以己推人): your own instincts as a human are the best proxy for user needs
- The real user is NOT the person sitting next to you — 80% are "grassroots" users far from your world

### 2. Product Manager = Creator Beside God
- Build a system with rules, then let the group **self-evolve** within it
- Unpredictability and emergent behavior are features, not bugs
- A product with **DNA** (core values and cognition) evolves; without DNA it's just accumulated features

---

## User Psychology & Human Nature

> Route here when the question involves understanding *why* users behave as they do.

### Fundamental Human Drivers
- **Laziness**: Users won't learn; if it requires effort, it fails
- **Impatience**: Response speed is the #1 UX priority — every 100ms matters
- **Herd mentality**: People follow groups; design for group effects, not individual features
- **Desire for validation**: People want to feel seen, interesting, successful
- **Curiosity**: "Cool" and "fun" beat "useful" and "cheap" — psychological motivation > functional utility
- **Confiding impulse**: Drift Bottle isn't dating; it's the need to confide and be nosy

### Psychological Need Discovery Method
1. **Start from your own needs** — if you need it, millions likely do too
2. **Look behind the feature request** — user says "I want X" but means "I feel Y"
3. **Observe social media for 1 hour daily** — feel the emotional "trend," not the data
4. **Design for the unseen 80%** — the "grassroots" majority, not your tech-savvy colleagues
5. **Test against human nature, not logic** — rational analysis misses irrational behavior

### Failure Modes in Understanding Users

| Failure Mode | Symptom | Root Cause | Fix |
|---|---|---|---|
| **Persona Trap** | Creating elaborate user personas that feel precise but predict nothing | Abstracting humans into categories instead of understanding behavior | Drop personas; use self-empathy and direct observation |
| **Vocal Minority Bias** | Building features for the loudest 5% of users | Confusing feedback volume with need prevalence | Weight observations by social media trends, not support tickets |
| **Rational User Fallacy** | Assuming users will read instructions, compare options logically | Product managers are more rational than average users | Design for the laziest, most impatient version of yourself |
| **Feature = Need Confusion** | Treating "add a button" as solving a need | Skipping the psychological layer entirely | Always ask: "What emotional state does this address?" |
| **Data-Only Decisions** | Killing or building based solely on metrics | Data shows what happened, not why or what should exist next | Combine data observation with human-nature reasoning |

---

## Requirements Analysis

> Route here when deciding *what* to build or whether a need is real.

### What NOT to Do
1. ❌ Don't survey users for new features (surveys only validate existing ones)
2. ❌ Don't analyze/brainstorm in isolation
3. ❌ Don't copy competitors (you'll never understand their reasoning deeply enough)
4. ❌ Don't listen to product managers' personal needs (they're more rational than average users)
5. ❌ Don't say "I have a great idea!" — 99% of the time, denying new ideas is correct
6. ❌ Don't do what users say — user feedback reveals thinking, not solutions

### What TO Do
1. ✅ **Spend 1 hour daily** reading how real users talk about your product on social media — feel the "trend"
2. ✅ **Satisfy your own needs first** — if you need it, millions likely do too
3. ✅ **Find the psychological need BEHIND the feature request** — Drift Bottle ≠ dating; it's about the desire to confide and be curious
4. ✅ **Design for group effects** — create mechanisms, let users generate emergent behavior (Shake, Nearby People)
5. ✅ **Determine version features at the last moment** — plan is the enemy; iterate based on latest understanding
6. ✅ **"Cool" and "Fun" beat "useful" and "cheap"** — psychological motivation > functional utility

### Needs Come From:
- Curiosity about group effects
- Your own daily needs
- Understanding of current life trends
- Understanding of information flow
- Vision of the future (more important than current needs)

### Requirements Analysis Checkpoint

Before accepting any requirement, verify all five:

- [ ] **Source validity**: Did this come from observed behavior, not a survey or feature request?
- [ ] **Psychological layer**: Have you identified the human emotion behind the stated need?
- [ ] **Self-empathy test**: Would YOU feel this need on a normal Tuesday, not just in a brainstorm?
- [ ] **Majority check**: Does the unseen 80% of users care about this, or just the vocal 5%?
- [ ] **Denial test**: If you said "no" to this requirement for 3 months, what actually breaks?

---

## Design Methodology

> Route here when deciding *how* something should work or how the product is structured.

### Structure First
- **Product structure > feature details** — get the skeleton right first, hide branches deep
- **Design is classification** — most product problems reduce to poor classification
- **Abstract to simplify** — 100 needs → 10 needs → 1 need (find the commonality)
- **Feature modules must be organically connected**, not stacked like blocks

### Scene-Driven Design
- **Design for scenes, not feature lists** — a feature without context is meaningless
- **Only capture the main scene** — Moments focused on photos (easy), hid text posting
- **Let features exist invisibly** — merchant membership only appears after scanning QR code
- **Distinguish mobile from PC** — phone is an extension of your hand and touch

### Restraint Principles
- **Don't over-design** — Nearby People is the simplest in its category
- **Lose features before losing experience** — no "edit" button to avoid accidental deletion triggers
- **If the solution is too complex, the problem itself is wrong**
- **Response speed is ALWAYS the #1 UX priority** — simple + fast = effortless
- **If a feature doesn't excite you, don't build it** — curiosity is the product manager's engine
- **Preserve change** — don't build v2.0 features into v1.0; launch, learn, then decide

### Evolution Over Planning
- Products evolve, they're not planned
- **No organic growth → no promotion** — KPI is a byproduct of good products
- **Stay rough, stay clumsy** — if no good solution exists yet, leave the problem alone
- **Let users drive users** — show their own empty avatar → they set it naturally (no forced prompts)
- **Extreme simplicity cannot be surpassed** — if something is already at minimum, making it less is nearly impossible

### Design Failure Modes

| Failure Mode | Symptom | Root Cause | Fix |
|---|---|---|---|
| **Feature Creep via Iteration** | Each version adds; nothing is removed | No one owns the "what should we kill?" question | Every sprint: remove one thing before adding one |
| **Complexity as Thoroughness** | "Comprehensive" designs with 15 settings per screen | Confusing coverage with quality | If the solution needs a tutorial, the problem is wrong |
| **PC Thinking on Mobile** | Dense layouts, hover-dependent interactions | Porting desktop mental models to touch devices | Design for one thumb, one hand, 3-second attention |
| **Stacked Features** | Modules added as isolated blocks with no organic connection | Building from a feature checklist, not a structural vision | Start from product structure; features must flow from skeleton |
| **Premature Perfection** | Shipping v1.0 with v2.0 features "to be thorough" | Fear of looking incomplete | "Stay rough, stay clumsy" — ship what you understand now |

### Design Checkpoint

Before finalizing any design, verify:

- [ ] **Structure test**: Can you draw the product skeleton on a napkin? If not, it's not clear enough.
- [ ] **Classification test**: Is this a classification problem disguised as a feature problem?
- [ ] **Scene clarity**: Can you describe the ONE main scene in one sentence?
- [ ] **Speed preservation**: Will this design maintain sub-second response for core flows?
- [ ] **Invisibility test**: Can the feature exist without appearing in the main UI until needed?
- [ ] **Restraint test**: What can you remove without breaking the core experience?

---

## Feature Decisions

> Route here when evaluating whether to add, remove, or prioritize a feature.

### The Add/Remove Decision Matrix

| Question | If YES | If NO |
|---|---|---|
| Does it satisfy a **psychological need**? | Proceed | Stop — functional-only needs rarely stick |
| Would you be **personally excited**? | Proceed | Strong signal to reject |
| Does it work for the **main scene**? | Proceed | Redesign for the scene or kill it |
| Can it create **group effects**? | High value — prioritize | Proceed cautiously |
| Is it **simple enough** without text explanation? | Proceed | Simplify or kill |
| Does it preserve **product DNA**? | Proceed | Non-negotiable rejection if it violates DNA |
| Would removing it hurt **less** than adding? | Don't add | Proceed |
| Is **response speed** preserved? | Proceed | Non-negotiable rejection if speed degrades |

### The Kill Decision

When deciding whether to remove an existing feature:
1. If nobody would notice in 30 days → **kill it**
2. If removing it requires a blog post explaining why → it's probably core, **keep it**
3. If it needs a tooltip to explain → it was a mistake, **kill it**
4. If it makes the product feel schizophrenic → **kill it**, even if the data says it's used

### Feature Decision Failure Modes

| Failure Mode | Symptom | Root Cause | Fix |
|---|---|---|---|
| **KPI-Driven Building** | "This will move the metric" as the primary argument | Inverting cause and effect | KPI follows good products; never start from the metric |
| **Competitor Parity** | "Competitor X has this" as justification | Fear of missing out, not understanding of own users | You'll never understand their reasoning; trust your own |
| **Integration Fantasy** | "Let's merge these 5 products into one" | Believing 50 + 50 = 100 | 50 + 50 = <50; bundled products are never good |
| **Tab Proliferation** | Adding more tabs/categories as features grow | Lack of structural thinking | 4 tabs max; if you need more, the structure is broken |
| **Content Import Temptation** | "Let's pull in content from other platforms" | Wanting engagement without earning it | Wrong atmosphere for the scene; breaks the vibe |
| **Persistent Feature Addition** | Every sprint adds, nothing is removed | No kill culture | Require removing one feature for every new one added |
| **Schizophrenic Compromise** | Features that reflect conflicting product visions | Collective decision-making on core direction | Persistent (even stubborn) product leadership; listen, then decide |

### Feature Decision Checkpoint

Before any feature decision (add or remove):

- [ ] **Psychological root**: Is this grounded in a human emotion, not just a use case?
- [ ] **Excitement test**: Does this make you curious to see how users will surprise you?
- [ ] **DNA alignment**: Does this reinforce the product's core values, or dilute them?
- [ ] **Schizophrenia check**: Would a neutral observer say this feature belongs with the others?
- [ ] **Simplicity gate**: Can you explain the feature in 5 words or fewer?
- [ ] **Speed gate**: Does this add latency to any existing core flow?
- [ ] **Kill gate**: If this feature existed and you were reviewing it today, would you keep it?

---

## Product Temperament (气质)

### Values Over Features
- **Your values determine every product decision** — even small ones like filters or "iPhone online" badges
- **It's a WORK (作品), not just a PRODUCT (产品)** — works crave perfection
- **Craftsman, not designer** — optimize 10 details daily, each detail is a complete product
- **Product with a soul** — organic structure, muscles (features), temperament (values), agile reactions (interaction), eloquent copy (文案), harmonious as a whole

### Soul vs. Schizophrenia
- A product built by compromise from conflicting ideas = **schizophrenic product**
- **Persistent (even stubborn) product leadership prevents schizophrenia**
- Collective decisions → mediocrity and fragmentation
- But: listen to collective discussion first, then decide with conviction

### Cultural Expression
- **Text reflects temperament** — clear, friendly, never condescending
- Avoid: "吧", "哦", mandatory-sounding phrases, unnecessary "成功/失败" labels
- Use "你" not "您"
- **Welcome pages are for expressing ideas**, not listing features
- **Aesthetic sensibility matters** — rock music, photography, art inform product taste

---

## UI Principles

1. **Clarity > Beauty** — well-organized information beats visual flair
2. **One theme per screen** — like photography, one subject, blur the rest
3. **Consistent elements** — one font, one control style, one background
4. **Obvious default actions** — blue "Done" button in every dialog
5. **Polish the most common operations** relentlessly
6. **Features needing text explanation = bad UX** — avoid Tips tooltips
7. **Hide numbers** — nobody cares about 78.56% progress
8. **Forbid designers from using competitor products** — product managers summarize, designers create independently
9. **Explore new mobile interactions** — sensors, gestures, hardware capabilities

---

## Master Decision Checklist

When evaluating whether to build a feature:

- [ ] Does it satisfy a **psychological need**, not just a functional one?
- [ ] Would I personally be **excited** about this?
- [ ] Does it work for the **main scene** without complicating others?
- [ ] Can it create **group effects** or emergent behavior?
- [ ] Is the solution **simple enough** that it doesn't need text explanation?
- [ ] Does it preserve the product's **DNA and values**?
- [ ] Would removing it hurt **less** than adding it?
- [ ] Is the **response speed** preserved?
- [ ] Does it feel like a **natural evolution**, not a forced addition?

---

## Anti-Patterns Catalog

### The Seven Deadly Product Anti-Patterns

| # | Anti-Pattern | What It Sounds Like | Why It's Wrong | Counter-Principle |
|---|---|---|---|---|
| 1 | **Survey-Driven Design** | "Let's survey users" | Users can't tell you what doesn't exist yet | Self-empathy + social media observation |
| 2 | **Competitor Mimicry** | "Let's do what competitor X does" | You'll never understand their reasoning deeply | Trust your own understanding of human nature |
| 3 | **Integration Delusion** | "Let's merge these products" | 50 + 50 = <50; bundled products are never good | Keep products independent and focused |
| 4 | **Complexity Creep** | "Let's add a Tab / more options" | Complexity accumulates silently until it kills the product | 4 tabs max; enforce with agreements |
| 5 | **Content Import Temptation** | "Let's import content from other platforms" | Wrong atmosphere for the scene; breaks the vibe | Earn engagement within your own ecosystem |
| 6 | **Education Escalation** | "Let's use Tips to teach users" | Users don't want education; if they miss it, they miss it | Design so intuitively that instruction is unnecessary |
| 7 | **KPI Inversion** | "This feature will drive KPI" | KPI follows good products, not the other way around | Build for human nature; metrics are a byproduct |

### Advanced Anti-Patterns

| Anti-Pattern | What It Sounds Like | Why It's Wrong | Counter-Principle |
|---|---|---|---|
| **Consensus Product** | "Let's vote on the direction" | Collective decisions → mediocrity and schizophrenia | Listen to discussion, then decide with conviction |
| **Data Supremacy** | "The data says we should…" | Data shows what happened, not what should exist | Combine data with human-nature intuition |
| **Feature Checklist Culture** | "Competitor has 12 features, we have 8" | Feature count ≠ product quality | Abstract 100 needs to 1 need; find the commonality |
| **Premature Generalization** | "This should work for all use cases" | Designing for everything = designing for nothing | Capture the main scene; let others emerge naturally |
| **Forced Engagement** | "Let's send a push notification to bring them back" | Manipulation breeds resentment | Let users drive users; empty avatar → natural action |
| **Tooltip Dependency** | "We'll add a tooltip to explain" | If it needs explanation, the design failed | Redesign until explanation is unnecessary |

---

## Failure Modes — Comprehensive Reference

### Product Strategy Failures

| Failure Mode | Early Warning Signs | Diagnosis | Recovery |
|---|---|---|---|
| **Direction Schizophrenia** | Features feel disconnected; users can't describe what the product "is" | Multiple competing visions forced into one product | Appoint one product leader with conviction; kill conflicting features |
| **Growth-at-All-Costs** | Promotions, incentives, forced onboarding | Organic growth has stalled; KPI pressure overrides taste | Stop all promotion; focus on the one thing that delights |
| **Platform Trap** | "We need to become a platform" | Ego-driven scope expansion beyond core competence | Return to core use case; platforms emerge, they aren't declared |
| **Feature Debt** | 100 features, none polished | Speed of addition > quality of execution | Feature freeze; polish existing flows for 2 sprints |

### Execution Failures

| Failure Mode | Early Warning Signs | Diagnosis | Recovery |
|---|---|---|---|
| **Speed Degradation** | Loading times creep up; animations feel sluggish | Performance wasn't treated as a feature | Make response speed a non-negotiable release gate |
| **Design-by-Committee** | "We need alignment across 5 teams" | No single product owner with taste and authority | Reduce stakeholders; one person decides design |
| **Over-Engineering** | Simple features taking weeks to ship | Solution complexity exceeds problem complexity | Restate the problem in one sentence; if it's not simple, the problem is wrong |
| **Tip Creep** | "Just add one more tooltip/instruction" | Fundamentally unintuitive design being papered over | Kill the feature or redesign from scratch |

### Team & Culture Failures

| Failure Mode | Early Warning Signs | Diagnosis | Recovery |
|---|---|---|---|
| **Taste Erosion** | "Users won't notice this detail" | Team no longer cares about craft | Zhang's rule: each detail is a complete product |
| **Rationality Bias** | "The use case analysis shows…" | Team thinks like analysts, not humans | Spend time with real users' social media; feel, don't analyze |
| **Copy Culture** | "Let's see what Apple/Google/ByteDance did" | Lack of original product thinking | Forbid designers from using competitor products; summarize independently |
| **Metric Worship** | Every discussion starts with dashboard numbers | Data replaced intuition as the decision framework | Use data as observation, not direction; lead with human understanding |

---

## Summary Formula

```
Great Product = Human Nature Understanding
              + Psychological Need Discovery
              + Structural Simplicity
              + Scene-Driven Design
              + Extreme Restraint
              + Cultural Temperament
              + Relentless Speed Optimization
```

---

## Quick Reference: Scene → Action

```
INCOMING QUESTION
    │
    ├─ "Should we build X?" ─────────────→ §Requirements Analysis Checkpoint
    ├─ "How should this work?" ──────────→ §Design Checkpoint
    ├─ "Why aren't users doing Y?" ──────→ §User Psychology Failure Modes
    ├─ "Add feature A or B?" ────────────→ §Feature Decision Checkpoint
    ├─ "Competitor Z has this…" ─────────→ §Anti-Pattern #2 (Competitor Mimicry)
    ├─ "The data says…" ────────────────→ §Anti-Pattern (Data Supremacy)
    ├─ "Let's survey users…" ───────────→ §Anti-Pattern #1 (Survey-Driven Design)
    └─ "Let's add a tooltip…" ──────────→ §Anti-Pattern (Tooltip Dependency)
```

---

> "我所说的，都是错的。" — Don't take any of this as doctrine. Only what YOU deeply understand is truly yours.
