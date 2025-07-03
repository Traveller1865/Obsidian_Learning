---
type: node_logic
target_node: Mitochondrial Dysfunction
category: biological_response
---

# 🧠 Node Logic — Mitochondrial Dysfunction

## 🔑 Activation Criteria
- Elevated lactate, ammonia, or reactive oxygen species (ROS)
- Fatigue + exercise intolerance + poor HR recovery
- Low VO₂ max with low HRV + persistent brain fog

## 🔁 Risk Propagation
- [[Chronic Fatigue]] (β = 0.8)
- [[Neurodegeneration]] (β = 0.6)
- [[Hormonal Imbalance]] (β = 0.55)
- [[Immune Dysfunction]] (β = 0.6)

- **Decay Half-Life**: 45 days
- **Scaling**: Amplifies under sustained oxidative stress or poor recovery

## 🚨 Alert Rules
- Trigger if energy score <5/10 for 10+ days + 2+ mitochondrial markers abnormal
- Recommend mitochondrial support (CoQ10, B2, PQQ), exercise taper, breathwork

## 🛠 Intervention Feedback
- Deactivate if energy, lactate, or VO₂ max normalize over 2-week check-in

## 🧠 Modeling Notes
Early decline often mistaken for burnout or mood — foundational in chronic fatigue, brain fog, and degenerative risk states
