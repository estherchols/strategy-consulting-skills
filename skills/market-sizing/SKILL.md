---
name: market-sizing
description: Estimate the size of a market (TAM, SAM, SOM) or any quantity using top-down and bottom-up approaches with explicit, sanity-checked assumptions. Use when the user asks how big a market is, for a TAM/SAM/SOM, a Fermi or guesstimate question, a market-sizing case ("how many X are sold in the US per year?"), or a revenue potential estimate.
---

# Market Sizing

Produce a transparent, defensible estimate. Being right to within an order of magnitude matters less than showing structured logic and clear assumptions.

## Step 1: Clarify the question

Pin down before calculating:
- **What exactly is measured:** units, revenue, users? Annual or one-time?
- **Geography and time frame.**
- **Market definition:** what's in and out (for example, do e-bikes count as bikes?).
- **Purpose:** an investment case needs SAM/SOM, while an interview question usually needs just one number.

## Step 2: Choose the approach (ideally use both)

### Top-down
Start from a large known number and narrow it down:
`Population → relevant segment % → adoption/usage % → frequency → price`

### Bottom-up
Build up from unit economics:
`# of buyers/locations × units per buyer × price per unit`
(e.g., # of coffee shops × cups per day × days per year × price per cup)

### Other angles
- **Supply-side:** production capacity, number of suppliers × output.
- **Analogs/proxies:** a comparable market in another country, scaled by GDP or population.
- **Value-based:** customer pain (cost saved or value created) × willingness to pay.

## Step 3: Calculate with a driver table

| Driver | Value | Source / rationale |
|--------|-------|--------------------|
| US population | 335M | Census (known) |
| Households | ~130M | ~2.6 people per household |
| % households owning a dog | ~40% | Industry surveys (estimate) |
| ... | ... | ... |
| **Result** | **$X B** | |

Rules:
- Use round numbers to keep the math clean (335M → ~330M), and say you've rounded.
- Segment when behavior differs meaningfully (urban vs. rural, age bands, B2B vs. B2C).
- Mark each assumption as **known fact**, **sourced estimate**, or **assumption**.
- If web search is available, look up anchor facts (population, industry reports) and cite them.

## Step 4: Define TAM, SAM, SOM (for business cases)
- **TAM** (Total Addressable Market): total demand if you had 100% share.
- **SAM** (Serviceable Available Market): the portion your product, channel, and geography can actually serve.
- **SOM** (Serviceable Obtainable Market): the share you can realistically capture in 3–5 years, given competition and go-to-market capacity. Justify it with benchmarks (for example, "the leading competitor has 15% share after 8 years").

## Step 5: Sanity check (always)
- **Triangulate:** do the top-down and bottom-up answers agree within ~2×? If not, find which assumption drives the gap.
- **Reality check:** compare with known figures (revenue of a market leader, public industry estimates, per-capita spend).
- **Sensitivity:** which 1–2 assumptions move the answer most? Show a low/base/high range.

## Output

```markdown
## Question & definition
## Approach (and why)
## Calculation (driver table, top-down and bottom-up)
## Result: base case, plus a low–high range
## Sanity checks
## Key assumptions to validate
## So what: what this number means for the decision
```
