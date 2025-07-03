# 🔁 Risk Propagation Rules

This defines how risk flows between nodes once a parent node is activated.

---

## 🔸 Insulin Resistance

- **Propagates To**:
  - Type 2 Diabetes (β = 0.85)
  - Hypertension (β = 0.6)
  - Fatty Liver (β = 0.75)
- **Decay Half-Life**: 30 days
- **Scaling Function**: Linear
- **Note**: Risk decreases gradually after node deactivates unless re-triggered.

---

## 🔸 Chronic Stress

- **Propagates To**:
  - High Cortisol (β = 0.9)
  - Depression (β = 0.6)
  - Immune Dysfunction (β = 0.5)
