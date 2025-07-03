---
type: node_logic
target_node: Immune Dysfunction
category: biological_response
---

# 🧠 Node Logic — Immune Dysfunction

## 🔑 Activation Criteria
- Elevated CRP, ESR, IgG/IgA abnormalities, ANA+
- Frequent infections, poor wound healing
- Immunosenescence markers (low NK activity, elevated IL-6)

## 🔁 Risk Propagation
- [[Autoimmune Disease]] (β = 0.75)
- [[Systemic Inflammation]] (β = 0.7)
- [[Fatigue]] (β = 0.65)
- [[Cancer]] (β = 0.5)

- **Decay Half-Life**: 60–90 days
- **Scaling**: Stepwise — worsens with toxin load, cortisol, nutrient depletion

## 🚨 Alert Rules
- Trigger if immune markers off + infection risk or symptoms spike
- Recommend vitamin D repletion, gut repair, stress mod

## 🛠 Intervention Feedback
- Recheck labs after 4–6 weeks of protocol
- Deactivate with symptom and biomarker normalization

## 🧠 Modeling Notes
Core defense signal — both input and output of inflammation and metabolic load. Often triggered in stealth by gut, sleep, and stress
