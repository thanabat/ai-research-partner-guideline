# Example — Secondary Research (abridged)

> A fictional worked example showing what a filled-in desk research project looks like. It only covers the sections that matter most for getting oriented — Project Setup, the Evidence Repository, Synthesis, and Evidence Gaps. Your real project should fill in only what its Research Depth requires (see the template's "Suggested Execution by Research Depth" table) — this is just here so a blank template doesn't feel like a blank page. This example uses **Deep** depth, which is why it separates Source and Evidence repositories rather than using the default lean table.

---

# 01 — Project Setup

**Project Name:** Subscription Delivery Landscape Review  
**Research Topic:** How grocery delivery subscription models retain customers  
**Research Owner:** Nat (UX Researcher)  
**Stakeholders:** Product Manager (Retention), Growth Lead  
**Research Depth:** Deep — this decision affects a paid launch, so we wanted stronger auditability  
**Status:** Synthesis  
**Last Updated:** 2026-08-14

## Background
The team is considering launching a paid delivery subscription. Before running primary research, we want to understand what's already known about how similar subscriptions retain (or lose) customers.

## Research Goal
Understand what drives subscription retention and churn in grocery/food delivery, to inform whether — and how — GreenCart should launch one.

## Decisions This Research Should Inform
- Whether to launch a subscription tier
- What retention levers are worth testing with our own users first

## Out of Scope
- Pricing strategy specifics
- Legal/regulatory considerations

## Existing Knowledge / Assumptions
- [Assumption] The team believes free delivery is the main draw of subscriptions
- [Assumption] The team believes churn mostly happens in month 1

> Existing assumptions are context, not research evidence.

---

# 06 — Evidence Repository & Analysis (excerpt, Deep Research Repository)

### Source Repository

| Source ID | Source | Source Type | Date | Relevant RQ | Reliability / Limitation Notes |
|---|---|---|---|---|---|
| S01 | Industry report on delivery subscription churn (market research firm) | Independent | 2025 | RQ1 | Aggregated across US market; may not reflect other regions |
| S02 | Competitor's public "why customers cancel" blog post | Official / Platform | 2025 | RQ1 | Self-reported by the company; likely frames their own product favorably |
| S03 | Academic paper on subscription commitment psychology | Academic | 2023 | RQ2 | Not delivery-specific; general subscription behavior |

### Evidence Repository

| Evidence ID | Source ID | Research Question | Evidence | Evidence Type | Context / Limitation | Researcher Note |
|---|---|---|---|---|---|---|
| E01 | S01 | RQ1 | Most cancellations happen in the first 30 days, not gradually over time | Independent | US market only | Supports "month 1 is critical" assumption — but with actual data behind it |
| E02 | S02 | RQ1 | Company claims their top cancellation reason is "didn't use it enough" | Official / Platform Claim | Published as a marketing "lessons learned" post, not a data disclosure | Self-reported — may omit reasons unflattering to the company (price, bugs); useful as a hypothesis, not confirmed fact |
| E03 | S03 | RQ2 | Users commit more strongly to subscriptions when they've made an active choice (vs. auto-enrolled) | Academic | Not delivery-specific | General psychology finding — treat as a hypothesis to test, not a delivery fact |

---

# 07 — Synthesis & Key Findings (excerpt)

## Finding — Early Churn Window

### Evidence Pattern
Independent benchmark data (E01) shows cancellations concentrate in the first 30 days rather than being spread evenly over the subscription lifetime.

### Interpretation
Whatever value a subscription delivers, customers seem to decide quickly whether it's worth keeping — early experience likely matters more than long-term engagement features.

### Research-backed Insight
Grocery delivery subscriptions tend to lose customers early, within the first month, rather than through gradual disengagement.

### Supporting Evidence
- E01

### Counter-evidence / Variation
- E02 (a platform claim from the same company) frames cancellation as being about underuse rather than timing — these aren't necessarily contradictory, but E02 doesn't confirm *when* underuse-driven cancellations happen, so it can't be used to strengthen or weaken the timing claim.

### Evidence Strength
**Moderate**

### Evidence Strength Rationale
- Source quality: independent market research firm, reasonably credible
- Source independence: single source — no second independent source cross-confirms the exact 30-day figure
- Recency: 2025, recent enough
- Context relevance: US market, not our specific market — a real transfer risk

> Evidence Strength reflects how defensible the conclusion is, not how important the topic is.

---

# 10 — Evidence Gaps & Validation Required (excerpt)

## Gap — Does Early Churn Apply to GreenCart's Market?

**What Existing Evidence Supports:**  
Early (first-30-day) churn is a documented pattern in the US grocery delivery subscription market.

**What Existing Evidence Does NOT Confirm:**  
Whether the same pattern holds in GreenCart's market, or for GreenCart's specific customer base.

**Context Transfer Risk:**  
Market research is US-only; delivery subscription behavior may differ by region, existing habits, or price sensitivity.

**Evidence Status:**  
Research-informed Hypothesis

**Recommended Next Step:**  
Primary Research — if GreenCart launches a subscription pilot, track cancellation timing directly rather than assuming the US pattern transfers.

---

## Golden Rule check

Notice what this example does *not* do:
- It doesn't treat the competitor's self-reported blog post (E02, an **Official / Platform Claim**) as equally credible to the independent benchmark report (E01) — the two evidence types are kept visibly separate rather than both being labeled generically "evidence."
- It doesn't let a general psychology paper (E03) masquerade as a delivery-specific fact — it's explicitly flagged as a hypothesis to test.
- It doesn't assume the US benchmark automatically applies to GreenCart's market — that gap is named directly rather than quietly assumed away.
- Evidence Strength is "Moderate," not "Strong," specifically because there's only one independent source for the core claim — the rationale says why, rather than just asserting a label.
- It uses the Deep repository (separate Source + Evidence tables) because the decision — a paid subscription launch — is high-stakes enough to warrant it, not by default. A Rapid-depth version of this same question would use one lean table instead.
