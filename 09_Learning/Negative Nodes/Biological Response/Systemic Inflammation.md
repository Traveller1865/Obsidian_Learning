---
type: biological_response
modifiable: semi
node_category: inflammatory
tags: [inflammation, cytokine, aging]
source_type: [lab, inference]
linked_model_inputs: [CRP, IL6, TNF_alpha]
---

# Systemic Inflammation — Biological Response Node

## 🧪 Description
A chronic low-grade inflammatory state involving elevated cytokines and immune dysregulation — implicated in most age-related diseases.

## 🔁 Triggered By
- [[Gut Dysbiosis]]
- [[Poor Sleep Quality]]
- [[Environmental Toxins]]
- [[Obesity]]

## ⛓ Leads To
- [[Autoimmune Disease]]
- [[Atherosclerosis]]
- [[Cancer]]

## 📊 Measurable Biomarkers
- hs-CRP
- IL-6
- TNF-alpha

## 🔍 Detection Threshold
CRP >2.0 mg/L or IL-6 >3 pg/mL over >3 readings

## 📉 Downstream Risk Amplification
- Propagation Coefficient: `0.9`
- Risk Scaling Factor: `exponential`

## 🛠 Influenced By
| Intervention         | Effect       | Evidence Level |
|----------------------|--------------|----------------|
| [[Anti-inflammatory Diet]] | Reduces inflammatory load | High     |
| [[Omega-3 Supplementation]] | Reduces CRP, IL-6 | Moderate     |

## 🧠 Model Notes
Amplifies multiple disease nodes; central to aging and immune-mediated dysfunction
