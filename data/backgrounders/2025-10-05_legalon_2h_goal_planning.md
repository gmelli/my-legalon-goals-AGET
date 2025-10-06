# Legalon 2H FY2025 Goal Planning Context

**Date:** 2025-10-05
**Source:** Handoff from my-ccb-AGET
**Purpose:** Background context for structuring Gabor's 2H FY2025 goals in Rippling
**Managed by:** my-legalon-goals-AGET v2.5.1
**Owner:** Gabor Melli, VP of AI Engineering @ LegalOn

---

## Document Purpose

This backgrounder captures the context needed for 2H FY2025 goal planning. It connects:
- Historical performance (2H FY2024, 1H FY2025)
- Current state (1H goals with stale percentages)
- Emerging priorities (Playbook Agent, CRB engagement, 10-min review PoC, Contract DB, LOA analysis)
- Rippling system requirements (SMART goals, structural patterns, limits)

**Current priority:** 2H goal reporting (the crunch)

---

## Current State: 1H FY2025 Goals (as of Sep 30, 2025)

**CRITICAL NOTE:** Percentages are STALE - not regularly updated

1. **AI Review accuracy at >= 0.9 F1 for >= 90% of rules four contract types** (0%)
2. **GenAI Hiring** (0%) - MOSTLY COMPLETE: 2 DS hired ✓, NLP signed ✓, 2 AI Engineers pending
3. **MyPlaybook Agent used in production** (0%) - Actually "Playbook Agent", launching ~mid-Nov
4. **MyPlaybook benchmarked and accuracy increased** (0%)
5. **Thought leadership** (0%) - Too vague, needs SMART reformulation
6. **Improve product-market-fit in SMB and Enterprise segments (1-5k employees)** (0%)
7. **Maximize user value: with focus on improving customers' time savings** (7.41%)

---

## Historical Performance

### 2H FY2024: Product Market Fit (100% complete)
All 5 key results completed:
- Custom guidelines with AI revise ✓
- Increase accuracy of top 5 contracts by 10% ✓
- Trivium across all contracts ✓
- Implement reporting on KPIs (user engagement/satisfaction) ✓
- Cloud transition timeline on track ✓

### 2H FY2024: AI/Data Goals (39% complete)
Mixed results:
- LOA V3/V4 Development (50%) - Redline Summary ✓, Article Translation ✓
- Triviumize LLMs/Low Accuracy (25%)
- My Playbooks (20%)
- Hiring Goals (100%) - NLP Engineer hired ✓
- Presentations (0%) - Two external presentations NOT delivered

---

## 2H FY2025: Emerging Priorities

### New Data Infrastructure Goals
1. **Public Contract-Focused Database** - Clauses, templates, standardization
2. **LOA Session Analysis** - Drastically expanded analysis volume/depth
3. **User-Session Data Capture** - AI Revise + products (privacy/RTBF challenges)

### Continuing Projects
- **Playbook Agent** - Production launch ~mid-Nov (Q2 start → 2H completion)
- **AI Review Accuracy** - F1 >= 0.9 target continues?
- **Hiring** - 2 AI Engineers for potential SWAT team experiment

---

## Product Hierarchy

**Accuracy Umbrella:**
- AI Revise
- AI Review
- Playbook Agent (production ~mid Nov)

---

## Rippling Goals System - Structural Requirements

**Platform:** Rippling Goals app

**Timeline:**
- Update 1H goals: Now (October)
- Set 2H goals: October review cycle
- Manager alignment: Required

**Structure Options:**
- **Pattern A:** Flat - Simple key results under "[Your name]'s goals"
- **Pattern B:** Nested - Supporting goals with key results underneath
- **Hybrid:** Mix of both patterns

**SMART Framework:** Specific, Measurable, Achievable, Relevant, Time-Bound

**System Limits:**
- Max 5 goals
- Max 4-5 key results per goal
- "Uncomfortably ambitious" - not expecting 100% completion

**Visibility:** Goals visible to you + direct/indirect managers

---

## Key Achievements & Updates (NEW - 2025-10-05)

### ✅ AI Review Accuracy - ACHIEVED via Ancalagon
- **1H Goal:** "AI Review accuracy at >= 0.9 F1 for >= 90% of rules four contract types"
- **Status:** COMPLETED during 1H FY2025
- **Project:** Ancalagon - Custom LLM issue-spotting rule inference
- **Technology Shift:** Deprecated regex + ML (gradient boosted trees on TF-IDF) → Custom LLM approach
- **Implication:** Should be marked complete in 1H, not carried to 2H

### 🎯 Thought Leadership - Contract Review Benchmark (CRB)
- **1H Goal:** "Thought leadership (0%)" - was too vague
- **Current Status:** CRB nascently live, v2 complete (genai-ops repo, ~1 year development)
- **Branding:** "CRB" name created by Daniel (CEO) after GPT-5 announcement
- **Context:** Response to competitor benchmarks (e.g., Harvey's legal research benchmark)
- **2H Goal Nature:** NOT building from scratch - branding + external engagement
- **Purpose:** "PR spear" for Accuracy initiatives
- **Measurable:** Engagement (adoption/usage/awareness)
- **Still need:** Specific engagement targets and timeline

### ✅ Time Savings - 10-Minute Contract Review PoC
- **1H Goal:** "Maximize user value: with focus on improving customers' time savings (7.41%)"
- **1H Reality:** NOT achieved
- **2H Commitment:** 10-minute contract review Proof of Concept
- **Timeline:** Q3 demo (Jul-Sep 2H FY2025)
- **Mechanism:** Automated "Revise" button clicks on AI Review + MyPlaybook alerts
- **Success:** Working demo of 10-minute end-to-end review

## Key Challenges to Address

1. **Stale Percentages** - 1H goals show 0% but work has been done (hiring, Playbook Agent progress, Ancalagon completion)
2. **Vague Goals** - "Thought leadership" now defined as Contract Review Benchmark
3. **Naming Inconsistency** - "MyPlaybook Agent" vs "Playbook Agent"
4. **Missing Connections** - Goals not explicitly linked to product hierarchy
5. **New Priorities** - Contract DB, LOA analysis, user-session data need goal representation

---

## Open Questions

1. **AI Review F1 >= 0.9** - Still the right target for 2H?
2. **Thought Leadership** - What's the actual 2H deliverable? (Talk? Paper? Metric?)
3. **Time savings (7.41%)** - Real measure? Still relevant for 2H?
4. **SWAT team experiment** - New explicit 2H goal?
5. **Structure preference** - Pattern A (flat) vs B (nested) vs hybrid?
6. **Other product areas** - Beyond Accuracy/Data/Hiring?

---

---

## Agent Role & Document Map

**Agent:** my-legalon-goals-AGET v2.5.1
**Specialization:** Rippling goals lifecycle, SMART goal structuring, progress tracking, review reporting

**What I do:**
- Structure 2H FY2025 goals using hybrid pattern (product + theme based)
- Update 1H percentages to reflect actual work (no more 0% for completed work!)
- Connect goals to products (Accuracy umbrella, Data Infrastructure, Team Building)
- Generate review summaries with historical context and pattern analysis
- Document decisions and preserve context for future cycles

**Key Documents:**
- [Agent Vision/Mission/Goals](../goals/agent_vision_mission_goals.md) - My purpose and objectives
- [Capabilities](../../docs/capabilities.md) - Quick reference for what I do
- [1H FY2025 Rippling Goals (actual)](../goals/1h_fy2025_rippling_actual.md) - Current state in Rippling
- [2H Goal Structure Decisions](../../workspace/2h_goal_structure_decisions.md) - Decision tracking for 2H
- [Contract Review Benchmark](contract_review_benchmark.md) - CRB context

---

**Related Goals:** (to be linked when 2H goals finalized)
**Last Updated:** 2025-10-05
