---
type: biological_response
modifiable: true
node_category: nervous_system
tags: [HRV, vagal_tone, resilience, positive_marker]
source_type: [wearable]
linked_model_inputs: [baseline_HRV, stress_resilience_index]
---

# High HRV — Biological Response Node

## 🧪 Description
High heart rate variability (HRV) reflects a flexible, adaptive autonomic nervous system with strong vagal tone. It is associated with greater physical recovery, emotional regulation, and long-term health.

## 🔁 Promoted By
- [[Box Breathing]]
- [[Quality Sleep]]
- [[Circadian Stability]]
- [[Social Connection]]

## ⛓ Protects Against
- [[Autonomic Dysfunction]]
- [[Depression]]
- [[Hypertension]]
- [[Cardiovascular Disease]]

## 📊 Measurable Biomarkers
- HRV (RMSSD, SDNN above personalized baseline)
- HRV reactivity to stress (acute recovery curve)

## 🔍 Detection Threshold
Defined as ≥15% above personal 30-day rolling baseline or trending upward over 10+ days

## 📉 Downstream Protective Scaling
- Protection Coefficient: `-0.6`
- Dampening Factor: `inverse decay` to risk nodes

## 🛠 Strengthened By
| Behavior               | Effect                 | Evidence Level |
|------------------------|------------------------|----------------|
| [[Meditation Practice]]| Improves vagal tone    | High           |
| [[Zone 2 Training]]    | Boosts parasympathetic reserve | High |
| [[Evening Wind-down]]  | Stabilizes nervous system | Moderate  |

## 🧠 Model Notes
Acts as a **negative weight** on downstream stress and inflammation pathways. Can be used in feedback loops to simulate resilience-building over time.
