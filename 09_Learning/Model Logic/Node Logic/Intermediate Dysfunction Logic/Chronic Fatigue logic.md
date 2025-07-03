---
type: node_logic
target_node: Chronic Fatigue
category: intermediate_dysfunction
---

# 🧠 Node Logic — Chronic Fatigue

## 🔑 Activation Criteria
- Energy level <4/10 for >2 weeks
- Poor response to rest/sleep
- Rule out anemia, thyroid, infection (clinical dx or labs)

## 🔁 Risk Propagation
- [[Depressive Symptoms]] (β = 0.65)
- [[Mitochondrial Dysfunction]] (β = 0.7)
- [[Immune Dysfunction]] (β = 0.6)
- [[Social Withdrawal]] (β = 0.5)

- **Decay Half-Life**: 30–60 days (depending on underlying cause)
- **Scaling**: Nonlinear — worsens with inactivity + circadian misalignment

## 🚨 Alert Rules
- Trigger if low energy + poor HRV recovery + no exercise tolerance
- Recommend pacing strategy, anti-inflammatory diet, sleep window anchoring

## 🛠 Intervention Feedback
- Reassess energy, HRV, and RHR trend after 2 weeks
- Deactivate if energy stabilizes >6/10 and HRV improves

## 🧠 Modeling Notes
Difficult to reverse once entrenched — represents physiological system exhaustion; highly sensitive to layered stress/inflammation
