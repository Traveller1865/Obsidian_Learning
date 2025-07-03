---
type: node_logic
target_node: Fatty Liver (NAFLD)
category: intermediate_dysfunction
---

# 🧠 Node Logic — Fatty Liver (NAFLD)

## 🔑 Activation Criteria
- ALT/AST elevation (>30 IU/L) with ALT > AST
- Ultrasound-confirmed hepatic steatosis
- Triglycerides >150 mg/dL + central obesity

## 🔁 Risk Propagation
- [[Insulin Resistance]] (β = 0.8)
- [[Chronic Inflammation]] (β = 0.6)
- [[Cardiovascular Disease]] (β = 0.65)
- [[Chronic Kidney Disease]] (β = 0.5)

- **Decay Half-Life**: 45–90 days
- **Scaling**: Linear with TG elevation and sugar intake

## 🚨 Alert Rules
- Trigger if ALT/AST abnormal + waist gain + low activity
- Recommend sugar detox, fasting, mitochondrial support

## 🛠 Intervention Feedback
- Recheck ALT/AST or imaging in 6–8 weeks
- Deactivate if liver enzymes normalize + TG drops

## 🧠 Modeling Notes
Silent node — liver dysfunction precedes many cardiometabolic diseases, but often goes undetected until advanced
