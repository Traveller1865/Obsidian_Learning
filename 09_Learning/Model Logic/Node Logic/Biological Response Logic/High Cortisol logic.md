---
type: node_logic
target_node: High Cortisol
category: biological_response
---

# 🧠 Node Logic — High Cortisol

## 🔑 Activation Criteria
- AM serum cortisol >18 μg/dL or PM cortisol >10 μg/dL
- Flattened diurnal rhythm (e.g. low AM:PM ratio)
- Hair cortisol or salivary 4-point > reference range
- Symptoms: anxiety, wired fatigue, abdominal weight gain

## 🔁 Risk Propagation
- [[Insulin Resistance]] (β = 0.7)
- [[Sleep Fragmentation]] (β = 0.6)
- [[Depressive Symptoms]] (β = 0.55)
- [[Immune Dysfunction]] (β = 0.6)

- **Decay Half-Life**: 14 days with proper intervention
- **Scaling**: Sharp early spike, plateaus under chronic load

## 🚨 Alert Rules
- Trigger if cortisol + HRV suppression + sleep efficiency <80%
- Recommend morning sunlight, breathwork, glycemic regulation

## 🛠 Intervention Feedback
- Deactivate if AM/PM slope restores and symptoms improve for 7+ days

## 🧠 Modeling Notes
Core stress biomarker — links behavioral (stress) and physiological (immune/metabolic) states
