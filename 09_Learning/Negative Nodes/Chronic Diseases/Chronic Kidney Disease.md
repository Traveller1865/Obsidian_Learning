---
type: disease_outcome
modifiable: partially
node_category: diagnosis
tags: [chronic_disease, renal, CKD]
source_type: [lab, imaging, clinical_dx]
linked_model_inputs: [creatinine, eGFR, albuminuria]
---

# Chronic Kidney Disease — Final Disease Node

## 🧨 Description
Progressive loss of kidney function often driven by diabetes, hypertension, and inflammation. Silent in early stages, yet devastating in later phases (ESRD, dialysis).

## 🔁 Upstream Dysfunctions
- [[Hypertension]]
- [[Type 2 Diabetes]]
- [[Systemic Inflammation]]
- [[Oxidative Stress]]

## 🔁 Contributing Root Causes
- [[Poor Diet]]
- [[Medication Toxicity]]
- [[Chronic Dehydration]]

## 🔬 Diagnostic Criteria
- eGFR <60 mL/min for ≥3 months
- Albumin:creatinine ratio >30 mg/g
- Elevated serum creatinine

## 🩺 Symptoms / Clinical Findings
- Fatigue
- Swelling
- Nocturia
- High blood pressure

## 📉 Model Implications
- Key endpoint for wearable + lab fusion modeling
- Triggers urgent alerts for progression reversal

## 🛠 Disease Management Levers
| Lever                     | Effect                   | Evidence Level |
|---------------------------|---------------------------|----------------|
| [[Low Sodium + DASH Diet]] | Stabilizes BP, reduces proteinuria | High   |
| [[ACE Inhibitors]]        | Renal protection          | High           |

## 🧠 Modeling Notes
Often unrecognized until stage 3 — ideal AI use case for silent progression detection from lifestyle + lab drift
