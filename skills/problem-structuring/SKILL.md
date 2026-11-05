---
name: problem-structuring
description: Structure an ambiguous business problem the way strategy consultants do, with a SMART problem statement, a MECE issue tree, hypotheses, and a workplan. Use when the user faces a vague business question ("why are sales falling?", "should we expand?"), asks for an issue tree, logic tree, MECE breakdown, hypothesis tree, problem statement, SCQ, or "how would a consultant approach this?"
---

# Problem Structuring

Turn a fuzzy question into a precise problem, a MECE breakdown, and a hypothesis-driven plan. Every other strategy skill builds on this one.

## Step 1: Define the problem precisely

Write a problem statement that is **SMART**: Specific, Measurable, Action-oriented, Relevant, Time-bound.

- ❌ "Improve profitability."
- ✅ "How can RetailCo raise EBITDA margin from 6% to 9% within 24 months without cutting store count by more than 10%?"

Capture the context with a **problem definition worksheet**:
- **Key decision maker:** who owns the answer?
- **Success criteria:** what does a good outcome look like, in numbers?
- **Scope:** what's in and out (geographies, business units, levers)?
- **Constraints:** budget, time, things that can't change.
- **Stakeholders:** whose buy-in is needed?

## Step 2: Frame it as Situation, Complication, Question (SCQ)

- **Situation:** the stable context that everyone agrees on.
- **Complication:** what changed or what threatens the situation.
- **Question:** the key question that follows from the complication. This becomes the root of the tree.

## Step 3: Build a MECE issue tree

MECE means **Mutually Exclusive** (no overlaps between branches) and **Collectively Exhaustive** (nothing left out).

Choose the tree type:
- **Diagnostic (why) tree:** breaks down the reasons a problem exists. Use it when the root cause is unknown.
- **Solution (how) tree:** breaks down the ways to achieve a goal. Use it when the cause is known and options are needed.

Prefer splits that are MECE by construction:
- **Math:** Profit = Revenue − Cost; Revenue = Volume × Price.
- **Process or value chain stages:** sourcing → production → distribution → sales.
- **Segments:** customer type, geography, product, channel.
- **Opposing pairs:** internal vs. external, new vs. existing, short-term vs. long-term.

Rules:
- Go 3–4 levels deep at most; stop when a branch can be tested with analysis.
- Each level should have 2–5 branches.
- Test MECE-ness explicitly: "Could any item fall into two branches? Is any plausible cause missing?"

Render the tree as an indented list or an ASCII tree:
```
Why has RetailCo's EBITDA margin fallen from 9% to 6%?
├── Revenue per store has fallen
│   ├── Traffic is down (fewer visits)
│   └── Basket size is down (lower spend per visit)
│       ├── Fewer items per basket
│       └── Lower price per item (mix shift, discounting)
└── Costs per store have risen
    ├── COGS up (supplier prices, shrinkage)
    └── Opex up (labor, rent, marketing)
```

## Step 4: Go hypothesis-driven

Don't boil the ocean. For the most likely branches, state a **falsifiable hypothesis** and the analysis that would prove or disprove it:

| Hypothesis | Analysis to test it | Data needed | Source | Owner / timing |
|-----------|---------------------|-------------|--------|----------------|
| Basket size fell because of heavier promotional discounting | Price-per-item trend vs. promo calendar, 2023–2025 | POS transaction data | Client BI team | Week 1 |

Prioritize branches by **impact × ease of testing**. Use the 80/20 rule and pursue the 2–3 branches likely to explain most of the gap.

## Step 5: Output

```markdown
## Problem statement
## SCQ
## Issue tree
## Priority hypotheses & workplan (table)
## Initial "answer first" (Day 1 hypothesis), stated as a one-sentence recommendation to be tested
```

## Quality bar
- The root question is a single question, not a compound one.
- Every branch is phrased as a question or a testable statement, not a topic label.
- There is a Day 1 hypothesis. Consultants start with a best guess and work to prove or kill it.
- Flag explicitly where the tree isn't fully MECE and why that's acceptable.
