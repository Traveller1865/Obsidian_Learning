---
type: root_cause
modifiable: true
node_category: behavioral
tags: [root, lifestyle, risk_factor]
source_type: [self-reported, wearable-inferred, survey]
linked_model_inputs: [nutrition_score, glucose_spikes, fasting_glucose]
---

# Poor Diet — Root Cause Node

## 🔍 Description
A diet high in added sugars, refined carbs, trans fats, and ultra-processed foods. Chronically poor nutrition leads to glycemic volatility, oxidative stress, and inflammation.

## 🧬 Biological Impact Pathways
- [[Elevated Blood Glucose]]
- [[Gut Dysbiosis]]
- [[Systemic Inflammation]]
- [[Fatty Liver]]
- [[Insulin Resistance]]

## ⚠️ Contributes To
- [[Visceral Obesity]]
- [[Type 2 Diabetes]]
- [[Cardiovascular Disease]]

## 🧩 Associated Biomarkers
- Fasting glucose
- Hemoglobin A1C
- CRP (C-reactive protein)
- ALT / AST (liver enzymes)

## 🛠 Interventions
| Intervention         | Evidence Level | Expected Risk Reduction |
|----------------------|----------------|--------------------------|
| Mediterranean Diet   | High           | 40–60%                   |
| Intermittent Fasting | Moderate       | 30–50%                   |
| Sugar Elimination    | High           | 60%+                     |

## 🧠 Model Notes
This node should activate when `nutrition_score < 60` for >14 days
