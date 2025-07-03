---
type: dysfunction_state
modifiable: true
node_category: sleep
tags: [sleep, circadian, neural]
source_type: [wearable, sleep_log, PSG]
linked_model_inputs: [sleep_efficiency, sleep_latency, REM_pct]
---

# Sleep Fragmentation — Dysfunction Node

## ⚠️ Description
Frequent arousals or transitions between sleep stages that disrupt sleep continuity. Contributes to fatigue, insulin resistance, and mood instability.

## 🔁 Triggered By
- [[Poor Sleep Quality]]
- [[High Cortisol]]
- [[Circadian Disruption]]
- [[Anhedonia]]

## ⛓ Leads To
- [[Chronic Fatigue]]
- [[Insulin Resistance]]
- [[Depression]]
- [[Hormonal Imbalance]]

## 📊 Measurable Criteria
- Sleep efficiency <75%
- ≥4 nightly awakenings
- REM <15% or N3 <10%

## 🔍 Diagnostic Threshold
Fragmented sleep for ≥4 nights over a 7-day period confirmed by wearable or PSG

## 📉 Risk Amplification
- Propagation Coefficient: `0.7`
- Acceleration Factor: `cognitive_depreciation`

## 🛠 Modifiable With
| Intervention         | Target Outcome         | Evidence Level |
|----------------------|------------------------|----------------|
| [[Sleep Hygiene Protocol]] | Improves continuity | High           |
| [[Magnesium / Glycine]]    | Reduces sleep latency | Moderate     |

## 🧠 Model Notes
Acts as a silent root of downstream emotional and metabolic instability — early intervention here improves systemic resilience
