---
type: dysfunction_state
modifiable: true
node_category: affective
tags: [mood, depression, neuroendocrine]
source_type: [survey, mood_log]
linked_model_inputs: [mood_score, SHAPS, PHQ9]
---

# Depressive Symptoms — Dysfunction Node

## ⚠️ Description
Persistent low mood, loss of motivation, or cognitive sluggishness without a formal diagnosis of Major Depressive Disorder. Predicts long-term mental and physical decline.

## 🔁 Triggered By
- [[Chronic Stress]]
- [[Anhedonia]]
- [[Sleep Fragmentation]]
- [[Inflammation]]

## ⛓ Leads To
- [[Major Depression]]
- [[Cognitive Decline]]
- [[Social Withdrawal]]
- [[Knowledge Vault/Scientific Papers/Metabolic Syndrome]]

## 📊 Measurable Criteria
- PHQ-9 score: 5–14 (mild to moderate)
- Mood score trend declining for ≥14 days

## 🔍 Diagnostic Threshold
≥2 persistent mood symptoms for >2 weeks, not meeting full MDD criteria

## 📉 Risk Amplification
- Propagation Coefficient: `0.7`
- Acceleration Factor: `cognitive_downshift`

## 🛠 Modifiable With
| Intervention             | Target Outcome           | Evidence Level |
|--------------------------|--------------------------|----------------|
| [[Exercise Protocol]]    | Lifts mood, improves cognition | High     |
| [[Therapy / CBT]]        | Improves thought patterns | High         |

## 🧠 Model Notes
Flag early to prevent full affective disorder onset — interacts recursively with fatigue, sleep, and inflammation nodes
