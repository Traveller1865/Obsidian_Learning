---
type: biological_response
modifiable: semi
node_category: nervous_system
tags: [stress, autonomic, fight_flight]
source_type: [wearable, HRV, biometric_inference]
linked_model_inputs: [HRV_ratio, resting_HR, respiration_rate]
---

# Sympathetic Dominance — Biological Response Node

## 🧪 Description
Chronic overactivation of the sympathetic nervous system — leads to suppressed recovery, elevated cortisol, and vascular strain.

## 🔁 Triggered By
- [[Chronic Psychological Stress]]
- [[Sleep Disruption]]
- [[Social Isolation]]

## ⛓ Leads To
- [[Autonomic Dysfunction]]
- [[Hypertension]]
- [[Sleep Disorders]]

## 📊 Measurable Biomarkers
- HRV (LF/HF ratio > 2.0)
- Resting heart rate
- Stress score (wearable-derived)

## 🔍 Detection Threshold
Sustained elevated LF/HF ratio and resting HR for 5+ days

## 📉 Downstream Risk Amplification
- Propagation Coefficient: `0.65`
- Risk Scaling Factor: `sympathetic_spike`

## 🛠 Influenced By
| Intervention         | Effect               | Evidence Level |
|----------------------|----------------------|----------------|
| [[Breathwork]]       | Shifts to parasympathetic | High       |
| [[Meditation]]       | Reduces SNS dominance | High         |

## 🧠 Model Notes
Interacts directly with cortisol and HRV nodes; also suppresses regenerative systems like digestion and immune repair
