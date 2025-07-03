---
type: node_logic
target_node: Substance Use
category: root_cause
---

# 🧠 Node Logic — Substance Use

## 🔑 Activation Criteria
- Alcohol >14 drinks/week (men), >7/week (women)
- Cannabis use ≥3x/week (self-report or passive log)
- Nicotine detected via CO breath, cotinine, or self-report
- Ongoing use of illicit or unprescribed stimulants, opioids, or depressants

## 🔁 Risk Propagation
- [[Liver Stress / Toxic Load]] (β = 0.7)
- [[Sleep Fragmentation]] (β = 0.65)
- [[Depressive Symptoms]] (β = 0.6)
- [[Insulin Resistance]] (β = 0.4)
- [[Cardiovascular Disease]] (β = 0.5)

- **Decay Half-Life**: 14–90 days (based on substance class)
- **Scaling**: Sharp step function after binge pattern or polyuse detected

## 🚨 Alert Rules
- Trigger if consumption > thresholds + matched symptoms (sleep, fatigue, mood)
- Recommend substance audit tracker, motivational nudge, support prompts

## 🛠 Intervention Feedback
- Reassess weekly use + liver/mood markers
- Deactivate if sustained abstinence or harm reduction for 14+ days

## 🧠 Modeling Notes
Not always primary cause — often co-factor that amplifies existing dysfunctions. Must detect hidden use where possible.
