# Example — Primary Research (abridged)

> A fictional worked example showing what a filled-in project looks like. It only covers the sections that matter most for getting oriented — Project Setup, Observation Capture, Clustering, Synthesis, and one Recommendation Detail. Your real project should fill in every section of [`primary-research-template.md`](../templates/primary-research-template.md); this is just here so a blank template doesn't feel like a blank page.

---

## 00 — Project Setup

**Project Name:** Checkout Delivery Slot Research  
**Product / Service:** GreenCart grocery delivery app  
**Research Owner:** Nat (UX Researcher)  
**Stakeholders:** Product Manager (Checkout), Logistics Lead  
**Status:** Synthesis  
**Last Updated:** 2026-08-10

### Background
Support tickets show a spike in complaints about missed delivery windows. The team suspects the delivery slot picker at checkout is confusing, but no one has watched users actually use it.

### Research Goal
Understand how customers choose a delivery slot at checkout, and where the current picker breaks down.

### Decisions This Research Should Inform
- Whether to redesign the delivery slot picker UI
- Whether "fastest available" should be the default selection

### Out of Scope
- Delivery pricing
- Rider-side logistics UX

---

## 03 — Research Execution (excerpt)

### Observation Capture

| Participant | Context / Task | Observation | Quote / Evidence | Initial Note |
|---|---|---|---|---|
| P01 | Choosing a slot for a weekday order | Scrolled past the first 3 slots without reading them | "I just want the soonest one, why do I have to scroll" | Wants fastest option surfaced, not buried |
| P02 | Same task | Selected a slot, then reopened the picker to double check | "I wasn't sure if I'd actually locked it in" | Confirmation state unclear |
| P03 | Same task | Picked a slot 2 days out on purpose | "I'm not home till Thursday anyway" | Not everyone wants the fastest slot — context-dependent |
| P04 | Same task | Missed that slots were grouped by day | "Oh wait, these are different days?" | Day grouping isn't visually distinct enough |
| P05 | Same task | Same as P02 — reopened picker after selecting | "Did that save?" | Second instance of confirmation doubt |

---

## 05 — Clustering (excerpt)

### Cluster — Selection Confirmation Doubt

**Scope:**  
Users are unsure whether their delivery slot selection was actually saved.

**Observations:**
- P02 reopened the picker to check
- P05 reopened the picker to check

**Supporting Participants:**  
P02, P05

**Contradicting / Different Evidence:**
- None observed

**Positive Evidence / Preserve:**
- The slot list itself (once found) was easy to scan

**Participant Suggestions:**
- P05 suggested "maybe show a checkmark or something"

---

## 06 — Synthesis (excerpt)

### Observation Pattern
2 of 5 participants reopened the delivery slot picker after making a selection, unprompted, to verify it had been saved.

### Interpretation
The picker likely lacks a clear confirmed state once a slot is chosen, so users fall back to re-checking manually.

### Actionable Insight
Customers should be able to tell at a glance that their delivery slot selection was saved, without needing to reopen the picker.

### Supporting Evidence
- P02, P05 observations

### Counter Evidence / Variation
- P01, P03, P04 did not reopen the picker — but their sessions also didn't include a distraction or delay between selecting and checking out, so this may under-represent the issue in real-world use

### Confidence
**Medium**

**Rationale:**  
Consistent behavior in 2 of 5 sessions is a real pattern, but the sample is small and the lab setting may not fully replicate real-world distractions that would make this worse (or interruptions that make people re-check more).

---

## 11 — Recommendation Detail (excerpt)

### Recommendation Detail — Visible Slot Confirmation

**Actionable Insight:**  
Customers should be able to tell at a glance that their delivery slot selection was saved.

**Why It Matters / Supporting Rationale:**  
Confirmation doubt adds friction right before checkout completion, a high-drop-off point.

**Recommended Direction:**  
Surface a clear, persistent confirmation once a slot is selected — without requiring the user to reopen the picker.

**Specific Recommendation:**
- Show selected slot as a summary line above the "Place Order" button
- Consider a brief inline confirmation (e.g. checkmark animation) at the moment of selection

**Recommendation Type:**  
Improvement

**Confidence:**  
Medium

**Decision Status:**  
To Discuss

---

## Golden Rule check

Notice what this example does *not* do:
- It doesn't turn P05's "maybe show a checkmark" into a locked requirement — it stays a suggestion feeding a direction, not the direction itself.
- It doesn't claim all users are confused — P01/P03/P04 didn't show this behavior, and that's recorded, not hidden.
- Confidence is "Medium" because the sample is small — not "High" just because the finding feels important.
