---
type: node_logic
target_node: Chronic Kidney Disease
category: chronic_disease
---

# 🧠 Node Logic — Chronic Kidney Disease

## 🔑 Activation Criteria
- eGFR <60 mL/min/1.73m² for ≥3 months
- Albumin-to-creatinine ratio (ACR) >30 mg/g
- Elevated BUN or creatinine on repeated tests

## 🔁 Upstream Contributors
- [[Hypertension]] (β = 0.8)
- [[Insulin Resistance]] (β = 0.75)
- [[Cardiovascular Disease]] (β = 0.7)
- [[Chronic Inflammation]] (β = 0.6)

- **Progression Window**: 3–20 years
- **Scaling**: Nonlinear — early stages asymptomatic, then rapid decline

## 🚨 Alert Rules
- Trigger if 2+ renal markers shift + BP/glucose poorly managed
- Recommend kidney-sparing protocol: hydration, sodium balance, BP control

## 🛠 Intervention Feedback
- Monitor GFR/ACR quarterly
- Deactivate active progression flag with stabilization or reversal

## 🧠 Modeling
