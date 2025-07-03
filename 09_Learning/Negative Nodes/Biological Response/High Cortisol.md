---
type: biological_response
modifiable: semi
node_category: hormonal
tags: [hormone, stress, cortisol]
source_type: [saliva, wearable proxy, HRV]
linked_model_inputs: [AM_cortisol, stress_index, HRV_baseline]
---

# High Cortisol — Biological Response Node

## 🧪 Description
Chronically elevated cortisol from persistent stress dysregulates metabolism, suppresses immunity, and disrupts circadian rhythms.

## 🔁 Triggered By
- [[Chronic Psychological Stress]]
- [[Poor Sleep Quality]]
- [[Circadian Disruption]]

## ⛓ Leads To
- [[Insulin Resistance]]
- [[Immune Dysfunction]]
- [[Poor Sleep Quality]]

## 📊 Measurable Biomarkers
- Morning cortisol (saliva)
- Flattened cortisol slope
- HRV suppression

## 🔍 Detection Threshold
AM/PM cortisol ratio abnormal for ≥3 days or HRV consistently low relative to baseline

## 📉 Downstream Risk Amplification
- Propagation Coefficient: `0.6`
- Risk Scaling Factor: `logarithmic`

## 🛠 Influenced By
| Intervention         | Effect       | Evidence Level |
|----------------------|--------------|----------------|
| [[Meditation]]       | Lowers cortisol | High         |
| [[Therapy/CBT]]      | Normalizes stress response | Moderate     |

## 🧠 Model Notes
Used as a feedback loop node for psychosocial resilience modeling; threshold-based decay applied if interventions sustained
