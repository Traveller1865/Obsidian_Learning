---
type: dysfunction_state
modifiable: true
node_category: vascular
tags: [blood_pressure, dizziness, autonomic]
source_type: [wearable, symptom_log]
linked_model_inputs: [BP_post_meal, dizziness_score]
---

# Postprandial Hypotension — Dysfunction Node

## ⚠️ Description
A drop in blood pressure after eating, leading to dizziness, fatigue, or fainting. Indicates autonomic or vascular instability, especially in aging or insulin resistance.

## 🔁 Triggered By
- [[Autonomic Dysfunction]]
- [[Insulin Resistance]]
- [[High Carb Diet]]

## ⛓ Leads To
- [[Cognitive Decline]]
- [[Falls / Injuries]]
- [[Fatigue States]]

## 📊 Measurable Criteria
- SBP drops >20 mmHg within 2 hours post-meal
- Associated dizziness, fatigue, or cognitive blunting

## 🔍 Diagnostic Threshold
Confirmed if ≥2 symptomatic BP drops postprandially over a week

## 📉 Risk Amplification
- Propagation Coefficient: `0.5`
- Acceleration Factor: `aging_bias`

## 🛠 Modifiable With
| Intervention           | Target Outcome                | Evidence Level |
|------------------------|-------------------------------|----------------|
| [[Meal Spacing / Lower Carb Meals]] | Stabilize BP response   | Moderate       |
| [[Hydration / Electrolytes]]        | Support vascular tone   | Moderate       |

## 🧠 Model Notes
Highly underdiagnosed — useful signal of vascular and nervous system fragility, especially in aging populations
