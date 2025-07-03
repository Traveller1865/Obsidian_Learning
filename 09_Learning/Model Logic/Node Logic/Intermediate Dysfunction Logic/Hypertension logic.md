---
type: node_logic
target_node: Hypertension
category: intermediate_dysfunction
---

# 🧠 Node Logic — Hypertension

## 🔑 Activation Criteria
- SBP ≥130 mmHg or DBP ≥80 mmHg (2+ readings)
- Confirmed with home BP or wearable average

## 🔁 Risk Propagation
- [[Cardiovascular Disease]] (β = 0.9)
- [[Chronic Kidney Disease]] (β = 0.75)
- [[Cognitive Decline]] (β = 0.6)
- [[Endothelial Dysfunction]] (β = 0.7)

- **Decay Half-Life**: 60–90 days
- **Scaling**: Amplified under stress + inactivity + salt excess

## 🚨 Alert Rules
- Trigger if SBP/DBP exceed cutoff + RHR or HRV drift
- Recommend DASH-like dietary audit, breathwork, walking program

## 🛠 Intervention Feedback
- Recheck BP trend weekly; deactivate if average <125/80 for 2 weeks

## 🧠 Modeling Notes
Vascular pressure overload is both a cause and symptom of poor recovery and systemic risk — modifiable with low-cost habits
