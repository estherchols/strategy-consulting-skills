---
name: profitability-analysis
description: Diagnose why a company, business unit, or product's profits are declining (or how to raise them) using a profit tree, segmentation, benchmarking, and a prioritized set of revenue and cost levers. Use when the user asks why profits or margins fell, how to improve profitability, for a cost reduction or pricing analysis, unit economics, or a profitability case.
---

# Profitability Analysis

Find where profit is being lost and which levers will recover it, quantified wherever possible.

## Step 1: Frame the problem
- What metric is it (profit, EBITDA, operating margin, contribution margin), what's the gap, and over what period?
- Is the problem company-specific or industry-wide? Ask for or look up competitor and industry trends early. This one question often splits the case.

## Step 2: Decompose with the profit tree

```
Profit
├── Revenue
│   ├── Volume (# units / customers)
│   │   ├── Market size / growth
│   │   └── Market share
│   └── Price (avg. realized price)
│       ├── List price
│       ├── Discounts / promotions
│       └── Mix (product, customer, channel)
└── Costs
    ├── Variable costs (per unit: materials, direct labor, shipping, commissions)
    └── Fixed costs (rent, salaries, SG&A, D&A)
```

Add other revenue streams (services, subscriptions, ancillary) as separate branches when relevant.

## Step 3: Locate the problem
Work top-down and quantify at each level:
1. **Trend:** which line moved, by how much, and since when? Use a profit bridge (waterfall): Profit last year → Δ volume → Δ price → Δ mix → Δ variable cost → Δ fixed cost → Profit this year.
2. **Segment:** break the moving line down by product, customer, region, and channel. Problems usually concentrate in one segment.
3. **Benchmark:** compare against competitors, internal best performers, and history.
4. **Root cause:** ask why the driver moved, both externally (demand shift, new entrant, input-cost inflation, regulation) and internally (pricing decisions, operational issues, mix strategy).

## Step 4: Generate and prioritize levers

| Revenue levers | Cost levers |
|---------------|-------------|
| Raise price / reduce discounting | Renegotiate suppliers, consolidate vendors |
| Shift mix to high-margin products/customers | Redesign product (design-to-value) |
| Increase volume: new channels, segments, geographies | Automate / improve productivity |
| Upsell, cross-sell, bundling | Reduce SG&A, spans & layers |
| Add revenue streams (services, financing) | Footprint optimization (close/merge sites) |
| Reduce churn | Outsource / offshore non-core |

Prioritize in a table:
| Lever | Est. profit impact ($) | Time to impact | Ease / risk | Priority |

Quantify impact with simple math (e.g., "a 2% price increase on $500M revenue at 0% volume loss = +$10M; break-even volume loss is X%").

## Step 5: Recommend (answer first)

```markdown
## Recommendation
One sentence: the answer, quantified.

## Diagnosis
Profit bridge + where the decline concentrates + root cause.

## Levers (prioritized table)

## Risks & next steps
```

## Pitfalls
- Don't jump to cost-cutting before checking revenue. Many profit problems are price or mix problems.
- Distinguish margin % from absolute profit. A falling margin can coexist with rising profit.
- Watch for allocation artifacts: allocated fixed costs can make a profitable segment look unprofitable. Check contribution margin before recommending cuts.
- Always ask whether the competition faces the same trend.
