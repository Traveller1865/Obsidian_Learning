---
type: dysfunction_state
modifiable: true
node_category: hepatic
tags: [liver, metabolic, NAFLD]
source_type: [imaging, ALT, AST]
linked_model_inputs: [ALT, AST, liver_ultrasound, insulin]
---

# Fatty Liver (NAFLD) — Dysfunction Node

## ⚠️ Description
Accumulation of fat in the liver not caused by alcohol. Early sign of metabolic dysfunction, insulin resistance, and systemic inflammation.

## 🔁 Triggered By
- [[Insulin Resistance]]
- [[Visceral Obesity]]
- [[Poor Diet]]
- [[Elevated Blood Glucose]]

## ⛓ Leads To
- [[Liver Disease]]
- [[Type 2 Diabetes]]
- [[Cardiovascular Disease]]

## 📊 Measurable Criteria
- ALT or AST > upper normal
- Liver ultrasound or FibroScan showing steatosis

## 🔍 Diagnostic Threshold
Elevated liver enzymes with risk factors or imaging-confirmed steatosis

## 📉 Risk Amplification
- Propagation Coefficient: `0.8`
- Acceleration Factor: `inflammatory_priming`

## 🛠 Modifiable With
| Intervention             | Target Outcome     | Evidence Level |
|--------------------------|--------------------|----------------|
| [[Low Fructose Diet]]    | Reverses liver fat | High           |
| [[Weight Loss 5–10%]]    | Reduces hepatic steatosis | High     |

## 🧠 Model Notes
Acts as a metabolic hub node; tracking NAFLD helps catch early metabolic collapse before diabetes onset
