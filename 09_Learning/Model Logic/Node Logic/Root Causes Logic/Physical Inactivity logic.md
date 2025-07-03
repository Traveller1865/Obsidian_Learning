---
type: node_logic
target_node: Physical Inactivity
category: root_cause
---

# 🧠 Node Logic — Physical Inactivity

## 🔑 Activation Criteria
- Daily step count <5,000 for 5+ days/week (wearable)
- VO₂ max <35 (men) or <30 (women)
- Resting HR >80 bpm + low HRV baseline
- No logged exercise in past 7 days (survey or calendar)

## 🔁 Risk Propagation
- [[Insulin Resistance]] (β = 0.7)
- [[Visceral Obesity]] (β = 0.6)
- [[Low HRV]] (β = 0.65)
- [[Fatty Liver (NAFLD)]] (β = 0.6)
- [[Cardiovascular Disease]] (β = 0.75)

- **Decay Half-Life**: 14 days
- **Scaling**: Logarithmic — risk plateaus if inactive >30 days

## 🚨 Alert Rules
- Trigger if no logged movement + RHR > baseline + rising weight or glucose
- Recommend movement streak, walking habit nudges, activity reminders

## 🛠 Intervention Feedback
- Reassess in 7 days: step count, RHR, energy, mood
- Deactivate if average steps >7,000 for 7 days

## 🧠 Modeling Notes
Acts as a "metabolic muter" — subtle but wide-ranging suppression of health system adaptability
