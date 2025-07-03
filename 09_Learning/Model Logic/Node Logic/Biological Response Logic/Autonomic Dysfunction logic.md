---
type: node_logic
target_node: Autonomic Dysfunction
category: biological_response
---

# 🧠 Node Logic — Autonomic Dysfunction

## 🔑 Activation Criteria
- Low HRV (<40 ms baseline) or high LF/HF ratio >2.0 (wearable)
- Elevated resting HR + poor HRV recovery post-stressor
- Self-reported dizziness, fatigue, heat intolerance (POTS screen)

## 🔁 Risk Propagation
- [[Sleep Fragmentation]] (β = 0.7)
- [[Sympathetic Dominance]] (β = 0.8)
- [[Digestive Dysregulation]] (β = 0.6)
- [[Depressive Symptoms]] (β = 0.5)

- **Decay Half-Life**: 21 days
- **Scaling**: Exponential — dysautonomia worsens downstream HR, temp, digestion systems

## 🚨 Alert Rules
- Trigger if HRV suppressed + elevated RHR for 10+ days
- Recommend breathing protocols, hydration, vagal tone stimulation

## 🛠 Intervention Feedback
- Reassess HRV, orthostatic tolerance, fatigue
- Deactivate if recovery markers improve for 7 days

## 🧠 Modeling Notes
Multisystem warning — autonomic dysfunction often masks as fatigue, poor digestion, or temperature instability
