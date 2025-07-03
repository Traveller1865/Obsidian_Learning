---
type: node_logic
target_node: Prehypertension
category: intermediate_dysfunction
---

# 🧠 Node Logic — Prehypertension

## 🔑 Activation Criteria
- SBP: 120–129 mmHg, DBP <80 mmHg (2+ readings)
- Wearable BP drift or white coat effect, confirmed at home

## 🔁 Risk Propagation
- [[Hypertension]] (β = 0.8)
- [[Endothelial Dysfunction]] (β = 0.6)
- [[Cognitive Decline]] (β = 0.5)
- [[Cardiovascular Disease]] (β = 0.7)

- **Decay Half-Life**: 30 days
- **Scaling**: Linear — strong leverage for reversal if caught early

## 🚨 Alert Rules
- Trigger if avg BP enters preHTN range for 5+ days
- Recommend sodium reduction, movement streak, stress modulation

## 🛠 Intervention Feedback
- Deactivate if average BP drops <120/80 with sustained habit changes

## 🧠 Modeling Notes
High ROI node — ideal point for cost-effective cardiovascular prevention before pathology sets in
