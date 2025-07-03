---
type: biological_response
modifiable: semi
node_category: nervous_system
tags: [HRV, vagal_tone, resilience]
source_type: [wearable]
linked_model_inputs: [baseline_HRV, sleep_quality, stress_events]
---

# Low HRV — Biological Response Node

## 🧪 Description
Heart Rate Variability (HRV) is a non-invasive biomarker of autonomic flexibility. Low HRV indicates poor adaptability to stress, higher inflammation, and elevated chronic disease risk.

## 🔁 Triggered By
- [[Chronic Psychological Stress]]
- [[Poor Sleep Quality]]
- [[Sympathetic Dominance]]

## ⛓ Leads To
- [[Autonomic Dysfunction]]
- [[Cardiovascular Disease]]
- [[Depression]]

## 📊 Measurable Biomarkers
- RMSSD
- SDNN
- HRV baseline trend vs personal average

## 🔍 Detection Threshold
>15% reduction from baseline HRV sustained over 5+ days

## 📉 Downstream Risk Amplification
- Propagation Coefficient: `0.7`
- Risk Scaling Factor: `logarithmic`

## 🛠 Influenced By
| Intervention         | Effect               | Evidence Level |
|----------------------|----------------------|----------------|
| [[Box Breathing]]    | Raises HRV acutely   | High           |
| [[Sleep Optimization]] | Improves vagal tone | High           |

## 🧠 Model Notes
Acts as early warning signal in stress-related and cardiac pathways
