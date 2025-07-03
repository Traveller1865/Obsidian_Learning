---
type: node_logic
target_node: Osteoporosis
category: chronic_disease
---

# 🧠 Node Logic — Osteoporosis

## 🔑 Activation Criteria
- T-score ≤ -2.5 (DEXA)
- Fragility fractures
- Low vitamin D, low calcium intake, low sex hormones

## 🔁 Upstream Contributors
- [[Low Estrogen/Testosterone]] (β = 0.75)
- [[Inflammation]] (β = 0.6)
- [[Malabsorption / Leaky Gut]] (β = 0.5)
- [[Sedentary Lifestyle]] (β = 0.6)

- **Progression Window**: Years
- **Scaling**: Steady decay accelerated by inactivity, acidity, low minerals

## 🚨 Alert Rules
- Trigger if FRAX risk > threshold or T-score dropping >5%/year
- Recommend weight-bearing exercise, repletion, bone-specific micronutrients

## 🛠 Intervention Feedback
- Reassess DEXA every 12–18 months
- Deactivate risk acceleration if T-score stabilized

## 🧠 Modeling Notes
Silent risk until fracture — highly modifiable through movement, micronutrients, and hormone balance
