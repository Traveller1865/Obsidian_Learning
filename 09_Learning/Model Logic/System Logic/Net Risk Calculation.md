# 🔢 Net Risk Calculation

## Formula

For each node:

net_score = ∑(upstream_risk_i × β_i) - ∑(upstream_resilience_j × β_j)

Where:
- `β_i` = positive coefficient from an upstream dysfunction node
- `β_j` = negative coefficient from a protective node

## Example

For node: `Insulin Resistance`
- 0.8 from Poor Diet
- 0.7 from Physical Inactivity
- 0.6 from Daily Exercise
- 0.5 from Fasting State

net_score = 1.5 - 1.1 = 0.4 → Node becomes active if threshold = 0.3
## Use

This logic allows dynamic health scoring, rebalancing risk each day based on both damage and repair inputs.
