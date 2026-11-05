# Strategy Consulting Skills for Claude

[Agent Skills](https://docs.claude.com/en/docs/agents-and-tools/agent-skills/overview) for Claude Code and Claude.ai that teach Claude the hypothesis-driven, structured problem-solving methods used at top-tier (MBB-style) strategy consulting firms. These methods include MECE issue trees, answer-first communication, and well-known strategy frameworks.

> Independent project. Not affiliated with or endorsed by McKinsey, BCG, Bain, or any other firm.

| Skill | What it does |
|-------|--------------|
| [`problem-structuring`](skills/problem-structuring/SKILL.md) | SMART problem statement, SCQ, MECE issue trees, prioritized hypotheses, and a workplan |
| [`market-sizing`](skills/market-sizing/SKILL.md) | TAM/SAM/SOM and estimation questions, built top-down and bottom-up with sanity checks and ranges |
| [`profitability-analysis`](skills/profitability-analysis/SKILL.md) | Profit tree, profit bridge, segmentation, and prioritized revenue and cost levers |
| [`market-entry`](skills/market-entry/SKILL.md) | Market attractiveness, competition, right to win, build/buy/partner choice, and a go/no-go call |
| [`competitive-strategy`](skills/competitive-strategy/SKILL.md) | Five Forces, value chain, generic strategies, where to play/how to win, growth-share matrix, 7S, and competitive response |
| [`growth-and-ma`](skills/growth-and-ma/SKILL.md) | Ansoff matrix, growth horizons, target screening, due diligence, synergies, and valuation sense checks |
| [`executive-storyline`](skills/executive-storyline/SKILL.md) | Pyramid Principle, SCR, action titles, ghost decks, and executive summaries |

## Install

### Claude Code (as a plugin)

```
/plugin marketplace add estherchols/strategy-consulting-skills
/plugin install strategy-consulting-skills@strategy-consulting-skills
```

### Claude Code (manual)

```bash
git clone https://github.com/estherchols/strategy-consulting-skills.git
cp -r strategy-consulting-skills/skills/* ~/.claude/skills/
```

### Claude.ai

Zip a skill folder (for example `skills/problem-structuring/`) and upload it under **Settings → Capabilities → Skills**.

## Usage

Skills trigger automatically when the request matches the skill. For example:

- "Build an issue tree for why our subscription churn doubled this year"
- "How big is the US market for pet insurance?"
- "Our airline client's profits fell 20%. Walk me through why"
- "Should a European grocery chain enter the US?"
- "Run Five Forces on the cloud GPU rental industry"
- "Should we acquire this company? Here are its financials"
- "Turn these findings into a storyline and ghost deck for the CEO"
- "Give me a candidate-led profitability case, final-round difficulty"



## Contributing

Issues and PRs are welcome. Each skill is one `SKILL.md` file with `name` and `description` frontmatter.

## License

MIT
