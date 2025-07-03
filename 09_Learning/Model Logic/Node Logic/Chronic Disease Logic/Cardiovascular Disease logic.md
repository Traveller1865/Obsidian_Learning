---
type: node_logic
target_node: Cardiovascular Disease
category: chronic_disease
---

# 🧠 Node Logic — Cardiovascular Disease

## 🔑 Activation Criteria
- Clinical diagnosis (CAD, MI, stroke, PAD)
- Elevated CAC score, LDL-P, hsCRP, ApoB
- Symptomatic: angina, SOB, claudication

## 🔁 Upstream Contributors
- [[Hypertension]] (β = 0.85)
- [[Insulin Resistance]] (β = 0.8)
- [[Visceral Obesity]] (β = 0.75)
- [[Endothelial Dysfunction]] (β = 0.8)

- **Progression Window**: 5–15 years
- **Scaling**: Linear until event threshold reached (e.g. MI)

## 🚨 Alert Rules
- Trigger if lipid + BP + HRV + visceral fat cluster
- Recommend statin-free protocol: inflammation, lifestyle reversal, Zone 2

## 🛠 Intervention Feedback
- Reassess ApoB, CAC, CRP quarterly
- Deactivate progression state with reversal score drop

## 🧠 Modeling Notes
#1 cause of death — but also the most preventable. Predictive modeling here has the highest impact and ROI.
