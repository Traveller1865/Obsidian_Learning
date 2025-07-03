---
type: biological_response
modifiable: semi
node_category: immune
tags: [immune, dysregulation, infection]
source_type: [lab, immunoassay]
linked_model_inputs: [white_cell_diff, CRP, IgG_subclasses]
---

# Immune Dysfunction — Biological Response Node

## 🧪 Description
A maladaptive immune state marked by overactivation, suppression, or misdirection — contributes to autoimmunity, chronic infection, and poor repair mechanisms.

## 🔁 Triggered By
- [[Gut Dysbiosis]]
- [[Environmental Toxins]]
- [[Chronic Psychological Stress]]

## ⛓ Leads To
- [[Autoimmune Disease]]
- [[Chronic Fatigue]]
- [[Cancer]]

## 📊 Measurable Biomarkers
- White cell counts (CD4/CD8)
- IgG subclass imbalance
- Inflammatory cytokines

## 🔍 Detection Threshold
Documented irregularities in immunoglobulins or CD markers

## 📉 Downstream Risk Amplification
- Propagation Coefficient: `0.75`
- Risk Scaling Factor: `cyclical feedback`

## 🛠 Influenced By
| Intervention         | Effect                  | Evidence Level |
|----------------------|--------------------------|----------------|
| [[Elimination Diet]] | Reduces immune load      | Moderate       |
| [[Probiotics]]       | Rebalances gut-immune axis| High           |

## 🧠 Model Notes
Highly individual; interacts bidirectionally with inflammation and infection nodes
