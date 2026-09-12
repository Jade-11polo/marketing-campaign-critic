# Marketing Campaign Critic

A compact Agent Skill for critical campaign diagnosis, built from scratch and iterated through real campaign tests.

## Current version

**v0.4.1**

```text
Campaign Input
      ↓
Campaign Type Router
      ↓
Evidence Check
      ↓
Core Framework
      ↓
Conditional Lenses
      ↓
Risk Scan
      ↓
Strategic Diagnosis
      ↓
Score + Recommendation
```

## Core framework

| Dimension | Weight |
|---|---:|
| Audience | 15 |
| Insight | 20 |
| Strategy | 20 |
| Big Idea | 20 |
| IMC Integration | 15 |
| Measurement | 10 |
| **Total** | **100** |

## Conditional lenses

Loaded only when relevant:
- Collaboration
- Reactive Campaign
- Cultural Moment
- Crisis Response

## Risk layer

Scans for legal/compliance, brand safety, execution, and ethical risk. A material high risk may override an otherwise strong strategic score.

## Evaluation-driven development

- **Test 01: adidas “进城办事”** → exposed scoring math, linear-planning assumptions, and static brand ownership.
- **Test 02: Luckin Coffee × Duolingo** → exposed the need for insight taxonomy and a collaboration lens.
- **Test 03: Pechoin “1931”** → exposed the difference between viral creative quality and campaign-system quality, plus execution/IP risk.
- **Regression 01: adidas rerun on v0.4** → confirmed routing stability and added the safeguard against manufactured risks.

## Repository structure

```text
marketing-campaign-critic/
├── SKILL.md
├── README.md
├── CHANGELOG.md
├── VERSION
├── references/
│   └── architecture.md
└── evals/
    ├── README.md
    ├── 001_adidas_errands.md
    ├── 002_luckin_duolingo.md
    └── 003_pechoin_1931.md
```

## Status

Pre-1.0. The goal now is stability, not feature accumulation. Future changes should be driven by failed evaluations or repeated user needs.
