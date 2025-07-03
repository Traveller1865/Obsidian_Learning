---
type: biological_response
modifiable: semi
node_category: metabolic
tags: [metabolic, insulin, prediabetes]
source_type: [lab, wearable (inferred)]
linked_model_inputs: [HOMA_IR, glucose_trends, waist_circumference]
---

# Insulin Resistance — Biological Response Node

## 🧪 Description
A diminished cellular response to insulin signaling, causing elevated blood glucose and compensatory hyperinsulinemia — central to metabolic disease.

## 🔁 Triggered By
- [[Elevated Blood Glucose]]
- [[High Cortisol]]
- [[Physical Inactivity]]

## ⛓ Leads To
- [[Visceral Obesity]]
- [[Type 2 Diabetes]]
- [[Hypertension]]

## 📊 Measurable Biomarkers
- HOMA-IR
- Fasting insulin (>10 μIU/mL)
- Glucose-insulin curve

## 🔍 Detection Threshold
Sustained HOMA-IR >2.0 or fasting insulin >10 + glucose >100

## 📉 Downstream Risk Amplification
- Propagation Coefficient: `0.8`
- Risk Scaling Factor: `multiplicative`

## 🛠 Influenced By
| Intervention         | Effect       | Evidence Level |
|----------------------|--------------|----------------|
| [[Exercise]]         | Enhances insulin sensitivity | High     |
| [[Low Carb Diet]]    | Reduces insulin demand | High     |

## 🧠 Model Notes
Critical threshold node for metabolic collapse — progressive and hard to reverse once entrenched
