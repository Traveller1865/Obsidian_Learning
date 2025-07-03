---
type: biological_response
modifiable: semi
node_category: cardiovascular
tags: [endothelium, vascular, nitric_oxide]
source_type: [lab, wearable-inferred]
linked_model_inputs: [flow_mediated_dilation, CRP, BP_variability]
---

# Endothelial Dysfunction — Biological Response Node

## 🧪 Description
Impairment in the vascular endothelium's ability to regulate blood flow, inflammation, and clotting — a central factor in atherosclerosis and cardiovascular disease.

## 🔁 Triggered By
- [[Systemic Inflammation]]
- [[Elevated Blood Glucose]]
- [[Oxidative Stress]]
- [[Hypertension]]

## ⛓ Leads To
- [[Atherosclerosis]]
- [[Hypertension]]
- [[Stroke]]

## 📊 Measurable Biomarkers
- Flow-mediated dilation (FMD)
- ADMA (asymmetric dimethylarginine)
- CRP
- Nitric oxide levels

## 🔍 Detection Threshold
Impaired FMD (<6%) and elevated CRP or ADMA

## 📉 Downstream Risk Amplification
- Propagation Coefficient: `0.85`
- Risk Scaling Factor: `vascular-resistance`

## 🛠 Influenced By
| Intervention              | Effect                  | Evidence Level |
|---------------------------|--------------------------|----------------|
| [[Aerobic Exercise]]      | Improves endothelial function | High      |
| [[Nitrate-Rich Diet]]     | Increases NO availability     | Moderate   |

## 🧠 Model Notes
Vascular gateway node — small improvements here reduce risk across all cardiovascular downstream paths
