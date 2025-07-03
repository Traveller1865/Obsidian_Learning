---
type: node_logic
target_node: Subclinical Hypothyroid
category: intermediate_dysfunction
---

# 🧠 Node Logic — Subclinical Hypothyroid

## 🔑 Activation Criteria
- TSH: 3.0–5.0 mIU/L with normal FT4
- Symptoms: fatigue, cold intolerance, weight gain, constipation
- Poor metabolic rate and mood

## 🔁 Risk Propagation
- [[Fatigue]] (β = 0.7)
- [[Depressive Symptoms]] (β = 0.55)
- [[Hormonal Axis Disruption]] (β = 0.6)
- [[Weight Gain]] (β = 0.65)

- **Decay Half-Life**: 30–60 days
- **Scaling**: Stronger with iodine/zinc deficiency, stress

## 🚨 Alert Rules
- Trigger if TSH in subclinical range + symptoms cluster
- Recommend micronutrient repletion, circadian realignment

## 🛠 Intervention Feedback
- Recheck TSH/FT4 after 4–6 weeks
- Deactivate if levels drop <2.5 and symptoms resolve

## 🧠 Modeling Notes
Precedes overt thyroid disease — highly responsive to lifestyle if caught early; must be monitored closely
