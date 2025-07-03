---
type: disease_outcome
modifiable: partially
node_category: diagnosis
tags: [chronic_disease, reproductive]
source_type: [lab, imaging, clinical_dx]
linked_model_inputs: [FSH, LH, TSH, sperm_count]
---

# Infertility — Final Disease Node

## 🧨 Description
Failure to achieve pregnancy after 12 months of unprotected intercourse. Reflects dysfunction in the HPA/HPG axis, hormone signaling, oxidative stress, and inflammation.

## 🔁 Upstream Dysfunctions
- [[Hormonal Axis Disruption]]
- [[Oxidative Stress]]
- [[Insulin Resistance]]
- [[Subclinical Hypothyroid]]

## 🔁 Contributing Root Causes
- [[Chronic Stress]]
- [[Poor Diet]]
- [[Environmental Toxins]]

## 🔬 Diagnostic Criteria
- Hormone panels (FSH, LH, TSH, AMH, testosterone)
- Ultrasound (PCOS, fibroids, structural issues)
- Sperm analysis (motility, count, morphology)

## 🩺 Symptoms / Clinical Findings
- Irregular cycles
- Low libido
- Sexual dysfunction
- Emotional distress

## 📉 Model Implications
- Key outcome for metabolic-endocrine modeling
- Use for early flagging based on lifestyle and hormone drift

## 🛠 Disease Management Levers
| Lever                     | Effect                  | Evidence Level |
|---------------------------|--------------------------|----------------|
| [[Hormonal Rebalancing Protocols]] | Restore ovulation or sperm health | Moderate |
| [[Weight Loss in PCOS]]  | Improves fertility       | High           |

## 🧠 Modeling Notes
Best modeled as a confluence node from endocrine + inflammation + mitochondrial pathways — often reversible
