---
type: node_logic
target_node: Circadian Disruption
category: root_cause
---

# 🧠 Node Logic — Circadian Disruption

## 🔑 Activation Criteria
- Sleep onset variability >90 min over a week
- Low AM light exposure or high PM brightness (wearable lux >300 at 11 PM)
- Mid-sleep time drift >2 hours on weekends vs weekdays

## 🔁 Risk Propagation
- [[Hormonal Axis Disruption]] (β = 0.7)
- [[Insulin Resistance]] (β = 0.6)
- [[Sleep Fragmentation]] (β = 0.8)
- [[Depressive Symptoms]] (β = 0.55)

- **Decay Half-Life**: 10 days
- **Scaling**: Exponential risk if sleep and light rhythm diverge

## 🚨 Alert Rules
- Alert if bedtime drift >90 min + sleep efficiency <80% + evening lux >200 for 3+ days
- Recommend wake-time anchor, morning sunlight, blue light filters

## 🛠 Intervention Feedback
- Deactivation if onset variance drops <30 min and sleep stabilizes for 7 days

## 🧠 Modeling Notes
Circadian drift silently shifts metabolic and endocrine balance — high leverage lifestyle node
