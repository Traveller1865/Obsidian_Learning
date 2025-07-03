---
type: node_logic
target_node: Gut Dysbiosis
category: root_cause
---

# 🧠 Node Logic — Gut Dysbiosis

## 🔑 Activation Criteria
- Microbiome test: low diversity (< Shannon Index 2.5) or overgrowth
- Stool markers: calprotectin, pH, secretory IgA abnormal
- Symptoms: bloating, constipation, urgency

## 🔁 Risk Propagation
- [[Leaky Gut]] (β = 0.8)
- [[Digestive Dysregulation]] (β = 0.7)
- [[Systemic Inflammation]] (β = 0.6)
- [[Autoimmune Disease]] (β = 0.5)

- **Decay Half-Life**: 30 days
- **Scaling**: Accelerated if fiber intake <15g/day

## 🚨 Alert Rules
- Trigger if poor stool quality + >2 microbial imbalance markers
- Recommend targeted prebiotic/probiotic protocol

## 🛠 Intervention Feedback
- Recheck stool panel in 30 days
- Deactivate if diversity and inflammation normalize

## 🧠 Modeling Notes
High influence node — interacts with immunity, metabolism, mood, and inflammation; foundational in long-term risk prevention
