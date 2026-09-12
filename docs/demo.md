# Demo

This page shows the intended behavior of **Marketing Campaign Critic** in a compact, portfolio-friendly format.

## Example input

> Analyze adidas “进城办事”. I want a strategic critique, not a campaign summary.

## Example output shape

### Campaign classification

- **Primary:** Reactive Campaign
- **Secondary:** Cultural Moment
- **Insight type:** Cultural + Behavioral
- **Confidence:** High

### Strategic score

| Dimension | Score |
|---|---:|
| Audience | 12 / 15 |
| Insight | 18 / 20 |
| Strategy | 17 / 20 |
| Big Idea | 18 / 20 |
| IMC Integration | 12 / 15 |
| Measurement | 7 / 10 |
| **Total** | **84 / 100** |

### Diagnosis

The campaign’s strength comes from cultural sensitivity, response speed, and restraint rather than from manufacturing the original idea. The brand successfully amplified an audience-created cultural moment without over-controlling it.

### Brand ownership

**Execution-built ownership**

The phrase was not inherently proprietary, but repeated branded execution helped convert a public cultural asset into a stronger brand association.

### Risk scan

- **Brand safety:** Medium
- **Evidence status:** Inference / future risk
- **Reason:** Repeating the same accidental tone deliberately could feel forced and reduce authenticity.
- **Risk override:** No

### Recommendation

Learn from the organization’s cultural-response capability, not from the surface-level formula of “make the brand sound funny.”

---

## What this demo is testing

This example is intentionally used as a regression case. The skill should:

1. classify the work as reactive rather than purely planned,
2. distinguish cultural participation from simple virality,
3. recognize execution-built brand ownership,
4. avoid inventing legal or ethical risks just because a Risk Scan exists,
5. preserve the original strategic judgment after new modules are added.

The exact numeric score may move slightly across versions. The **direction of diagnosis** should remain stable.
