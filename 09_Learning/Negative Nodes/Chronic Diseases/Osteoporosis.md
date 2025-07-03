---
type: disease_outcome
modifiable: partially
node_category: diagnosis
tags: [chronic_disease, bone_health]
source_type: [DEXA_scan, clinical_dx]
linked_model_inputs: [bone_density_score, hormone_levels]
---

# Osteoporosis — Final Disease Node

## 🧨 Description
A progressive skeletal disorder characterized by decreased bone mineral density and structural deterioration, leading to increased fracture risk.

## 🔁 Upstream Dysfunctions
- [[Hormonal Axis Disruption]]
- [[Low Estrogen / Testosterone]]
- [[Inflammation]]
- [[Nutrient Deficiency]]

## 🔁 Contributing Root Causes
- [[Sedentary Lifestyle]]
- [[Poor Diet]]
- [[Chronic Stress]]
- [[Low Vitamin D Exposure]]

## 🔬 Diagnostic Criteria
- DEXA T-score ≤ -2.5
- History of fragility fracture
- Bone turnover markers

## 🩺 Symptoms / Clinical Findings
- Back pain
- Loss of height
- Stooped posture
- Fragility fractures

## 📉 Model Implications
- Flagged for proactive fracture prevention pathways
- Risk score rises sharply post-menopause or andropause unless mitigated

## 🛠 Disease Management Levers
| Lever                   | Effect                  | Evidence Level |
|------------------------|--------------------------|----------------|
| [[Weight-Bearing Exercise]] | Stimulates bone formation | High         |
| [[Vitamin D + Calcium Supplementation]] | Supports mineral density | High |

## 🧠 Modeling Notes
Use as a silent, late-stage structural node — alerts should trigger in postural change, sex hormone loss, or sedentary cluster
