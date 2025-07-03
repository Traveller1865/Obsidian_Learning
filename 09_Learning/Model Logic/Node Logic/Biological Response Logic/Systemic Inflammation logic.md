---
type: node_logic
target_node: Systemic Inflammation
category: biological_response
---

# 🧠 Node Logic — Systemic Inflammation

## 🔑 Activation Criteria
- hsCRP >1.0 mg/L (low-grade), >3.0 (high)
- IL-6, TNF-α, ESR elevated
- Symptoms: joint pain, fog, morning stiffness

## 🔁 Risk Propagation
- [[Cardiovascular Disease]] (β = 0.85)
- [[Autoimmune Disease]] (β = 0.75)
- [[Mitochondrial Dysfunction]] (β = 0.65)
- [[Depressive Symptoms]] (β = 0.55)

- **Decay Half-Life**: 30–60 days
- **Scaling**: Stepwise with immune, gut, metabolic burden

## 🚨 Alert Rules
- Trigger if CRP + fatigue/mood markers persist >7 days
- Recommend anti-inflammatory protocol: omega-3s, turmeric, fasting, fiber

## 🛠 Intervention Feedback
- Recheck CRP, ESR, and symptom trends after 14–21 days

## 🧠 Modeling Notes
Final common pathway — amplifies most downstream conditions, and slows resolution. Critical to track across systems.
