---
type: root_cause
modifiable: true
node_category: behavioral
tags: [root, sleep, circadian]
source_type: [wearable, user log]
linked_model_inputs: [sleep_efficiency, total_sleep, HRV]
---

# Poor Sleep Quality — Root Cause Node

## 🔍 Description
Chronic sleep deprivation and fragmentation impair glucose metabolism, raise cortisol, and increase inflammation.

## 🧬 Biological Impact Pathways
- [[Systemic Inflammation]]
- [[High Cortisol]]
- [[Insulin Resistance]]

## ⚠️ Contributes To
- [[Hypertension]]
- [[Type 2 Diabetes]]
- [[Cognitive Decline]]

## 🧩 Associated Biomarkers
- Sleep efficiency
- Total sleep time
- Cortisol AM/PM
- HRV

## 🛠 Interventions
| Intervention         | Evidence Level | Expected Risk Reduction |
|----------------------|----------------|--------------------------|
| Sleep Hygiene        | High           | 30–50%                   |
| Blue Light Reduction | Moderate       | 20–40%                   |
| Melatonin            | Low            | 15–30%                   |

## 🧠 Model Notes
Node activates when sleep efficiency < 75% for 7+ days
