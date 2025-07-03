---
type: node_logic
target_node: Sympathetic Dominance
category: biological_response
---

# 🧠 Node Logic — Sympathetic Dominance

## 🔑 Activation Criteria
- Low HRV (<40 ms) + high LF/HF ratio (>2.0)
- Persistent RHR elevation (>10 bpm above baseline)
- Symptoms: anxiety, jaw tension, shallow breathing

## 🔁 Risk Propagation
- [[High Cortisol]] (β = 0.85)
- [[Sleep Fragmentation]] (β = 0.7)
- [[Autonomic Dysfunction]] (β = 0.65)
- [[Cardiovascular Disease]] (β = 0.6)

- **Decay Half-Life**: 10–14 days with rest + vagal tone recovery
- **Scaling**: Steep under stress + stimulant use

## 🚨 Alert Rules
- Trigger if HRV trend down + RHR up + stress symptoms cluster for 5+ days
- Recommend HRV training, breathing, cold exposure (if tolerable)

## 🛠 Intervention Feedback
- Reassess HRV and RHR trend after 1 week of protocol

## 🧠 Modeling Notes
Autonomic bias node — causes many false alarms if not contextually understood; important for overtraining and fatigue loops
