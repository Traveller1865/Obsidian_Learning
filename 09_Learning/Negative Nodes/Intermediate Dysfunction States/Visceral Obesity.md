---
type: dysfunction_state
modifiable: true
node_category: metabolic
tags: [obesity, fat_distribution, metabolic]
source_type: [waist_circumference, DEXA, BMI]
linked_model_inputs: [waist_size, WHR, bodyfat_percent]
---

# Visceral Obesity — Dysfunction Node

## ⚠️ Description
Excess abdominal fat around internal organs, more metabolically harmful than subcutaneous fat. Drives inflammation, insulin resistance, and hormone imbalance.

## 🔁 Triggered By
- [[Poor Diet]]
- [[Physical Inactivity]]
- [[Insulin Resistance]]

## ⛓ Leads To
- [[Type 2 Diabetes]]
- [[Hypertension]]
- [[Non-Alcoholic Fatty Liver Disease]]
- [[Cancer]]

## 📊 Measurable Criteria
- Waist circumference >102 cm (men), >88 cm (women)
- Waist-to-hip ratio >0.9 (men), >0.85 (women)

## 🔍 Diagnostic Threshold
Consistent central adiposity above WHO cutoffs for 2+ weeks

## 📉 Risk Amplification
- Propagation Coefficient: `0.9`
- Acceleration Factor: `cytokine_loop`

## 🛠 Modifiable With
| Intervention             | Target Outcome      | Evidence Level |
|--------------------------|---------------------|----------------|
| [[Low Carb Diet]]        | Reduces abdominal fat | High        |
| [[Resistance Training]]  | Improves fat partitioning | Moderate |

## 🧠 Model Notes
Often acts as a causal amplifier node — higher levels worsen nearly every other dysfunction and accelerate disease conversion
