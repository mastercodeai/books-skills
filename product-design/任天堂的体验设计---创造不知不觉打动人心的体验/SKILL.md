# SKILL: Nintendo Experience Design Principles

## When to use
- Designing products, services, or interfaces that need to feel intuitive
- Creating experiences that sustain engagement over time
- Making communication (presentations, teaching, marketing) more compelling
- Any situation where you need to move people from understanding → action → meaning

## Core Mental Model

### The Experience Chain
```
体验 (Experience) → 感情 (Emotion) → 记忆 (Memory)
```
People remember what moves them emotionally. Design for emotion, not just function.

## Scene Routing

Determine which design type dominates based on your current situation:

```
START: What is the user's primary problem?
│
├─ "Users can't figure out what to do / feel lost"
│   → ROUTE TO: Intuitive Design
│
├─ "Users understand it but are bored / disengaged / fatigued"
│   → ROUTE TO: Surprise Design
│
├─ "Users engage but feel no meaning / no reason to return"
│   → ROUTE TO: Story Design
│
└─ "Users never even start"
    → ROUTE TO: Intuitive Design (first contact problem)
```

**Combination patterns:**
- **Launch phase**: Intuitive Design dominant (lower barrier to entry)
- **Growth phase**: Surprise Design dominant (sustain curiosity)
- **Maturity phase**: Story Design dominant (create lasting meaning)
- **Crisis phase** (churn/decline): Re-introduce Surprise Design to re-energize

### Three Types of Experience Design

**1. Intuitive Design (直觉设计)** — "不由自主就做了"
```
假设 (Hypothesize) → 尝试 (Try) → 高兴 (Confirm with joy)
```
- Let users discover rules themselves through environment cues (affordances + signifiers)
- Key principle: **"Understanding" beats "good/correct"** — prioritize making things comprehensible over showcasing quality
- Users trust self-discovered knowledge for life (like riding a bicycle)
- Keep each cycle short (<10 seconds of uncertainty)
- Make things simple and easy — this is harder than making them complex
- **Initial Effect**: front-load learning content when attention is highest

**2. Surprise Design (惊喜设计)** — "不由自主就着迷"
```
误解 (Misconceive) → 尝试 (Try) → 惊讶 (Be surprised)
```
- Addresses the weakness of intuitive design: fatigue and boredom from repetition
- Exploits two kinds of belief:
  - **Belief in premise**: "This product/experience is X" → betray it
  - **Belief in normality**: "Taboo things won't appear" → introduce them
- **10 Taboo Themes** for creating surprise:
  - Primal positive: Sex, Food, Gain/Loss, Recognition
  - Primal negative: Filth, Violence, Chaos, Death
  - Complex: Luck/Chance (概率), Personal Privacy (暴露个性)
- Insert surprise at peak fatigue points to re-energize engagement
- Non-essential products MUST create surprise to survive (essential products don't need to)

**3. Story Design (故事设计)** — "不由自主想叙述"
```
吸引 (Attract) → 成长 (Grow) → 意志 (Will)
```
- The meaning-making layer — transforms experience from entertainment to growth
- **Environmental Storytelling**: scatter information fragments, let users piece together "what happened"
- **Rhythm & Contrast**: alternate passive/info-rich ↔ active/info-poor scenes (wave pattern)
- **Foreshadowing**: plant hints whose true meaning is revealed later
- **Three Growth Themes**:
  - Collection & Repetition: show gaps + whole → user fills gaps naturally
  - Choice & Deliberation: offer risk/reward tradeoffs → user self-adjusts difficulty
  - Companion Reversal & Empathy: frustrating companion → crisis → overcome hatred → grow
- **Return to Origin**: end at the starting point so users can compare before/after selves and notice their growth
- Users grow, not just characters — the fictional story is a vehicle for real player growth

## Decision Framework

| Problem | Apply | Effect |
|---------|-------|--------|
| Users can't understand what to do | Intuitive Design | Users figure it out themselves |
| Users get fatigued/bored | Surprise Design | Re-energizes engagement |
| Users see no meaning/value | Story Design | Creates sense of purpose and growth |

## Failure Modes & Anti-Patterns

### Failure Modes

| Symptom | Root Cause | Fix |
|---------|-----------|-----|
| Users try once, never return | First-contact failure — no Initial Effect | Front-load the most discoverable, rewarding moment; cut all setup friction |
| Users get it but leave quickly | No surprise injection — monotone loop | Insert a taboo-theme moment or subverted expectation at the 3rd-4th interaction |
| Power users disengage | No Story Design layer — all surface, no depth | Add foreshadowing + Return-to-Origin arc so mastery feels meaningful |
| Surprise feels cheap/offensive | Taboo theme deployed without context or payoff | Ensure surprise serves the arc — it must reveal something, not just shock |
| Users can't explain why they like it | Design is intuitive but has no emotional hook | Layer at least one surprise moment that triggers an emotional response |
| Tutorial drags / users skip it | Instruction disguised as experience | Convert tutorial into discoverable affordances; let users hypothesize and confirm |
| Users feel trapped / resentful | No graceful exit, no "cheating" allowed | Add explicit stopping points + hidden shortcuts |

### Anti-Patterns

1. **The Lecture Trap**: Over-explaining how things work instead of letting users discover. If your onboarding has more than 3 sentences of text, you've already failed.
2. **Feature Showcase**: Designing to demonstrate product quality rather than user comprehension. Users don't care how clever your system is — they care that they figured it out.
3. **Surprise Without Structure**: Random shocking moments that don't connect to any narrative or growth arc. Surprise without foreshadowing is just noise.
4. **Meaning Without Emotion**: Telling users "this is meaningful" instead of making them feel it. Story must be experienced, not announced.
5. **The Infinite Loop**: Engagement hooks with no exit or resolution. Users eventually feel imprisoned and develop negative brand association.
6. **Complexity as Depth**: Adding features/mechanics to create the illusion of richness. True depth comes from a few elements that interact in surprising ways.
7. **Adult Override**: An adult/authority figure choosing what's "correct" for the user instead of preserving their freedom to discover (including the freedom to fail).

## Checkpoints

Use these checkpoints at each design phase to validate your work:

### Pre-Design Checkpoints
- [ ] Can a first-time user understand the goal within 10 seconds?
- [ ] Have I identified which design type (Intuitive/Surprise/Story) is primary for this phase?
- [ ] Am I designing for someone who has never seen this before?

### Intuitive Design Checkpoints
- [ ] Can users hypothesize what to do without instruction?
- [ ] Does the environment itself communicate affordances?
- [ ] Is each discovery cycle under 10 seconds of uncertainty?
- [ ] Is the first interaction the most rewarding moment?
- [ ] Would I describe this as "simple" — and did that require significant effort?

### Surprise Design Checkpoints
- [ ] Have I identified what belief (premise or normality) I'm subverting?
- [ ] Is the surprise placed at a fatigue/boredom peak, not randomly?
- [ ] Does the surprise connect to the larger experience arc?
- [ ] Would users want to tell someone about this moment?
- [ ] Is the taboo theme contextualized, not gratuitous?

### Story Design Checkpoints
- [ ] Have I planted foreshadowing that pays off later?
- [ ] Is there a rhythm of tension and release (wave pattern)?
- [ ] Does the experience end at (or reference) the starting point?
- [ ] Would users describe their own growth, not just the content?
- [ ] Can users narrate their experience to others as a story?

### Post-Design Review
- [ ] Does the experience chain hold? (Experience → Emotion → Memory)
- [ ] Is the user the protagonist, not the product?
- [ ] Have I designed the exit/stopping point as carefully as the engagement?
- [ ] Would I want to experience this myself?

## Design Principles

1. **Simplicity is supreme**: Making things simple is harder than making them complex; do it anyway
2. **User understanding > Product quality**: A product users can't grasp is worthless regardless of quality
3. **Design for the first-time user**: Initial Effect means first contact is the highest-leverage learning moment
4. **Product is supporting actor**: The user's life is the protagonist; never steal their time
5. **Allow graceful exit**: Design explicit stopping points; don't trap users
6. **Give freedom including "cheating"**: User choice = user growth; even shortcuts serve the experience
7. **Emotion determines memory**: Only emotionally charged experiences become lasting memories
8. **Feedback is fundamental**: Every user action must get a response — this is the basic structure of interaction

## Practical Applications

### Presentations/Communication
- Use connecting words to preview next slide (avoid "接下来")
- Insert taboo themes or silence periodically to recapture attention
- Show your main point at the beginning AND end — let audience feel their own growth

### Team Facilitation
- Break "must say good ideas" constraint → discuss "useless ideas" first
- Build team identity through shared discovery (intuitive design in group)
- Use foreshadowing: find hidden significance in members' past remarks

### Product Design
- Always design for someone who has never seen your product before
- Provide explicit "cheat" options — freedom to choose = freedom to return
- Design the experience's stopping point as carefully as its engagement hooks

### Teaching/Parenting
- Non-compliance often means lack of clear target (not laziness)
- Boredom requires deliberate wrong attempts to reignite appreciation
- Shared discovery ("I don't know either!") creates engagement for both parties

## Key Insight
> Not because the game itself is interesting, but because one's own intuitive experience is interesting — that's why people play. The brain always wants to understand the world. Design experiences that serve this fundamental drive.
