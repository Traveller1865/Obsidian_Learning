# 🔑 Node Activation Rules

Below are the standard criteria that determine whether a node becomes “active” in the graph.

---

## 🧠 Glucose Intolerance

- **Data Sources**: A1C, CGM, OGTT
- **Thresholds**:
  - A1C ≥ 5.6%
  - CGM spikes >20% (7-day average)
  - OGTT ≥ 140 mg/dL at 2 hours
- **Minimum duration**: 7 days
- **Confidence weights**:
  - Lab: 1.0
  - Wearable: 0.9
  - Symptom log: 0.6
- **Status**: ⚠️ Activate if 2 or more thresholds crossed for 7+ days
