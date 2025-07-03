---
type: node_logic
target_node: Postprandial Hypotension
category: intermediate_dysfunction
---

# 🧠 Node Logic — Postprandial Hypotension

## 🔑 Activation Criteria
- BP drop ≥20 mmHg within 2 hours after eating
- Wearable BP/RHR sync shows hypotensive trend post-meal
- Symptoms: dizziness, fatigue, “crash” after eating

## 🔁 Risk Propagation
- [[Fatigue]] (β = 0.6)
- [[Cognitive Impairment]] (β = 0.5)
- [[Autonomic Dysfunction]] (β = 0.65)
- [[Fall Risk (elderly)]] (β = 0.4)

- **Decay Half-Life**: 7–14 days
- **Scaling**: Steep in undernourished, elderly, or highly insulin resistant

## 🚨 Alert Rules
- Trigger if 2+ episodes detected in 1 week + symptom log match
- Recommend meal spacing, hydration, blood sugar stabilization

## 🛠 Intervention Feedback
- Deactivate after 7+ days with no post-meal drop or symptoms

## 🧠 Modeling Notes
Rare but important dysfunction — shows early autonomic or vascular fragility; underdetected without wearables or logs
