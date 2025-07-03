---
type: disease_outcome
modifiable: partially
node_category: diagnosis
tags: [chronic_disease, autoimmune]
source_type: [lab, symptom_log, clinical_dx]
linked_model_inputs: [ANA, CRP, cytokines]
---

# Autoimmune Disease — Final Disease Node

## 🧨 Description
A class of conditions where the immune system attacks self-tissues. Includes lupus, rheumatoid arthritis, MS, Hashimoto’s, and others. Strongly tied to gut, stress, and toxin exposure.

## 🔁 Upstream Dysfunctions
- [[Leaky Gut]]
- [[Systemic Inflammation]]
- [[Immune Dysfunction]]
- [[Gut Dysbiosis]]

## 🔁 Contributing Root Causes
- [[Chronic Psychological Stress]]
- [[Environmental Toxins]]
- [[Poor Diet]]

## 🔬 Diagnostic Criteria
- Positive ANA or disease-specific autoantibodies
- Clinical symptom constellation (e.g., fatigue, joint pain)
- Diagnostic imaging / biopsy if applicable

## 🩺 Symptoms / Clinical Findings
- Fatigue
- Joint pain / stiffness
- Skin rashes
- Brain fog or malaise

## 📉 Model Implications
- Trigger early warning when inflammatory + gut + stress nodes co-activate
- Use for multiclass labeling (RA, MS, SLE, etc.)

## 🛠 Disease Management Levers
| Lever                     | Effect                         | Evidence Level |
|---------------------------|----------------------------------|----------------|
| [[Autoimmune Paleo Diet]] | Reduces flares                  | Moderate       |
| [[Biologics / Immunomodulators]] | Suppress immune overactivity | High        |

## 🧠 Modeling Notes
Highly heterogeneous; use clustering + longitudinal symptom tracking to simulate personalized autoimmune trajectories
