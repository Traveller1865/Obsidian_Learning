---
type: node_logic
target_node: Endothelial Dysfunction
category: biological_response
---

# 🧠 Node Logic — Endothelial Dysfunction

## 🔑 Activation Criteria
- Elevated homocysteine, ADMA, or oxidized LDL (lab)
- FMD test: <7% dilation
- Persistent hypertension or erectile dysfunction in males

## 🔁 Risk Propagation
- [[Cardiovascular Disease]] (β = 0.9)
- [[Chronic Kidney Disease]] (β = 0.7)
- [[Cognitive Decline]] (β = 0.5)
- [[Inflammation]] (β = 0.6)

- **Decay Half-Life**: 30–45 days
- **Scaling**: Steady — risk accumulates silently over months

## 🚨 Alert Rules
- Trigger if 2+ endothelial biomarkers elevated + BP drift
- Recommend nitric oxide support (beets, exercise), methylation support

## 🛠 Intervention Feedback
- Deactivate if biomarker levels improve + BP stabilizes <120/80

## 🧠 Modeling Notes
Critical vascular gatekeeper — early damage leads to global perfusion issues and silent organ decline
