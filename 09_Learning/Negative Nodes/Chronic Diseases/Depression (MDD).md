---
type: disease_outcome
modifiable: partially
node_category: diagnosis
tags: [chronic_disease, mental_health, affective]
source_type: [survey, clinical_dx]
linked_model_inputs: [PHQ9, SHAPS, HRV_baseline]
---

# Depression (MDD) — Final Disease Node

## 🧨 Description
Major Depressive Disorder is a persistent affective condition characterized by low mood, anhedonia, and functional impairment. Rooted in HPA axis dysregulation, inflammation, and circadian disruption.

## 🔁 Upstream Dysfunctions
- [[Anhedonia]]
- [[Chronic Stress]]
- [[Low HRV]]
- [[Sleep Fragmentation]]
- [[Hormonal Axis Disruption]]

## 🔁 Contributing Root Causes
- [[Social Isolation]]
- [[Poor Sleep Quality]]
- [[Trauma]]

## 🔬 Diagnostic Criteria
- PHQ-9 ≥10
- ≥5 DSM-V symptoms for ≥2 weeks
- Functional or social impairment

## 🩺 Symptoms / Clinical Findings
- Persistent sadness
- Loss of interest
- Appetite or sleep changes
- Suicidal ideation

## 📉 Model Implications
- Core affective label for mental health classifier
- Bidirectional loops with sleep, metabolic, and inflammation pathways

## 🛠 Disease Management Levers
| Lever                 | Effect                 | Evidence Level |
|------------------------|------------------------|----------------|
| [[CBT / Therapy]]      | Improves mood + function | High         |
| [[Exercise Protocol]]  | Comparable to SSRIs     | High           |

## 🧠 Modeling Notes
Key to psychosocial modeling loop; early detection should focus on combined sleep + mood + HRV drift over time
