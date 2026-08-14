# Example — Secondary Research (abridged)

> A fictional worked example showing what a filled-in desk research project looks like. It only covers the sections that matter most for getting oriented — Project Setup, Source Repository, Evidence Capture, Clustering, and Synthesis. Your real project should fill in every section of [`secondary-research-template.md`](../templates/secondary-research-template.md); this is just here so a blank template doesn't feel like a blank page.

---

# 01 — Project Setup

**Project Name:** Subscription Delivery Landscape Review  
**Research Topic:** How grocery delivery subscription models retain customers  
**Research Owner:** Nat (UX Researcher)  
**Stakeholders:** Product Manager (Retention), Growth Lead  
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

# 04 — Source Repository

| Source ID | Source | Source Type | Date | Relevant RQ | Reliability / Limitation Notes |
|---|---|---|---|---|---|
| S01 | Industry report on delivery subscription churn (market research firm) | Independent | 2025 | RQ1 | Aggregated across US market; may not reflect other regions |
| S02 | Competitor's public "why customers cancel" blog post | First-party | 2025 | RQ1 | Self-reported by the company; likely frames their own product favorably |
| S03 | Academic paper on subscription commitment psychology | Academic | 2023 | RQ2 | Not delivery-specific; general subscription behavior |

## Source Record — S01

**Title:** Grocery Delivery Subscriptions: Retention Benchmarks  
**Author / Organization:** [Market Research Firm]  
**Published:** 2025  
**Source Type:** Independent  
**Accessed:** 2026-08-05

**Relevant Research Question(s):** RQ1

**Why This Source Matters:**  
Provides benchmark churn rates across multiple competitors, not just one company's self-reported numbers.

**Important Limitations:**  
US-only data; GreenCart operates in a different market, so numbers may not transfer directly.

---

# 05 — Evidence Capture & Classification (excerpt)

## 5.2 Evidence Repository

| Evidence ID | Source ID | Research Question | Evidence | Evidence Type | Initial Note |
|---|---|---|---|---|---|
| E01 | S01 | RQ1 | Most cancellations happen in the first 30 days, not gradually over time | Independent | Supports "month 1 is critical" assumption — but with actual data behind it |
| E02 | S02 | RQ1 | Company claims their top cancellation reason is "didn't use it enough" | First-party | Self-reported — may omit reasons unflattering to the company (e.g. price, bugs) |
| E03 | S03 | RQ2 | Users commit more strongly to subscriptions when they've made an active choice (vs. auto-enrolled) | Academic | Not delivery-specific — a general psychology finding, treat as a hypothesis to test, not a delivery fact |

## Evidence Record — E02

**Source:** S02

**Evidence:**  
Competitor blog post states their #1 self-reported cancellation reason is "didn't use it enough."

**Context:**  
Published as part of a "lessons learned" marketing post, not a data disclosure.

**Evidence Classification:**  
First-party

**Supports:**  
RQ1 — what drives cancellation

**Limitations / Caveats:**  
First-party source describing their own churn reasons — likely omits reasons that reflect poorly on the product itself (price, reliability, bugs). Should not be treated as independently validated.

**Researcher Note:**  
Useful as a hypothesis to check against our own future data, not as confirmed fact.

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
- E02 (first-party, same company) frames cancellation as being about underuse rather than timing — these aren't necessarily contradictory, but E02 doesn't confirm *when* underuse-driven cancellations happen, so it can't be used to strengthen or weaken the timing claim.

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
- It doesn't treat the competitor's self-reported blog post (E02) as equally credible to the independent benchmark report (E01) — first-party and independent evidence are kept visibly separate.
- It doesn't let a general psychology paper (E03) masquerade as a delivery-specific fact — it's explicitly flagged as a hypothesis to test.
- It doesn't assume the US benchmark automatically applies to GreenCart's market — that gap is named directly rather than quietly assumed away.
- Evidence Strength is "Moderate," not "Strong," specifically because there's only one independent source for the core claim — the rationale says why, rather than just asserting a label.
