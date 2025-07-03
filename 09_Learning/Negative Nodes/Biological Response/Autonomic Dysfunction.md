---
type: biological_response
modifiable: semi
node_category: nervous_system
tags: [autonomic, vagal, HRV]
source_type: [wearable, HRV, proxy markers]
linked_model_inputs: [HRV_baseline, resting_heart_rate, stress_index]
---

# Autonomic Dysfunction — Biological Response Node

## 🧪 Description
A disruption in autonomic nervous system balance, typically manifesting as reduced parasympathetic (vagal) tone and increased sympathetic dominance — linked to cardiovascular, metabolic, and emotional regulation.

## 🔁 Triggered By
- [[Chronic Psychological Stress]]
- [[Physical Inactivity]]
- [[Poor Sleep Quality]]

## ⛓ Leads To
- [[Hypertension]]
- [[Cardiovascular Disease]]
- [[Depression]]

## 📊 Measurable Biomarkers
- HRV (low vs. individual baseline)
- Resting heart rate
- Respiratory rate variability

## 🔍 Detection Threshold
HRV consistently >15% below rolling baseline for 7+ days

## 📉 Downstream Risk Amplification
- Propagation Coefficient: `0.6`
- Risk Scaling Factor: `threshold with decay`

## 🛠 Influenced By
|
