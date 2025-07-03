---
type: node_logic
target_node: Polycystic Ovary Syndrome (PCOS)
category: chronic_disease
---

# 🧠 Node Logic — Polycystic Ovary Syndrome (PCOS)

## 🔑 Activation Criteria
- Rotterdam criteria: 2 of 3 (oligo/anovulation, hyperandrogenism, polycystic ovaries)
- Acne, hirsutism, irregular cycles
- Labs: elevated LH:FSH ratio, high testosterone, low SHBG

## 🔁 Upstream Contributors
- [[Insulin Resistance]] (β = 0.85)
- [[Hormonal Axis Disruption]] (β = 0.75)
- [[Stress]] (β = 0.6)
- [[Poor Sleep]] (β = 0.5)

- **Progression Window**: Chronic unless reversed
- **Scaling**: Vicious cycle with metabolic syndrome and infertility

## 🚨 Alert Rules
- Trigger if 2+ criteria met + cycle/metabolic dysfunction
- Recommend insulin sensitization, androgen modulation, circadian lock

## 🛠 Intervention Feedback
- Track LH/FSH, testosterone, SHBG, ovulatory rhythm
- Deactivate active PCOS tag if cycle + labs normalize

## 🧠 Modeling Notes
Metabolic + reproductive disorder — early insulin sensitivity reversal prevents a cascade of reproductive and chronic disease outcomes
