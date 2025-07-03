---
type: dysfunction_state
modifiable: true
node_category: gut
tags: [gut, permeability, immune]
source_type: [stool test, symptom_log]
linked_model_inputs: [zonulin, LPS, GI_symptoms]
---

# Leaky Gut — Dysfunction Node

## ⚠️ Description
Increased intestinal permeability allows toxins, antigens, and microbes to cross the gut barrier — triggering systemic inflammation and immune dysfunction.

## 🔁 Triggered By
- [[Gut Dysbiosis]]
- [[Stress]]
- [[Poor Diet]]
- [[Environmental Toxins]]

## ⛓ Leads To
- [[Systemic Inflammation]]
- [[Autoimmune Disease]]
- [[Fatigue]]
- [[Mood Disorders]]

## 📊 Measurable Criteria
- Elevated zonulin
- LPS (lipopolysaccharide)
- GI panel markers of barrier dysfunction

## 🔍 Diagnostic Threshold
>2 elevated gut permeability markers or chronic GI symptoms + inflammation

## 📉 Risk Amplification
- Propagation Coefficient: `0.75`
- Acceleration Factor: `immune_amplifier`

## 🛠 Modifiable With
| Intervention             | Target Outcome       | Evidence Level |
|--------------------------|----------------------|----------------|
| [[Elimination Diet]]     | Reduces gut barrier load | High       |
| [[L-Glutamine + Zinc]]   | Supports mucosal repair | Moderate     |

## 🧠 Model Notes
Bi-directional interactions with gut microbiome, inflammation, and immune activation; critical in autoimmune and fatigue modeling
