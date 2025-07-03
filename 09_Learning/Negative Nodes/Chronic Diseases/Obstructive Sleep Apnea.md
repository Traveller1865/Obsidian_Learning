---
type: disease_outcome
modifiable: partially
node_category: diagnosis
tags: [chronic_disease, respiratory, sleep]
source_type: [PSG, wearable, symptom_log]
linked_model_inputs: [AHI, snore_index, SpO2_variability]
---

# Obstructive Sleep Apnea — Final Disease Node

## 🧨 Description
A condition where the airway collapses or becomes blocked during sleep, leading to intermittent oxygen deprivation and arousals. Strongly linked to obesity, inflammation, and cardiovascular disease.

## 🔁 Upstream Dysfunctions
- [[Visceral Obesity]]
- [[Sleep Fragmentation]]
- [[Low HRV]]
- [[Circadian Disruption]]

## 🔁 Contributing Root Causes
- [[Poor Sleep Hygiene]]
- [[Alcohol Use]]
- [[Anatomical Risk Factors]]

## 🔬 Diagnostic Criteria
- Apnea-Hypopnea Index (AHI) ≥5
- Confirmed via PSG or validated wearable

## 🩺 Symptoms / Clinical Findings
- Loud snoring
- Daytime sleepiness
- Morning headaches
- Cognitive impairment

## 📉 Model Implications
- Creates systemic propagation via inflammation, fatigue, and BP nodes
- Must be considered in metabolic and cognitive dysfunction modeling

## 🛠 Disease Management Levers
| Lever                     | Effect                  | Evidence Level |
|---------------------------|--------------------------|----------------|
| [[CPAP Therapy]]          | Reduces apneas and inflammation | High     |
| [[Weight Loss]]           | Improves airway patency  | High           |

## 🧠 Modeling Notes
Closed-loop node feeding back into sleep, cortisol, and cardiovascular systems; wearable-based prediction models strongly encouraged
