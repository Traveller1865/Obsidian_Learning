---
type: node_logic
target_node: Chronic Psychological Stress
category: root_cause
---

# 🧠 Node Logic — Chronic Psychological Stress

## 🔑 Activation Criteria
- Self-reported stress ≥6/10 for ≥5 days in 2 weeks
- Elevated cortisol pattern (flat AM/PM slope or high PM)
- Wearable HRV suppression (LF/HF imbalance or HRV < baseline by >15%)

## 🔁 Risk Propagation
- [[High Cortisol]] (β = 0.9)
- [[Sleep Fragmentation]] (β = 0.75)
- [[Systemic Inflammation]] (β = 0.6)
- [[Depressive Symptoms]] (β = 0.65)

- **Decay Half-Life**: 14 days if acute event resolved  
- **Scaling**: Linear with mood + HRV input

## 🚨 Alert Rules
- Alert if combined HRV suppression + mood score <5 for 5+ days
- Recommend mindfulness, journaling, CBT prompt, social contact

## 🛠 Intervention Feedback
- Reassess HRV and mood trends after 10 days of adherence
- Deactivation if symptom log + wearable stabilize

## 🧠 Modeling Notes
Stress is both a cause and amplifier — feedback loop with sleep, mood, immune, endocrine nodes
