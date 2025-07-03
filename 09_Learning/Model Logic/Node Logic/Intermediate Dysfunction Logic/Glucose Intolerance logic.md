---
type: node_logic
target_node: Glucose Intolerance
category: intermediate_dysfunction
---

# 🧠 Node Logic — Glucose Intolerance

## 🔑 Activation Criteria
- Fasting glucose 100–125 mg/dL
- Post-meal glucose 140–199 mg/dL at 1 hr
- A1C between 5.6–6.4%

## 🔁 Risk Propagation
- [[Type 2 Diabetes]] (β = 0.85)
- [[Insulin Resistance]] (β = 0.7)
- [[Fatty Liver]] (β = 0.6)
- [[Chronic Kidney Disease]] (β = 0.5)

- **Decay Half-Life**: 14–30 days
- **Scaling**: Steepest with low muscle mass and high sugar intake

## 🚨 Alert Rules
- Trigger if 2+ impaired readings + fatigue/cravings
- Recommend glucose disposal support, low GI diet, strength training

## 🛠 Intervention Feedback
- Reassess fasting + postprandial glucose weekly
- Deactivate if fasting <95 and postprandial <140 for 7+ days

## 🧠 Modeling Notes
Strong mid-point signal in metabolic breakdown — early, actionable, and fully reversible if caught
