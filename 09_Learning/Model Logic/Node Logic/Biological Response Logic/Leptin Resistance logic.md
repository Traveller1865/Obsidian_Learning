---
type: node_logic
target_node: Leptin Resistance
category: biological_response
---

# 🧠 Node Logic — Leptin Resistance

## 🔑 Activation Criteria
- Leptin >20 ng/mL (men) / >30 ng/mL (women)
- Self-reported constant hunger + weight gain despite high intake
- Weak satiety signal post-meal (app score <4/10)

## 🔁 Risk Propagation
- [[Obesity]] (β = 0.9)
- [[Insulin Resistance]] (β = 0.7)
- [[Sleep Fragmentation]] (β = 0.6)
- [[Fatty Liver (NAFLD)]] (β = 0.5)

- **Decay Half-Life**: 30–45 days
- **Scaling**: Synergistic with circadian disruption and sugar overexposure

## 🚨 Alert Rules
- Trigger if leptin + hunger + weight gain cluster active >10 days
- Recommend fasting window, resistance training, inflammation reduction

## 🛠 Intervention Feedback
- Reassess satiety, fasting labs, and weight trend in 14–21 days

## 🧠 Modeling Notes
Crucial but underused metabolic signal — marks satiety loop breakdown; foundational for weight-loss resistance
