---
type: node_logic
target_node: Autoimmune Disease
category: chronic_disease
---

# 🧠 Node Logic — Autoimmune Disease

## 🔑 Activation Criteria
- Clinical diagnosis (RA, MS, Hashimoto’s, IBD, SLE)
- ANA, CRP, ESR, and autoantibodies positive
- Symptoms: joint pain, fatigue, gut issues, flares

## 🔁 Upstream Contributors
- [[Leaky Gut]] (β = 0.75)
- [[Immune Dysfunction]] (β = 0.8)
- [[Environmental Toxins]] (β = 0.6)
- [[Chronic Stress]] (β = 0.55)

- **Progression Window**: 6 months – 10 years
- **Scaling**: Triggered flare threshold + barrier dysfunction

## 🚨 Alert Rules
- Trigger if CRP/ANA + fatigue/pain log + flare symptoms
- Recommend autoimmune nutrition plan, gut healing, and stress audit

## 🛠 Intervention Feedback
- Monitor symptom log, labs quarterly
- Deactivate flare phase when markers + symptoms stabilize

## 🧠 Modeling Notes
Immune threshold disease — risk modulated heavily by gut and environmental input, not purely genetic
