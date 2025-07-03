---
type: root_cause
modifiable: true
node_category: behavioral
tags: [root, toxicology]
source_type: [survey, lab, biomarker]
linked_model_inputs: [alcohol_use, smoker_status]
---

# Substance Use — Root Cause Node

## 🔍 Description
Regular consumption of alcohol, nicotine, or drugs contributes to systemic toxicity, inflammation, liver burden, and cardiovascular risk.

## 🧬 Biological Impact Pathways
- [[Systemic Inflammation]]
- [[Liver Stress]]
- [[Hypertension]]

## ⚠️ Contributes To
- [[Liver Disease]]
- [[Cancer]]
- [[Cardiovascular Disease]]

## 🧩 Associated Biomarkers
- GGT
- ALT
- CRP
- Blood Pressure

## 🛠 Interventions
| Intervention         | Evidence Level | Expected Risk Reduction |
|----------------------|----------------|--------------------------|
| Alcohol Reduction    | High           | 50–70%                   |
| Nicotine Cessation   | High           | 60–80%                   |
| Substance Abuse Therapy | Moderate     | 40–60%                   |

## 🧠 Model Notes
Node activates if alcohol >14 drinks/week or smoker status = true
