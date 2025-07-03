---
type: node_logic
target_node: Social Isolation
category: root_cause
---

# 🧠 Node Logic — Social Isolation

## 🔑 Activation Criteria
- No significant social interaction for >5 consecutive days (self-report or passive log)
- Subjective loneliness ≥7/10
- Absence of positive social affect markers in journal or passive audio data

## 🔁 Risk Propagation
- [[Depressive Symptoms]] (β = 0.75)
- [[Chronic Psychological Stress]] (β = 0.6)
- [[Sleep Fragmentation]] (β = 0.5)
- [[Low HRV]] (β = 0.55)
- [[Cognitive Decline]] (β = 0.4)

- **Decay Half-Life**: 21 days (slow recovery)
- **Scaling**: Stepwise — sharp drop once reconnection is logged

## 🚨 Alert Rules
- Trigger if loneliness + mood score <6 + no social events logged for 7+ days
- Recommend journaling, outreach nudge, “Call a friend” challenge

## 🛠 Intervention Feedback
- Reassess social mood and recovery markers after 3 interactions
- Deactivate if social log improves + positive affect returns

## 🧠 Modeling Notes
Silent but powerful — social withdrawal is both a trigger and marker of multi-domain decline
