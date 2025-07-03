---
type: dysfunction_state
modifiable: true
node_category: endocrine
tags: [HPA, thyroid, gonadal, hormonal]
source_type: [lab, symptom_log]
linked_model_inputs: [TSH, cortisol_rhythm, testosterone, estrogen]
---

# Hormonal Axis Disruption — Dysfunction Node

## ⚠️ Description
A breakdown in hypothalamic-pituitary-end organ signaling (e.g. adrenal, thyroid, gonads). Disrupts energy, libido, sleep, and mood — often caused by stress, inflammation, and circadian mismatch.

## 🔁 Triggered By
- [[Chronic Stress]]
- [[Sleep Fragmentation]]
- [[Circadian Disruption]]
- [[Inflammation]]

## ⛓ Leads To
- [[Infertility]]
- [[Fatigue]]
- [[Weight Gain]]
- [[Depression]]

## 📊 Measurable Criteria
- Abnormal cortisol slope or TSH/T3 mismatch
- Low testosterone (men) / low estradiol (women)

## 🔍 Diagnostic Threshold
≥2 hormone panels with abnormal HPA, HPT, or HPG markers + matching symptoms

## 📉 Risk Amplification
- Propagation Coefficient: `0.8`
- Acceleration Factor: `hormonal_drift`

## 🛠 Modifiable With
| Intervention         | Target Outcome         | Evidence Level |
|----------------------|------------------------|----------------|
| [[Sleep + Light Timing Reset]] | Normalizes rhythm | High        |
| [[Adaptogens / Micronutrient Support]] | Rebuilds signaling | Moderate   |

## 🧠 Model Notes
Cross-domain node: connects endocrine, affective, and metabolic loops; critical in long-term risk stratification
