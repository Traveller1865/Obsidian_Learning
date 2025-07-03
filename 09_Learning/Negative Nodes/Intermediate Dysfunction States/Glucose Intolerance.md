---
type: dysfunction_state
modifiable: true
node_category: pre-disease
tags: [glucose, insulin, metabolic]
source_type: [lab, CGM, wearable]
linked_model_inputs: [CGM_spikes, A1C, OGTT_curve]
---

# Glucose Intolerance — Dysfunction Node

## ⚠️ Description
A transitional metabolic state where the body has impaired ability to manage glucose after meals. A precursor to insulin resistance and Type 2 Diabetes.

## 🔁 Triggered By
- [[Elevated Blood Glucose]]
- [[High Cortisol]]
- [[Poor Diet]]

## ⛓ Leads To
- [[Insulin Resistance]]
- [[Type 2 Diabetes]]

## 📊 Measurable Criteria
- A1C: 5.6%–6.4%
- 2-hr OGTT: 140–199 mg/dL
- Frequent CGM spikes >30 mg/dL postprandial

## 🔍 Diagnostic Threshold
Two abnormal glycemic markers or continuous CGM variability exceeding 20% over 7 days

## 📉 Risk Amplification
- Propagation Coefficient: `0.75`
- Acceleration Factor: `multiplicative`

## 🛠 Modifiable With
| Intervention             | Target Outcome               | Evidence Level |
|--------------------------|------------------------------|----------------|
| [[Low Glycemic Diet]]    | Stabilizes postprandial spikes | High         |
| [[Intermittent Fasting]] | Improves glucose sensitivity  | High         |

## 🧠 Model Notes
This is a key “turning point” node — reversible in early stages and ideal for AI-triggered dietary intervention
