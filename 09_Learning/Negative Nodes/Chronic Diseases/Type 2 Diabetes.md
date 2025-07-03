---
type: disease_outcome
modifiable: partially
node_category: diagnosis
tags: [chronic_disease, metabolic, diabetes]
source_type: [lab, clinical_dx]
linked_model_inputs: [A1C, fasting_glucose, OGTT]
---

# Type 2 Diabetes — Final Disease Node

## 🧨 Description
A chronic metabolic disorder characterized by insulin resistance and beta-cell dysfunction, resulting in sustained hyperglycemia. One of the most preventable and costly chronic conditions worldwide.

## 🔁 Upstream Dysfunctions
- [[Insulin Resistance]]
- [[Glucose Intolerance]]
- [[Visceral Obesity]]
- [[Fatty Liver (NAFLD)]]

## 🔁 Contributing Root Causes
- [[Poor Diet]]
- [[Physical Inactivity]]
- [[Chronic Psychological Stress]]

## 🔬 Diagnostic Criteria
- HbA1c ≥6.5%
- Fasting glucose ≥126 mg/dL
- 2-hr OGTT ≥200 mg/dL

## 🩺 Symptoms / Clinical Findings
- Polyuria
- Fatigue
- Blurred vision
- Slow wound healing

## 📉 Model Implications
- Flagged as “terminal metabolic node”
- Backpropagation risk increases for kidneys, nerves, and vasculature
- Used as a core AI training label (classification: positive)

## 🛠 Disease Management Levers
| Lever                        | Effect                          | Evidence Level |
|-----------------------------|----------------------------------|----------------|
| [[Low Carb / Ketogenic Diet]] | Reverses insulin resistance     | High           |
| [[GLP-1 Agonists]]          | Lower glucose, reduce appetite   | High           |

## 🧠 Modeling Notes
Essential node for all risk prediction and preventative intervention engines — primary label for metabolic AI models
