---
type: node_logic
target_node: Elevated Blood Glucose
category: biological_response
---

# 🧠 Node Logic — Elevated Blood Glucose

## 🔑 Activation Criteria
- Fasting glucose >100 mg/dL (2+ readings)
- Postprandial spike >180 mg/dL or CGM excursions >30% of day
- A1C ≥ 5.6% and trending upward

## 🔁 Risk Propagation
- [[Insulin Resistance]] (β = 0.85)
- [[Visceral Obesity]] (β = 0.6)
- [[Fatty Liver (NAFLD)]] (β = 0.7)
- [[Type 2 Diabetes]] (β = 0.95)

- **Decay Half-Life**: 10–14 days (glucose shifts rapidly with diet/activity)
- **Scaling**: Steep if combined with high TGs or low activity

## 🚨 Alert Rules
- Trigger if glucose >100 for 5+ days or 2x >140 post-meal
- Recommend CGM challenge, carb audit, metabolic reset

## 🛠 Intervention Feedback
- Deactivate if fasting glucose <95 and postprandial <140 for 7+ days

## 🧠 Modeling Notes
Core metabolic signal — used as a leading indicator for multiple chronic disease pathways
