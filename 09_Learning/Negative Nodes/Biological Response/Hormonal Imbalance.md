---
type: biological_response
modifiable: semi
node_category: endocrine
tags: [hormones, imbalance, metabolism]
source_type: [lab, wearable-inferred]
linked_model_inputs: [cortisol_rhythm, leptin, insulin, melatonin]
---

# Hormonal Imbalance — Biological Response Node

## 🧪 Description
Disruptions in key hormonal systems — including cortisol, melatonin, insulin, thyroid, and sex hormones — that destabilize metabolic, reproductive, and mental health pathways.

## 🔁 Triggered By
- [[Circadian Disruption]]
- [[High Cortisol]]
- [[Poor Diet]]
- [[Poor Sleep Quality]]

## ⛓ Leads To
- [[Infertility]]
- [[Obesity]]
- [[Depression]]
- [[Type 2 Diabetes]]

## 📊 Measurable Biomarkers
- AM/PM cortisol slope
- Melatonin onset
- Leptin & ghrelin levels
- TSH / Free T3 / T4

## 🔍 Detection Threshold
Dysregulation in ≥2 major hormone pathways or loss of diurnal rhythm

## 📉 Downstream Risk Amplification
- Propagation Coefficient: `0.7`
- Risk Scaling Factor: `nonlinear`

## 🛠 Influenced By
| Intervention         | Effect                    | Evidence Level |
|----------------------|----------------------------|----------------|
| [[Circadian Realignment]] | Normalizes hormonal axes | High           |
| [[Adaptogens]]       | Supports adrenal balance   | Moderate       |

## 🧠 Model Notes
Feeds into multiple metabolic and mental health pathways; often coexists with sleep and stress-related dysfunctions
