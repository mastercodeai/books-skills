# SKILL.md — Growth Hacking Playbook

**Source**: *Hacking Growth* by Sean Ellis & Morgan Brown  
**Domain**: Product-led growth, experimentation, user lifecycle optimization

---

## Scene Routing

Route to the right section based on your current challenge:

| Scene | Signal | Jump To |
|-------|--------|---------|
| **PMF Validation** | "Not sure if we should scale yet" / low survey scores / high churn | → [PMF Gate](#scene-1-pmf-validation-gate) |
| **Growth Metrics Setup** | "No North Star defined" / tracking vanity metrics / no dashboards | → [Growth Metrics](#scene-2-growth-metrics--instrumentation) |
| **Viral Loops** | "Want to add referrals" / K factor is low / sharing is manual | → [Viral Loops](#scene-3-viral-loops--referral-engine) |
| **Retention** | "Users sign up but don't stick" / flat retention curve / high churn | → [Retention](#scene-4-retention--reactivation) |
| **Experiment Cadence** | "Running experiments randomly" / no prioritization / slow velocity | → [Full Growth Loop](#core-mental-models) |

---

## Scene 1: PMF Validation Gate

**Goal**: Confirm product-market fit BEFORE spending on growth.

### Steps
1. **Run Sean's Indispensability Survey**
   - Target: active users (need ≥300 responses for statistical significance)
   - Question: "How disappointed would you be if this product disappeared?"
   - Thresholds:
     - ≥40% "very disappointed" → **Green light** for growth experiments
     - 25–40% → Minor product tweaks + reframe messaging → re-test in 4 weeks
     - <25% → **STOP**. Fundamental product rework needed. No growth spending.
2. **Check Retention Curve**
   - Plot cohort retention over 8+ weeks
   - Curve must flatten (plateau) before scaling acquisition
   - If still dropping at week 8 → not ready
3. **Identify the Aha Moment**
   - Compare power users vs. churned users: what actions differ?
   - Examples: Facebook (7 friends/10d), Slack (2000 messages), Dropbox (first share)
   - Quantify: "X% of users who do [action] retain vs Y% who don't"

### Checkpoint: PMF Gate
- [ ] ≥40% "very disappointed" on indispensability survey
- [ ] Retention curve flattens by week 6–8
- [ ] Aha Moment identified and measurable
- [ ] At least one cohort shows stable retention before scaling

### Failure Modes
| Failure | Symptom | Fix |
|---------|---------|-----|
| **False PMF signal** | Survey skewed to power users only | Survey random active users, not just champions |
| **Premature scaling** | Retention still dropping but acquisition spending up | Pause all acquisition until curve flattens |
| **Aha Moment too late** | Users churn before reaching the moment | Shorten time-to-value; remove onboarding friction |
| **Survey too small** | <100 responses, high margin of error | Wait for statistical significance before deciding |

---

## Scene 2: Growth Metrics & Instrumentation

**Goal**: Build the measurement foundation so experiments aren't flying blind.

### Steps
1. **Define the Growth Equation**
   - Break revenue/growth into multiplicative levers
   - Example: `eBay = Sellers × Items Listed × Buyers × Successful Transactions = GMV`
2. **Pick ONE North Star Metric**
   - Must reflect core value delivery (not vanity)
   - Evolves by stage: early = activation, growth = retention, mature = revenue
3. **Build the Data Stack**
   - Integrate: web analytics + CRM + payment + support into one warehouse
   - Instrument every key event with consistent naming
4. **Set Up Cohort Dashboards**
   - Segment by: sign-up date, acquisition channel, behavior cluster
   - Weekly automated reporting on North Star + funnel stages

### Checkpoint: Metrics Ready
- [ ] Growth equation defined with 3–5 multiplicative levers
- [ ] North Star metric chosen and agreed upon by team
- [ ] All key events instrumented and flowing to warehouse
- [ ] Cohort dashboard live, updated weekly
- [ ] 99% confidence level set as default for experiment analysis

### Failure Modes
| Failure | Symptom | Fix |
|---------|---------|-----|
| **Vanity metric worship** | Page views up but revenue flat | Always tie metrics to North Star or revenue |
| **Data silos** | Marketing data separate from product data | Integrate into single warehouse |
| **Instrumentation gaps** | Can't run experiments because events aren't tracked | Audit event coverage before starting experiments |
| **P-hacking** | Running tests until p<0.05 by chance | Pre-register hypotheses; use 99% confidence |

---

## Scene 3: Viral Loops & Referral Engine

**Goal**: Instrument virality into the product, not bolt it on.

### Steps
1. **Measure Current Virality**
   ```
   K (Viral Coefficient) = Invitations Sent × Acceptance Rate
   Virality = Payload × Conversion Rate × Frequency
   ```
   - K > 1 is extremely rare and not required for meaningful growth
2. **Identify Natural Sharing Moments**
   - When do users already talk about your product?
   - What's the "payload" — what do recipients see/experience?
3. **Design the Referral Loop**
   - Dual-sided rewards (inviter + invitee both get value)
   - Embed sharing IN the workflow (not as an afterthought popup)
   - Make the reward immediate and tangible
4. **Optimize the Three Variables**
   - **Payload**: make shared content valuable/visible to recipient
   - **Conversion**: landing page must deliver on the promise
   - **Frequency**: create more natural sharing moments

### Checkpoint: Viral Loop
- [ ] Current K factor measured (even if <1)
- [ ] At least one natural sharing moment identified and instrumented
- [ ] Dual-sided incentive designed and tested
- [ ] Shared content/landing page optimized for recipient conversion
- [ ] A/B test plan for payload, conversion, and frequency variants

### Failure Modes
| Failure | Symptom | Fix |
|---------|---------|-----|
| **Bolted-on virality** | Sharing feels spammy, low adoption | Embed sharing in core workflow moments |
| **One-sided reward** | Invitations sent but low acceptance | Add meaningful reward for invitee too |
| **Ignoring payload** | Users share but recipients don't convert | Optimize the shared content/landing experience |
| **Dark patterns** | Users feel tricked into sharing | Never auto-send or obscure opt-out; destroys trust |

---

## Scene 4: Retention & Reactivation

**Goal**: Fix the leaky bucket before pouring more water in.

### Steps
1. **Segment Retention by Behavior**
   - Not all users churn for the same reason
   - Cluster by: usage frequency, features used, acquisition source
2. **Define Inactivity Threshold**
   - Use cohort data: at what point does a user become statistically unlikely to return?
   - Set automated triggers at this threshold
3. **Diagnose Churn Reasons**
   - Survey churned users (incentivize responses)
   - Categorize: product gap, competitor, price, use case expired, never activated
4. **Design Re-engagement Campaigns**
   - Only target users with addressable churn reasons
   - Test: messaging, channel (email/push/in-app), frequency, incentive
   - Know when to stop — some users are gone permanently
5. **Build Habit Loops**
   - Trigger → Action → Reward → Investment (Hook Model)
   - Personalize triggers based on user behavior patterns

### Checkpoint: Retention
- [ ] Retention segmented by at least 3 dimensions (channel, behavior, cohort)
- [ ] Inactivity threshold defined with data
- [ ] Top 3 churn reasons identified from surveys/interviews
- [ ] Re-engagement campaign designed with A/B test plan
- [ ] Habit loop mapped for core product use case

### Failure Modes
| Failure | Symptom | Fix |
|---------|---------|-----|
| **Treating all churn equally** | Same re-engagement for all lost users | Segment by churn reason; only target addressable ones |
| **Re-engaging too late** | Users have already found alternatives | Set triggers at early warning signs, not after full churn |
| **Ignoring new user activation** | Churn is actually an activation problem | Check if churned users ever reached Aha Moment |
| **Spamming win-backs** | Unsubscribes and complaints rise | Limit frequency; make it easy to opt out permanently |

---

## Core Mental Models

### 1. Product-Market Fit First
Before any growth push, validate indispensability:
- **Sean's survey**: "How disappointed would you be if this product disappeared?"
- **Threshold**: ≥40% "very disappointed" = green light
- **Retention curve**: must be flat/stable before scaling acquisition

### 2. The Aha Moment
Every product has one. Find it by comparing power users vs. churned users:
- Facebook: 7 friends in 10 days
- Twitter: follow 30 accounts, 1/3 follow back
- Slack: 2,000 team messages
- Dropbox: first file share
- Qualaroo: 50+ survey responses

### 3. Growth Equation + North Star Metric
Define a simple formula capturing all growth levers:
```
eBay: Sellers × Items Listed × Buyers × Successful Transactions = GMV
```
Pick ONE North Star metric that best reflects core value delivery. It evolves with company stage.

### 4. Growth Loop (The Engine)
```
Analyze → Generate Ideas → Prioritize (ICE) → Test → Analyze → Repeat
```
Run weekly. Every experiment is a learning opportunity. Most fail — that's normal.

---

## Key Frameworks

### ICE Scoring (for experiment prioritization)
| Criterion | Description | Scale |
|-----------|-------------|-------|
| **Impact** | Expected lift on target metric | 1–10 |
| **Confidence** | Evidence backing the hypothesis | 1–10 |
| **Ease** | Time/resources required | 1–10 |

Average the three. Higher score = higher priority. But don't over-index — let data decide.

### AARRR Funnel (Pirate Metrics)
| Stage | Goal | Key Tactic |
|-------|------|------------|
| **Acquisition** | Language-market fit + channel-product fit | Test headlines, find 1–2 best channels |
| **Activation** | Reduce friction to Aha Moment | Friction audit, flip the funnel, single sign-on |
| **Retention** | Build habits, increase LTV | Cohort analysis, triggers, personalization |
| **Revenue** | Maximize per-user value | Price testing, value metrics, decoy pricing |
| **Referral** | Instrumented virality | Dual-sided rewards, embed sharing in UX |

### Virality Formula
```
Viral Coefficient (K) = Invitations Sent × Acceptance Rate
Virality = Payload × Conversion Rate × Frequency
```
K > 1 is extremely rare. Focus on optimizing all three variables rather than chasing K > 1.

### Friction Formula
```
Desire – Friction = Conversion
```
Increase desire (better messaging) OR decrease friction (easier UX). Removing friction is usually the lower-hanging fruit.

### Channel Prioritization (6 factors)
Score each channel 1–10 on: Cost, Targeting, Control, Time to launch, Time to results, Scale. Highest average = test first.

---

## Tactical Recipes

### Recipe 1: Run the Indispensability Survey
1. Deploy to active users (need hundreds of responses)
2. Ask: "How disappointed if product disappeared?"
3. If ≥40% "very disappointed" → proceed to growth experiments
4. If 25–40% → minor product tweaks + language adjustments
5. If <25% → fundamental product work needed, NOT growth experiments

### Recipe 2: Map the Funnel to Aha Moment
1. List every step from first visit to Aha Moment
2. Build a conversion/dropoff funnel report
3. Segment by acquisition channel
4. Survey both converters AND drop-offs at each step
5. Identify the biggest drop-off point → highest-impact experiment zone

### Recipe 3: Weekly Growth Meeting (60 min)
| Time | Agenda |
|------|--------|
| 15 min | Review North Star metric + key metrics, wins, losses |
| 10 min | Review experiment velocity vs. target |
| 15 min | Analyze completed experiment results |
| 15 min | Select next week's experiments from prioritized backlog |
| 5 min | Check idea pipeline health |

### Recipe 4: Design an Experiment Brief
For every idea, specify:
- **Name** (≤50 chars)
- **Description**: Who, What, Where, When, Why, How
- **Hypothesis**: "If we [action], then [metric] will improve by [amount]"
- **Metrics to track**: primary + downstream metrics
- **ICE score**: submitted by idea originator

### Recipe 5: Price Testing
1. Survey users with 4 questions:
   - Too expensive (would never buy)
   - Expensive (but would consider)
   - Good value
   - Too cheap (doubt quality)
2. The intersection = ideal testing range
3. Test decoy packages to leverage pricing relativity
4. Test quarterly for SaaS, more frequently for e-commerce

### Recipe 6: Revive Churned Users
1. Define inactivity threshold (via cohort analysis)
2. Research why they left (surveys, interviews)
3. If reason is addressable → design re-engagement campaign
4. Test messaging, frequency, channels
5. Know when to stop — some users won't return

---

## Anti-Patterns to Avoid

| Anti-Pattern | Why It Fails | Prevention |
|--------------|-------------|------------|
| **Scaling before PMF** | Wastes money on a product people don't love | Gate all acquisition spend on ≥40% indispensability + flat retention curve |
| **Chasing K > 1 virality** | Unrealistic; better to optimize payload × conversion × frequency | Focus on incremental improvements to all three variables |
| **"Growth hacker as solo hero"** | Growth requires cross-functional teams, not lone wolves | Build growth team with engineering, design, data, and marketing |
| **Relying on a single channel** | Channels have ceilings and can change rules (Google, Facebook) | Always test 2+ channels; diversify before hitting ceiling |
| **Optimizing vanity metrics** | Page views ≠ growth. Always tie to North Star | Every metric on dashboard must map to growth equation |
| **Dark patterns in virality** | Tricking users into sharing destroys trust long-term | Never auto-send; always explicit opt-in; test trust impact |
| **Feature bloat** | More features ≠ more value. Often reduces retention | Validate each feature with experiment; measure impact on retention |
| **Ignoring data infrastructure** | Without proper instrumentation, experiments are flying blind | Audit instrumentation before starting experiment cadence |
| **Confirmation bias in experiments** | Seeing desired results, ignoring inconclusive data | Pre-register hypotheses; use 99% confidence; report all results |
| **Experiment theater** | Running many tests but none with real impact | Track experiment velocity AND win rate; focus on high-ICE ideas |
| **Copying other companies' hacks** | What worked for Dropbox won't necessarily work for you | Understand the principle, not the tactic; test in your context |

---

## Case Study Cheat Sheet

| Company | Growth Hack | Result | Key Principle |
|---------|------------|--------|---------------|
| **Dropbox** | Referral program: 250MB each | 60% more signups; 10K → 400K in 14 months | Dual-sided incentive + natural sharing moment |
| **Airbnb** | Craigslist cross-posting | Massive traffic at zero ad cost | Piggyback on existing platforms with your audience |
| **Facebook** | Translation via crowdsourcing; 7 friends in 10 days | Broke through 70M plateau to billions | Aha Moment engineering + localized growth |
| **Hotmail** | "Get your free email" in every email signature | Explosive early growth | Embed payload in natural product usage |
| **LinkedIn** | Outlook contact import | Network effects drove viral growth | Reduce friction to network building |
| **Pinterest** | Personalized onboarding (pick 5 topics) | +20% activation | Guided path to Aha Moment |
| **BitTorrent** | Upgrade button on main screen | +92% daily revenue | Placement > persuasion |
| **Yelp** | Elite user program | 65% users write 6+ reviews; elite = 44% of total | Power user programs drive disproportionate value |
| **Amazon Prime** | Free 2-day shipping + ecosystem | 91% Year 1 retention, 96% Year 3 | Habit formation through subscription |
| **Slack** | 2,000 message threshold | Team becomes committed + upgrades to paid | Quantified Aha Moment → natural upgrade trigger |

---

## Quick Decision Trees

**"Should I start growth experiments?"**
```
Product indispensable (≥40% "very disappointed")?
├── Yes → Retention curve flat?
│   ├── Yes → Define North Star metric → Start growth loop
│   └── No → Fix retention first → Re-check in 4 weeks
└── No → Is it ≥25%?
    ├── Yes → Minor product/language tweaks → Re-test in 4 weeks
    └── No → Fundamental product rework → Do NOT scale
```

**"Which growth lever to focus on?"**
```
Retention curve stable?
├── No → Fix retention first (can't fill a leaky bucket)
└── Yes → Where is the biggest opportunity?
    ├── Low traffic → Acquisition (language + channel fit)
    ├── Low activation → Reduce friction to Aha Moment
    ├── Low monetization → Price/value optimization
    └── Flat growth despite all above → New channel + bold experiments
```

**"Is my viral loop working?"**
```
K factor measured?
├── K > 0.5 → Optimize payload and conversion (you're close)
├── K 0.1–0.5 → Focus on acceptance rate and frequency
└── K < 0.1 → Virality is not your lever; focus on retention + acquisition
```

---

## Measurement Principles

1. **Track the North Star** — not vanity metrics
2. **Use cohorts** — segment users by sign-up date, channel, behavior
3. **Integrate data sources** — web analytics + CRM + payment + support into one warehouse
4. **99% confidence level** — reduces false positives from 1-in-20 to 1-in-100
5. **When in doubt, keep the control** — tie goes to the incumbent
6. **Build dashboards** — make metrics visible, actionable, and shared across the org
7. **Pre-register hypotheses** — write the prediction before running the test
8. **Report all results** — including negative and inconclusive; they prevent repeated mistakes

---

## Master Checklist: Growth Readiness

### Phase 1: Foundation (Week 1–2)
- [ ] Indispensability survey run (≥300 responses)
- [ ] Result: ≥40% "very disappointed"
- [ ] Retention curve analyzed (8+ weeks of data)
- [ ] Aha Moment identified and measurable
- [ ] Growth equation defined
- [ ] North Star metric chosen

### Phase 2: Instrumentation (Week 2–3)
- [ ] All key events instrumented
- [ ] Data sources integrated into warehouse
- [ ] Cohort dashboard live
- [ ] Experiment tracking system set up (brief template, ICE scoring)

### Phase 3: Experiment Cadence (Week 3+)
- [ ] First weekly growth meeting held
- [ ] Idea backlog seeded (≥20 ideas)
- [ ] First 3 experiments launched
- [ ] Experiment velocity target set (e.g., 3–5/week)
- [ ] Win rate tracked (target: 20–30%)

### Phase 4: Scale What Works (Ongoing)
- [ ] Winning experiments rolled out to 100%
- [ ] Channel diversification plan (≥2 active channels)
- [ ] Viral loop instrumented (even if K < 1)
- [ ] Retention/reactivation campaigns running
- [ ] Quarterly price testing cadence
