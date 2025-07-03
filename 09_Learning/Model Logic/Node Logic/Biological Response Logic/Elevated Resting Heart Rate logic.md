---
type: node_logic
target_node: Elevated Resting Heart Rate
category: biological_response
---

# 🧠 Node Logic — Elevated Resting Heart Rate

## 🔑 Activation Criteria
- Resting HR >80 bpm (persistent, wearable)
- RHR >10 bpm above personal baseline for ≥7 days
- Poor RHR recovery after sleep or stress

## 🔁 Risk Propagation
- [[Cardiovascular Disease]] (β = 0.75)
- [[Hypertension]] (β = 0.6)
- [[Fatigue]] (β = 0.55)
- [[Autonomic Dysfunction]] (β = 0.7)

- **Decay Half-Life**: 7–10 days (cardio-respiratory adaptable)
- **Scaling**: Amplified by poor sleep or inactivity

## 🚨 Alert Rules
- Alert if 7-day RHR average > baseline + HRV < baseline
- Recommend Zone 2 exercise, stress tracking, breathing rehab

## 🛠 Intervention Feedback
- Deactivate if RHR drops <75 bpm or returns to baseline for 7 days

## 🧠 Modeling Notes
Fast-reacting wearable biomarker — sensitive to stress, infection, fitness, and sleep quality
