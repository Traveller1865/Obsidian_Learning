---
type: dysfunction_state
modifiable: true
node_category: energy
tags: [fatigue, mitochondria, recovery]
source_type: [symptom_log, functional testing]
linked_model_inputs: [energy_score, VO2_max, mitochondrial_panel]
---

# Chronic Fatigue — Dysfunction Node

## ⚠️ Description
A persistent lack of physical or mental energy not relieved by rest. May reflect mitochondrial dysfunction, sleep problems, inflammation, or HPA axis dysregulation.

## 🔁 Triggered By
- [[Sleep Fragmentation]]
- [[Mitochondrial Dysfunction]]
- [[Subclinical Hypothyroid]]
- [[Systemic Inflammation]]

## ⛓ Leads To
- [[Depression]]
- [[Reduced Physical Activity]]
- [[Cognitive Impairment]]

## 📊 Measurable Criteria
- Self-reported fatigue ≥6/10
- Decreased VO2 max
- Impaired mitochondrial markers (ATP, lactate)

## 🔍 Diagnostic Threshold
Fatigue reported for >4 weeks + physiological dysfunction (VO2 or labs)

## 📉 Risk Amplification
- Propagation Coefficient: `0.65`
- Acceleration Factor: `energy_feedback_loop`

## 🛠 Modifiable With
| Intervention         | Target Outcome         | Evidence Level |
|----------------------|------------------------|----------------|
| [[Sleep Optimization]] | Restores energy availability | High     |
| [[CoQ10 / B Vitamins]] | Improves mitochondrial function | Moderate |

## 🧠 Model Notes
Acts as a convergence node for multiple hidden dysfunctions; severity often outpaces visible lab abnormalities
