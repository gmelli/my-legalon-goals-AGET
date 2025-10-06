# Contract Review Benchmark (CRB)

**Created:** 2025-10-05
**Purpose:** Reference document for CRB initiative - LegalOn's "PR spear" for Accuracy

---

## What is CRB?

The Contract Review Benchmark (CRB) is LegalOn's practical yardstick for testing how AI performs on real contract work.

**Core purpose:** Give in-house counsel clear evidence about:
- Where AI is ready
- Where a human must stay in the loop
- What to measure in pilots

---

## Four Workflows Tested

1. **Conversational Assistance** - Q&A and summaries
2. **Policy and Standards Checks** - Compliance verification
3. **Customer Playbook Enforcement** - Custom guidelines application
4. **Minimal-Diff Redlining** - Preserves definitions, numbering, cross-references

---

## Test Materials

**Contract mix:**
- Public contracts
- Custom contracts
- Anonymized contracts

**Languages:**
- English
- Japanese

**Paired with:**
- Prompts that mirror day-to-day review
- Expected outcomes

---

## Quality Metrics

### Classification Tasks
- Accuracy
- Precision
- Recall
- F1 score

### Generative Edits
- Edit integrity
- Formatting fidelity
- Time to decision

---

## Human Review Protocol

**Gold standard creation:**
- Attorney reviewers create gold answers
- Results adjudicated in pairs
- Third attorney or model used ONLY for pairwise preferences
- NEVER used to declare legal correctness

**Traceability:**
- Every score tied to source text
- Prompt version tracked
- Diff logs maintained
- Results are auditable

---

## Strategic Value

**Marketing/PR:**
- "PR spear" for Accuracy initiatives
- Demonstrates AI readiness to prospects
- Builds buyer confidence

**Competitive positioning:**
- Helps buyers compare tools fairly
- Provides objective performance data
- Supports pilot planning

**Product evolution:**
- Living benchmark
- Updates as models change
- Updates as workflows evolve
- Continuous relevance

---

## Connection to Product Hierarchy

**Accuracy Umbrella:**
- AI Revise
- AI Review
- Playbook Agent

CRB validates and promotes all three products through objective, traceable performance data.

---

## Development History

**Timeline:**
- **~2024:** GenAI team begins development in `genai-ops` repo
- **Recently:** Upgraded to v2
- **Current status:** Nascently live

**Branding evolution:**
- Original: Internal benchmarking tool
- **New (2025):** "Contract Review Benchmark" branding by Daniel (CEO)
- **Trigger:** GPT-5 announcement + competitor benchmarks (e.g., Harvey's legal research benchmark)
- **Strategic shift:** Internal tool → External PR/positioning asset

---

## 2H FY2025 Goal Considerations

**What's defined:**
- **Product status:** Nascently live, v2 complete
- **Goal type:** NOT building from scratch - this is branding + external engagement
- **Purpose:** PR/marketing tool for Accuracy (competitive positioning)
- **Measurable:** Engagement metrics

**What's needed for SMART goal:**
- Engagement target (prospects using it? Pilot decisions influenced? Publications/presentations?)
- Success criteria for "thought leadership"
- Timeline for measuring impact

**Key insight:**
This is about **positioning existing work** as thought leadership, not building new functionality.

---

**Related Goals:** (to be linked)
**Related Projects:** genai-ops repo
**Last Updated:** 2025-10-05
