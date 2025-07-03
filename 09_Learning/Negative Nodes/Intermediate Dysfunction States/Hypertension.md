---
type: dysfunction_state
modifiable: true
node_category: vascular
tags: [blood_pressure, cardiovascular, vascular]
source_type: [wearable, home_monitor, clinical]
linked_model_inputs: [SBP, DBP, BP_variability]
---

# Hypertension — Dysfunction Node

## ⚠️ Description
Chronically elevated blood pressure, often asymptomatic, leading to endothelial damage, vascular remodeling, and significantly increased cardiovascular risk.

## 🔁 Triggered By
- [[Insulin Resistance]]
- [[High Cortisol]]
- [[Sympathetic Dominance]]
- [[Endothelial Dysfunction]]

## ⛓ Leads To
- [[Cardiovascular Disease]]
- [[Chronic Kidney Disease]]
- [[Stroke]]

## 📊 Measurable Criteria
- Systolic BP ≥130 mmHg or Diastolic BP ≥80 mmHg
- Or sustained BP variability with >10% deviation from baseline

## 🔍 Diagnostic Threshold
Sustained elevated BP across 3+ days or 2+ clinical readings

## 📉 Risk Amplification
- Propagation Coefficient: `0.85`
- Acceleration Factor: `vascular_decay`

## 🛠 Modifiable With
| Intervention             | Target Outcome     | Evidence Level |
|--------------------------|--------------------|----------------|
| [[Sodium Reduction]]     | Lowers BP          | High           |
| [[Aerobic Exercise]]     | Improves vascular tone | High     |
| [[Stress Reduction]]     | Reduces sympathetic pressure | Moderate |

## 🧠 Model Notes
Acts as a high-impact convergence node with strong ties to CVD, kidney, and cognitive disease pathways
