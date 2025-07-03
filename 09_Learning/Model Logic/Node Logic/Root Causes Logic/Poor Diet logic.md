---
type: node_logic
target_node: Poor Diet
category: root_cause
---

# 🧠 Node Logic — Poor Diet

## 🔑 Activation Criteria
- >20% daily calories from added sugar
- <15g/day fiber intake
- Omega-6:Omega-3 ratio >15:1 (lab or inferred)
- >2 servings/day of ultra-processed foods

## 🔁 Risk Propagation
- [[Insulin Resistance]] (β = 0.8)
- [[Leaky Gut]] (β = 0.65)
- [[Fatty Liver (NAFLD)]] (β = 0.7)
- [[Elevated Triglycerides]] (β = 0.6)
- [[Depressive Symptoms]] (β = 0.5)

- **Decay Half-Life**: 10 days
- **Scaling**: Additive with circadian and stress nodes

## 🚨 Alert Rules
- Activate if 3+ poor quality markers persist for 4 out of 7 days
- Recommend dietary journaling, whole food challenge, hydration prompt

## 🛠 Intervention Feedback
- Reassess microbiome, blood glucose, and symptom log in 10–14 days
- Deactivate when 70%+ whole foods for 7+ days

## 🧠 Modeling Notes
Top 3 risk amplifier — almost all downstream nodes worsened by sustained poor intake quality
