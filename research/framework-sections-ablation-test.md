# Ablation Test: Archetypes / Three Time Horizons / Four-Way Pull

**Date:** 2026-05-12  
**Tester:** Hermes Agent (Claude Opus 4.6)  
**Purpose:** Determine whether the three framework sections present in every persona's Role Definition are necessary for AI agents to generate high-quality sales Call Plans.

---

## Sections Under Test

Each of the 19 CXO personas contains these three sections within "## 1. Role Definition":

1. **[Role] Archetypes (Postures, Not Industries)** — Diagnostic framework for identifying the executive's dominant decision posture
2. **The Three Time Horizons** — Framework for framing value across near/medium/long-term simultaneously
3. **The Four-Way Pull** — Framework for mapping competing stakeholder constituencies

Combined, these sections account for ~96 lines / ~16K characters per persona file (~18% of total content).

---

## Test Design

### Method
Three-way comparison using the same AI model (Claude Opus 4.6, 1M context) with identical sales scenarios:

| Condition | Description |
|-----------|-------------|
| **A — Full Persona** | Complete persona file with all sections |
| **B — Stripped Persona** | Same file with the 3 framework sections removed |
| **C — No Persona (Baseline)** | No reference material, general knowledge only |

### Scenarios Tested

**Scenario 1 (CFO):**  
Selling AI-powered financial close automation to the CFO of a top-5 global pharma ($50B+ revenue), post-$20B acquisition, facing CSRD Wave 1 deadlines.

**Scenario 2 (CTO):**  
Selling Kubernetes-based AI infrastructure to the CTO of a major US bank ($500B+ assets), with public "AI at scale" commitment, GPU procurement issues, SR 11-7 governance friction, and developer productivity challenges.

### Output Format
Each agent generated a Call Plan with:
1. Opening framing (first 90 seconds)
2. Key value propositions (3-4)
3. Top objection + handling
4. Closing ask

---

## Results

### Dimension-by-Dimension Comparison

| Dimension | Full (A/D) | Stripped (B/E) | Baseline (C) |
|-----------|:----------:|:--------------:|:------------:|
| Opens with dual time horizon | ✅ Explicit | ❌ Vague | ❌ Missing |
| Diagnoses executive archetype | ✅ "Transformation CFO + Strategic Co-Pilot" | ❌ Cannot diagnose | ❌ N/A |
| Multi-constituency positioning | ✅ "relieves 3 of 4 pulls" — explicit | 🟡 Implicit via other sections | ❌ Not addressed |
| Value prop precision | ⭐ Each VP maps to archetype's optimization target | 🟡 Reasonable but lacks "why this exec cares more" logic chain | 🟠 Generic, applicable to any company |
| Objection handling depth | ⭐ Structured, references persona's objection taxonomy | 🟡 Reasonable, relies on general sales knowledge | 🟠 Standard template |
| Opening gravitas (CXO-level) | ⭐ Sounds like a trusted advisor | 🟡 Sounds like a good vendor | 🟠 Sounds like a cold pitch |

### Quality Rating (subjective, 1-10)

| Condition | CFO Scenario | CTO Scenario | Average |
|-----------|:------------:|:------------:|:-------:|
| Full Persona | 9/10 | 9/10 | **9.0** |
| Stripped Persona | 7/10 | 7/10 | **7.0** |
| No Persona | 5.5/10 | — | **5.5** |

---

## Analysis: Value of Each Section

### 1. Archetypes — ⭐⭐⭐ (Highest Value)

**What it enables:**
- The agent can *diagnose* the executive's dominant posture before generating the plan
- All downstream language (opening, VPs, objection handling, close) is calibrated to the archetype
- Without it, the agent produces generically correct but undifferentiated output

**Example difference:**
- Full: *"Archetype Diagnosis: Transformation CFO + Strategic Co-Pilot blend. Post-$20B acquisition signals integration pressure..."* → pitch is calibrated
- Stripped: Opens with pain points but cannot explain *why* this CFO will respond to this framing over another

**Verdict:** Essential. This is the "tuning fork" for the entire Call Plan.

### 2. Three Time Horizons — ⭐⭐ (High Value)

**What it enables:**
- The agent explicitly names near-term AND medium/long-term outcomes in the opening 90 seconds
- Creates the "two-horizon sentence" that signals to the executive: "this vendor understands my seat"
- Provides the template: *"In the next two quarters this moves [X]; over the next [N] years it compounds into [Y]"*

**Example difference:**
- Full: *"In the next two quarters this frees capacity for integration work; over the next 18 months it compounds into a finance cost-to-revenue ratio reflecting your synergy targets"*
- Stripped: *"We work with pharma CFOs navigating exactly this intersection"* — correct but lacks the structural dual-horizon framing

**Verdict:** High value. The difference is especially noticeable in the opening — which is the most critical 90 seconds.

### 3. Four-Way Pull — ⭐ (Moderate Value)

**What it enables:**
- Explicit multi-stakeholder framing: "relieves board + investors + finance team"
- Helps the agent avoid single-constituency pitches that get delegated downward
- Provides the anti-pattern warning: don't frame around only one axis

**Example difference:**
- Full: Explicitly states which constituencies are relieved and why
- Stripped: Implicitly covers multiple stakeholders through Priorities and Pain Points sections, but doesn't frame it as a strategic positioning choice

**Verdict:** Moderate value. The stripped version can still address multiple stakeholders through other sections (Priorities, Pain Points), but does so implicitly rather than as a deliberate framing strategy. The Four-Way Pull's unique contribution is teaching the agent to *lead with the multi-constituency relief* as a positioning move.

---

## Conclusions & Recommendations

### Keep All Three Sections ✅

The three sections together lift output quality from 7/10 to 9/10. That delta — especially concentrated in the opening 90 seconds and the strategic positioning — is significant for CXO-level engagements where the first impression determines whether the meeting continues or gets delegated down.

### Optimization Options (if token budget matters)

| Option | Trade-off |
|--------|-----------|
| **Keep as-is** (embedded in each persona) | Best for small-context models that load one persona at a time. Redundancy is intentional per the design note in each file. |
| **Extract to shared framework file** | Saves ~16K chars × 18 = ~288K chars across non-CEO personas. Load persona + framework on demand. Risk: agents with limited context may skip the framework file. |
| **Compress to summary tables** | Reduce prose by 60% while keeping diagnostic tables and field rules. Loses examples but keeps actionable structure. |

### Recommended Approach

For models with 200K+ context: **keep as-is**. The redundancy cost (~16K/persona) is negligible against a 1M token window, and the self-contained design ensures any single persona works in isolation.

For models with <32K context: consider extracting the three frameworks into a shared `references/FRAMEWORKS.md` and referencing it from each persona with a one-line pointer.

---

## Appendix: Raw Test Outputs

### TEST A — Full CFO Persona (Score: 9/10)

**Opening:** *"I know you're in the middle of the most complex integration your finance organization has ever run — consolidating entities, harmonizing chart of accounts, and delivering synergy commitments to the board — while simultaneously standing up CSRD Wave 1 disclosures on a fixed regulatory clock. That's two transformation programs competing for the same finance-team hours. We help pharma CFOs compress the close cycle by 40–60% post-acquisition — which in the next two quarters frees the capacity your Controller's team needs for integration work and CSRD data collection, and over the next 18 months compounds into a finance cost-to-revenue ratio that reflects the synergy targets you've committed to investors."*

**Notable features:** Dual-horizon opening, archetype diagnosis (Transformation + Strategic Co-Pilot), explicit four-pull relief (board synergy narrative + investor margin + finance-team capacity), phased close with bounded risk.

---

### TEST B — Stripped CFO Persona (Score: 7/10)

**Opening:** *"I know you're managing a complex integration on a $20B+ acquisition while simultaneously preparing for CSRD Wave 1 reporting — both hitting your finance team at the same time. We work with pharma CFOs navigating exactly this intersection..."*

**Notable features:** Correct pain-point identification, reasonable VPs, adequate objection handling. Missing: archetype diagnosis, explicit time-horizon framing, multi-constituency positioning.

---

### TEST C — No Persona Baseline (Score: 5.5/10)

**Opening:** *"I know you're navigating an incredibly demanding period—integrating a $20 billion acquisition while delivering synergy commitments to the Street..."*

**Notable features:** Generic but competent. Could apply to any CFO at any pharma. No differentiation based on the specific executive's posture, priorities, or political context.

---

### TEST D — Full CTO Persona (Score: 9/10)

**Opening:** *"You told the market you're deploying AI at scale. That commitment now lives in three engineering realities simultaneously: in the current quarter, your teams are bottlenecked on GPU capacity... Through your next architecture cycle, you need a platform that lets 500+ developers ship AI workloads... And the next-generation bet is whether your AI platform becomes the foundation for thousands of models..."*

**Notable features:** Three-horizon framing explicitly adapted to CTO language (sprint/architecture cycle/platform generation), archetype diagnosis (Enterprise CTO + Transformer), four-pull mapped to CTO constituencies (velocity/reliability/cost/security).

---

### TEST E — Stripped CTO Persona (Score: 7/10)

**Opening:** *"What we're hearing from CTOs at top-10 banks is three things colliding at once: GPU capacity is constrained, SR 11-7 model governance is adding weeks to every deployment cycle, and developer productivity on AI workloads is 3-4x slower..."*

**Notable features:** Strong pain-point enumeration from Priorities/Pain Points sections. Missing: explicit time-horizon structure, archetype-based calibration, constituency-relief framing as a positioning strategy.

---

*End of test report.*
