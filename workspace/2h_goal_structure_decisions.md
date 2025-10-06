# 2H FY2025 Goal Structure - Decision Tracking

**Date:** 2025-10-05
**Status:** In progress - gathering clarifications

---

## Confirmed Decisions

### ✅ Q5: Goal Structure Pattern
**Decision:** HYBRID (Pattern A + B combo)
- Mix of product-based and theme-based organization
- "Clearly a combo" approach
- Final structure will be determined after all clarifying questions answered

### ✅ Q6: Product Coverage (Partial)
**Decision:** Three confirmed areas
1. **Accuracy Umbrella:** AI Revise, AI Review, Playbook Agent
2. **Data Infrastructure:** Contract DB, LOA analysis, user-session data
3. **Team Building:** AI Engineers, SWAT experiment

### ✅ Q4: SWAT Team Experiment
**Answer:** Implicit - part of US development team that Gabor supports

**Details:**
- **Team structure:** 2 AI Engineers (agent dev) + 2 Software Engineers = 4 person team
- **Purpose:** "Experiment if a swat team can get things done faster"
- **Gabor's role:** Supporting the US dev team
- **Implication:** NOT a direct goal for Gabor, but enabling/support activity
- **Goal treatment:** Implicit in "Team Building" or "Support US dev team" context

---

## Answered Questions

### ✅ Q1: AI Review Accuracy Target
**Answer:** NO - Already achieved in 1H via Ancalagon project

**Details:**
- F1 >= 0.9 target was met during 1H FY2025
- **Ancalagon project:** Custom LLM issue-spotting rule inference
- **Deprecated approach:** Regular expression + ML (gradient boosted trees on TF-IDF)
- **Implication:** This should be marked as COMPLETED in 1H, not carried forward to 2H

### ✅ Q2: Thought Leadership Deliverable
**Answer:** Contract Review Benchmark (CRB) + Engagement metrics

**Current Status:**
- **Development:** Nascently live, v2 complete
- **Team:** GenAI team developing in `genai-ops` repo for ~1 year
- **Branding:** "CRB" moniker created by Daniel (CEO) after GPT-5 announcement
- **Strategic context:** Response to competitor benchmarks (e.g., Harvey's legal research benchmark)
- **Goal nature:** NOT building from scratch - this is branding + external engagement of existing tool

**What is CRB:**
- **Purpose:** LegalOn's practical yardstick for testing AI performance on real contract work
- **Four workflows tested:**
  1. Conversational assistance (Q&A and summaries)
  2. Policy and standards checks
  3. Customer playbook enforcement
  4. Minimal-diff redlining (preserves definitions, numbering, cross-refs)
- **Test materials:** Mix of public, custom, anonymized contracts (English + Japanese)

**Quality Metrics:**
- **Classification tasks:** Accuracy, precision, recall, F1
- **Generative edits:** Edit integrity, formatting fidelity, time to decision
- **Human review:** Attorney reviewers create gold answers, adjudicate in pairs
- **Traceability:** Source text, prompt version, diff logs

**Strategic Value:**
- "PR spear" for Accuracy initiatives
- Shows in-house counsel where AI is ready, where human needed
- Helps buyers compare tools fairly and plan deployments
- Living benchmark: Updates as models/workflows change

**For SMART goal - still need:**
- Engagement target: What defines success? (X prospects using it? Y pilot decisions influenced? Z publications/presentations?)
- Timeline: When are engagement results measured in 2H?

### ✅ Q3: Time Savings Metric
**Answer:** 10-Minute Contract Review PoC - Demo in Q3

**SMART Goal Definition:**
- **Specific:** Proof of Concept for 10-minute end-to-end contract review
- **Measurable:** Working demo
- **Achievable:** Scoped to PoC, not production
- **Relevant:** Core to LegalOn's value proposition (time savings)
- **Time-bound:** Q3 demo (2H FY2025)

**Mechanism:**
- Click all 'Revise' buttons on issue-spotting alerts
  - LegalOn AI Review (expert-crafted rules)
  - MyPlaybook (user-created rules)
- Automated revisions reduce review time dramatically

**Current Status:**
- **1H goal:** "Achievable for some contracts"
- **1H reality:** NOT yet achieved
- **2H commitment:** PoC demonstration

**Success Criteria for PoC:**
- Demo shows 10-minute review from start to finish
- Uses real contract (or representative sample)
- Showcases AI Review + MyPlaybook integration
- Timeline: Q3 (Jul-Sep in FY2025 2H)

---

## Next Steps

1. Get answers to Q1, Q2, Q3
2. Finalize Q4 (explicit goal or not?)
3. Draft 2H goal structure using hybrid pattern
4. Apply SMART criteria to all goals
5. Check Rippling limits (max 5 goals, 4-5 key results each)
6. Manager alignment

---

**Related Files:**
- [agent_vision_mission_goals.md](../data/goals/agent_vision_mission_goals.md)
- [2025-10-05_legalon_2h_goal_planning.md](../data/backgrounders/2025-10-05_legalon_2h_goal_planning.md)

**Last Updated:** 2025-10-05
