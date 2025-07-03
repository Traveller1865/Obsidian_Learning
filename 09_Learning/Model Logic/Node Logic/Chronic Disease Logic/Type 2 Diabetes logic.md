---
type: node_logic
target_node: Type 2 Diabetes
category: chronic_disease
---

# 🧠 Node Logic — Type 2 Diabetes

## 🔑 Activation Criteria
- Fasting glucose ≥126 mg/dL or A1C ≥6.5%
- 2-hour OGTT ≥200 mg/dL
- Confirmed with CGM: >30% time above 180 mg/dL

## 🔁 Upstream Contributors
- [[Insulin Resistance]] (β = 0.95)
- [[Visceral Obesity]] (β = 0.85)
- [[Leptin Resistance]] (β = 0.7)
- [[Sleep Fragmentation]] (β = 0.6)

- **Progression Window**: 5–10 years from prediabetes
- **Scaling**: Steep under inactivity, chronic stress, sleep loss

## 🚨 Alert Rules
- Trigger if A1C trend rising or CGM flags metabolic inflexibility
- Recommend metabolic reversal plan: fasting, training, circadian sync

## 🛠 Intervention Feedback
- Monitor CGM and fasting trends weekly
- Deactivate active disease tag if reversal maintained for 90+ days

## 🧠 Modeling Notes
Highly reversible in early stages — cornerstone of metabolic disease logic and risk scoring
