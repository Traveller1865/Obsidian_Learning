---
type: node_logic
target_node: Poor Sleep Quality
category: root_cause
---

# 🧠 Node Logic — Poor Sleep Quality

## 🔑 Activation Criteria
- Sleep efficiency <80% (wearable)
- Sleep latency >30 min for 3+ nights/week
- Subjective sleep score <6/10 for ≥5 days

## 🔁 Risk Propagation
- [[Sleep Fragmentation]] (β = 0.8)
- [[Low HRV]] (β = 0.65)
- [[High Cortisol]] (β = 0.7)
- [[Insulin Resistance]] (β = 0.55)
- [[Depressive Symptoms]] (β = 0.5)

- **Decay Half-Life**: 7 days
- **Scaling**: Exponential if paired with stress, inactivity, or stimulant use

## 🚨 Alert Rules
- Trigger if <80% efficiency + HRV trending down + mood/cognition impacted
- Recommend sleep hygiene tracker, melatonin-free recovery protocol

## 🛠 Intervention Feedback
- Deactivate if sleep score improves >6.5 + latency <20 min for 5 days

## 🧠 Modeling Notes
Sleep is a first domino — errors propagate quickly into hormonal, mood, and metabolic loops
