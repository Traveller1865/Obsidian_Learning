---
type: node_logic
target_node: Environmental Toxins
category: root_cause
---

# 🧠 Node Logic — Environmental Toxins

## 🔑 Activation Criteria
- Positive exposure report: BPA, phthalates, VOCs, mold, heavy metals
- Serum or urine levels above threshold (e.g., mercury >5 μg/L)
- Symptom clusters (fatigue, fog, rash, hormone disruption)

## 🔁 Risk Propagation
- [[Oxidative Stress]] (β = 0.8)
- [[Leaky Gut]] (β = 0.6)
- [[Hormonal Axis Disruption]] (β = 0.65)
- [[Autoimmune Disease]] (β = 0.5)

- **Decay Half-Life**: 21–60 days depending on compound
- **Scaling**: Stepwise (threshold-based; nonlinear)

## 🚨 Alert Rules
- Trigger detox tracking workflow if confirmed exposure + active symptoms
- Recommend sauna, chelation (if metal), air/water filter upgrades

## 🛠 Intervention Feedback
- Monitor symptom regression + repeat exposure panels
- Deactivation if markers drop below safe range + symptoms resolve

## 🧠 Modeling Notes
Acts as a silent co-factor node; moderate risk on its own, but amplifies inflammation and hormone loops
