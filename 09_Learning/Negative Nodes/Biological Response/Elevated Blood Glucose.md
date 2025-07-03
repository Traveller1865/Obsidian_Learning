---
type: biological_response
modifiable: semi
node_category: biomarker
tags: [glycemic, metabolic, glucose]
source_type: [lab, wearable]
linked_model_inputs: [fasting_glucose, CGM_spikes, A1C]
---

# Elevated Blood Glucose — Biological Response Node

## 🧪 Description
Chronically elevated blood glucose levels indicate poor glycemic control, increasing the risk of insulin resistance, inflammation, and vascular damage.

## 🔁 Triggered By
- [[Poor Diet]]
- [[Chronic Psychological Stress]]
- [[Circadian Disruption]]

## ⛓ Leads To
- [[Insulin Resistance]]
- [[Fatty Liver]]
- [[Type 2 Diabetes]]

## 📊 Measurable Biomarkers
- Fasting Glucose (>100 mg/dL)
- HbA1C (>5.6%)
- CGM Spikes (>30 mg/dL postprandial)

## 🔍 Detection Threshold
Defined as present if 2+ abnormal fasting readings or >15% CGM spikes over 7 days

## 📉 Downstream Risk Amplification
- Propagation Coefficient: `0.7`
- Risk Scaling Factor: `linear`

## 🛠 Influenced By
| Intervention         | Effect            | Evidence Level |
|----------------------|-------------------|----------------|
| [[Intermittent Fasting]] | Improves insulin sensitivity | High           |
| [[Low Glycemic Diet]]   | Reduces postprandial spikes | High           |

## 🧠 Model Notes
Key node for metabolic syndrome; triggers alert if A1C and glucose trend upward over 14 days
