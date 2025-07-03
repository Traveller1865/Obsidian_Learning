---
type: biological_response
modifiable: semi
node_category: biochemical
tags: [oxidative, ROS, mitochondrial]
source_type: [lab, inference]
linked_model_inputs: [glutathione, 8-OHdG, inflammation_index]
---

# Oxidative Stress — Biological Response Node

## 🧪 Description
An imbalance between free radicals (ROS) and antioxidant defenses, contributing to cellular aging, DNA damage, and inflammation.

## 🔁 Triggered By
- [[Environmental Toxins]]
- [[Poor Diet]]
- [[Mitochondrial Dysfunction]]

## ⛓ Leads To
- [[Cancer]]
- [[Neurodegeneration]]
- [[Cardiovascular Disease]]

## 📊 Measurable Biomarkers
- Glutathione (GSH:GSSG ratio)
- 8-OHdG (oxidative DNA damage)
- Oxidized LDL

## 🔍 Detection Threshold
Low glutathione + elevated 8-OHdG over 2+ panels

## 📉 Downstream Risk Amplification
- Propagation Coefficient: `0.8`
- Risk Scaling Factor: `exponential`

## 🛠 Influenced By
| Intervention             | Effect              | Evidence Level |
|--------------------------|---------------------|----------------|
| [[Antioxidant-Rich Diet]]| Lowers ROS burden   | High           |
| [[Glutathione Precursors]]| Boosts resilience  | Moderate       |

## 🧠 Model Notes
Used in cancer, aging, and mitochondrial dysfunction pathways
