---
type: node_logic
target_node: Hormonal Imbalance
category: biological_response
---

# 🧠 Node Logic — Hormonal Imbalance

## 🔑 Activation Criteria
- Irregularities in cortisol, thyroid, insulin, testosterone, estrogen, progesterone, or DHEA
- Cycle disruption (length, severity, missing)
- Low libido, mood instability, poor recovery

## 🔁 Risk Propagation
- [[Infertility]] (β = 0.75)
- [[PCOS]] (β = 0.8)
- [[Insulin Resistance]] (β = 0.6)
- [[Depressive Symptoms]] (β = 0.55)

- **Decay Half-Life**: 28–90 days depending on hormone system
- **Scaling**: Exponential during menstrual dysregulation or andropause

## 🚨 Alert Rules
- Trigger if multi-hormonal drift + cycle or libido issues present
- Recommend hormone panel, stress audit, diet review

## 🛠 Intervention Feedback
- Reassess in 4–8 weeks depending on sex and system involved
- Deactivate when cycle or lab markers normalize

## 🧠 Modeling Notes
Acts as a bridge node between stress, metabolism, fertility, and energy — multi-axis disruption is common
