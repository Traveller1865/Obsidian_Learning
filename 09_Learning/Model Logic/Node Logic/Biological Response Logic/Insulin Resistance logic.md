---
type: node_logic
target_node: Insulin Resistance
category: biological_response
---

# 🧠 Node Logic — Insulin Resistance

## 🔑 Activation Criteria
- HOMA-IR >2.0
- Fasting insulin >10 µIU/mL + glucose >100 mg/dL
- CGM shows elevated baseline or prolonged postprandial glucose
- Waist-to-hip ratio >0.9 (men) / >0.85 (women)

## 🔁 Risk Propagation
- [[Type 2 Diabetes]] (β = 0.9)
- [[Hypertension]] (β = 0.6)
- [[Fatty Liver (NAFLD)]] (β = 0.75)
- [[PCOS]] (β = 0.7)
- [[Cognitive Decline]] (β = 0.55)

- **Decay Half-Life**: 30 days
- **Scaling**: Sharp early rise with low activity + poor diet

## 🚨 Alert Rules
- Trigger if HOMA-IR or fasting insulin + postprandial glucose out of range for 7+ days
- Recommend low-carb protocol, Zone 2 movement, time-restricted eating

## 🛠 Intervention Feedback
- Reassess insulin, glucose, and CGM trend in 2 weeks
- Deactivate if HOMA-IR drops <1.8 for 7+ days

## 🧠 Modeling Notes
Core metabolic bottleneck — early identifier of downstream cardiometabolic and hormonal disorders
