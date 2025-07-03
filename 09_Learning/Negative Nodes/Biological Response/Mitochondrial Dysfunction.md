---
type: biological_response
modifiable: semi
node_category: cellular
tags: [mitochondria, metabolism, energy]
source_type: [lab, functional panel]
linked_model_inputs: [ATP_level, lactate, VO2_max]
---

# Mitochondrial Dysfunction — Biological Response Node

## 🧪 Description
A state where mitochondrial efficiency is impaired, leading to reduced ATP production, increased ROS, fatigue, and impaired cellular repair — foundational to aging and disease.

## 🔁 Triggered By
- [[Oxidative Stress]]
- [[Poor Diet]]
- [[Environmental Toxins]]

## ⛓ Leads To
- [[Chronic Fatigue]]
- [[Neurodegeneration]]
- [[Cancer]]

## 📊 Measurable Biomarkers
- ATP production capacity
- VO2 max
- Lactate (fasted or post-exercise)

## 🔍 Detection Threshold
Confirmed via functional mitochondrial panel or consistent fatigue + poor VO2

## 📉 Downstream Risk Amplification
- Propagation Coefficient: `0.75`
- Risk Scaling Factor: `exponential + decay`

## 🛠 Influenced By
| Intervention           | Effect                | Evidence Level |
|------------------------|------------------------|----------------|
| [[Zone 2 Cardio]]      | Stimulates mitogenesis | High           |
| [[CoQ10 / NAD+]]       | Enhances function
