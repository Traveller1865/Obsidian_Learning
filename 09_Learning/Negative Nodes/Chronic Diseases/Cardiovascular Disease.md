---
type: disease_outcome
modifiable: partially
node_category: diagnosis
tags: [chronic_disease, cardiovascular]
source_type: [imaging, labs, clinical_dx]
linked_model_inputs: [BP, cholesterol, CAC_score]
---

# Cardiovascular Disease — Final Disease Node

## 🧨 Description
A broad category including coronary artery disease, heart failure, stroke, and arrhythmias. The leading global cause of death, rooted in metabolic and vascular dysfunction.

## 🔁 Upstream Dysfunctions
- [[Hypertension]]
- [[Endothelial Dysfunction]]
- [[Systemic Inflammation]]
- [[Visceral Obesity]]

## 🔁 Contributing Root Causes
- [[Poor Diet]]
- [[Chronic Psychological Stress]]
- [[Environmental Toxins]]

## 🔬 Diagnostic Criteria
- Coronary calcium score >100
- Carotid intima-media thickness (CIMT)
- History of MI, angina, CHF, or stroke

## 🩺 Symptoms / Clinical Findings
- Chest pain
- Dyspnea
- Palpitations
- Edema or fainting

## 📉 Model Implications
- Use as multiclass classifier label (CAD, CHF, Stroke subclasses)
- Risk scoring should begin in teenage years with lifestyle data

## 🛠 Disease Management Levers
| Lever                  | Effect                  | Evidence Level |
|------------------------|--------------------------|----------------|
| [[Statins]]            | Reduce LDL, stabilize plaque | High       |
| [[Exercise Protocol]]  | Improves HRV, lowers BP  | High           |

## 🧠 Modeling Notes
Propagation of vascular damage backward into sleep, renal, and cognitive nodes — multipath terminal node
