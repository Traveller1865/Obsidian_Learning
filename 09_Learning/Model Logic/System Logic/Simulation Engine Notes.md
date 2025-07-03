# 🧠 Simulation Engine Notes

## Purpose

This engine models how risk and resilience propagate across the node network in response to lifestyle data, wearable inputs, lab values, and survey scores.

## Node States

Each node can be:
- `Inactive` (no risk or protective input)
- `Active` (thresholds met, propagates risk or resilience)
- `Recovering` (after deactivation, decay applies)

## Propagation Flow

1. Risk nodes push downstream effects based on `β` coefficients.
2. Protective nodes subtract from active risk nodes’ scores.
3. Alerts are triggered when thresholds are crossed.
4. Interventions attenuate or reverse node state.

## Time Resolution
- Engine simulates at a daily time scale.
- Decay and propagation modeled via exponential or step decay curves.

## Conflict Resolution

If both risk and protective nodes affect a target:


net_risk = ∑(risk_score × β) - ∑(resilience_score × β_resilience)

Only if net_risk exceeds target threshold is that node activated.
