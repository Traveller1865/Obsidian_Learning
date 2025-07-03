---
type: node_logic
target_node: Obstructive Sleep Apnea
category: chronic_disease
---

# 🧠 Node Logic — Obstructive Sleep Apnea

## 🔑 Activation Criteria
- AHI >5 (mild), >15 (moderate), >30 (severe) via PSG
- Loud snoring + observed apneas or gasping
- Symptoms: morning headaches, dry mouth, excessive daytime sleepiness

## 🔁 Upstream Contributors
- [[Visceral Obesity]] (β = 0.8)
- [[Sleep Fragmentation]] (β = 0.75)
- [[Autonomic Dysfunction]] (β = 0.65)
- [[High Cortisol]] (β = 0.6)

- **Progression Window**: Chronic if untreated
- **Scaling**: Exponential with neck circumference and weight gain

## 🚨 Alert Rules
- Trigger if sleep quality low + ESS >10 + snore log
- Recommend home sleep study or PSG, CPAP referral, airway support

## 🛠 Intervention Feedback
- Monitor AHI, sleep efficiency, oxygen desaturation
- Deactivate if AHI controlled and symptoms resolved

## 🧠 Modeling Notes
Sleep apnea is a high-leverage node for metabolic, cognitive, and cardiac repair — detect early in at-risk users
