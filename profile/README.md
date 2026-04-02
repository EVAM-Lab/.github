# EVAM Lab

**Ancient logic. Modern AI. Built to know what it doesn't know.**

We build neuro-symbolic AI systems grounded in Buddhist formal logic — implementing 1,500-year-old epistemological frameworks as rigorous ML infrastructure.

This is a verification layer for AI classifiers and LLMs that rejects out-of-distribution inputs and flags hallucinations.


---

## What We're Building

**BUDDHI** — Buddhist Understanding through Dual Deep-symbolic Hybrid Intelligence.

A verification stack for neural AI, phase by phase:

| Phase | Module | Concept | Status |
|-------|--------|---------|--------|
| **A** | [Apoha] | Exclusion-based classification with principled OOD rejection | **Live** |
| B | Hetuchakra | Formal verification gate for LLM outputs | In progress |

---

## Phase A: Apoha — Live Now

A classifier that defines concepts by **what they exclude**, not what they include.
Inspired by Dignāga's *anyāpoha-vāda* (c. 480–540 CE).

When an input doesn't clearly belong anywhere → the model says **UNCERTAIN**.
Not a guess. Not a hallucination. A principled refusal to classify.

**Results (5 seeds, 6 benchmarks):**
- CLINC150: **5.6× better OOD rejection** than contrastive baselines (84.6% vs 15.1%)
- Banking77: contrastive baselines reject **0%** of OOD. Apoha rejects **29%**.
- HWU64: **166× better** OOD rejection than InfoNCE

---

## Philosophy

Buddhist epistemology (*pramāṇavāda*) spent 1,500 years developing rigorous frameworks for valid cognition — what counts as knowledge, what counts as inference, and crucially, when to withhold judgment.

These are not metaphors. Dignāga's exclusion theory maps onto hard-negative mining. Dharmakīrti's refinements map onto smooth-min loss functions. The Hetuchakra maps onto formal argument verification. We are implementing the logic, not borrowing the aesthetics.

> *"A concept is not defined by what it includes, but by what it excludes."*
> — Dignāga, *Pramāṇasamuccaya* (c. 480–540 CE)
