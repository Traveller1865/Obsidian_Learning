---
type: dysfunction_state
modifiable: true
node_category: endocrine
tags: [thyroid, fatigue, hormone]
source_type: [lab]
linked_model_inputs: [TSH, free_T3, reverse_T3]
---

# Subclinical Hypothyroid — Dysfunction Node

## ⚠️ Description
A mild underactivity of the thyroid gland without overt hypothyroid symptoms. Often missed, but linked to fatigue, weight gain, and depression.

## 🔁 Triggered By
- [[Hormonal Imbalance]]
- [[Chronic Stress]]
- [[Poor Sleep Quality]]

## ⛓ Leads To
- [[Chronic Fatigue]]
- [[Depression]]
- [[Visceral Obesity]]

## 📊 Measurable Criteria
- TSH: 2.5–4.5 mIU/L
- Free T3: low-normal
- Reverse T3: elevated

## 🔍 Diagnostic Threshold
TSH >2.5 with suboptimal T3 or elevated reverse T3 on two labs

## 📉 Risk Amplification
- Propagation Coefficient: `0.6`
- Acceleration Factor: `slow-decay`

## 🛠 Modifiable With
| Intervention             | Target Outcome             | Evidence Level |
|--------------------------|----------------------------|----------------|
| [[Stress Reduction]]     | Lowers TSH, improves conversion | Moderate   |
| [[Selenium / Iodine]]    | Supports thyroid enzyme activity | Moderate   |

## 🧠 Model Notes
Useful for explaining unexplained fatigue, weight issues, and depressive symptoms in younger populations
