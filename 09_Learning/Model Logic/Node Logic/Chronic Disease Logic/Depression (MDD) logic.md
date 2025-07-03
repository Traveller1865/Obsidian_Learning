---
type: node_logic
target_node: Depression (MDD)
category: chronic_disease
---

# 🧠 Node Logic — Depression (MDD)

## 🔑 Activation Criteria
- DSM-5 criteria for MDD: ≥2 weeks of low mood + anhedonia + 3+ symptoms
- PHQ-9 score ≥10
- Suicidal ideation, sleep/appetite/motivation issues

## 🔁 Upstream Contributors
- [[Chronic Stress]] (β = 0.75)
- [[Poor Sleep Quality]] (β = 0.7)
- [[Inflammation]] (β = 0.6)
- [[Social Isolation]] (β = 0.65)

- **Progression Window**: 1 month – years
- **Scaling**: Strong feedback loop — worsens with rumination + inactivity

## 🚨 Alert Rules
- Trigger if PHQ score >10 + energy/motivation log low for >7 days
- Recommend sleep-circadian realignment, structured activity, gut-brain protocol

## 🛠 Intervention Feedback
- Recheck mood score, HRV, sleep metrics weekly
- Deactivate when symptoms and logs stabilize

## 🧠 Modeling Notes
Not a purely chemical imbalance — integrative mood prediction must include inflammation, gut, sleep, and lifestyle data
