# Seunghyoung Ryu — Sejong University

- **University:** Sejong University
- **Department:** Department of Intelligent Mechatronics Engineering
- **Lab:** IDEAL Lab
- **Email:** shryu@sejong.ac.kr
- **Status:** DRAFTED
- **Last updated:** 2026-09-17

## Current evidence

- IDEAL Lab is currently recruiting undergraduate interns and graduate students.
- Current themes: anomaly detection, multivariate time-series forecasting, industrial AI, intelligent control, digital twins, robotics.
- Recent 2026 work includes:
  - **Data-driven surrogate modeling for thermal-hydraulic codes via hybrid deep neural networks and quantile learning**
  - **PQNet: Probabilistic Quantile Network for multivariate surrogate modeling in nuclear thermal-hydraulics**
  - open-source **UNN4AD** anomaly-detection baseline.

## Why this fits SUSAN

Use SUSAN's reliability/calibration background. The clean question is whether an anomaly or uncertainty score remains meaningful after the operating regime changes, instead of only whether the average detector accuracy remains high.

## Email

**Subject:** Undergraduate research inquiry — reliability of anomaly scores under operating shifts

Dear Professor Ryu,

My name is SUSAN. I finished high school in India this year, and I’m preparing to apply for undergraduate study in AI/Computer Science in Korea through GKS.

I came across IDEAL Lab while looking for groups working on industrial AI and anomaly detection. I spent some time reading through the lab’s recent work on probabilistic forecasting and the UNN4AD anomaly-detection direction.

One thing I kept wondering about was whether the score itself stays trustworthy when the operating condition changes.

In a physiological ML project I’ve been working on, I found that a model could look reliable overall but become much less reliable for one particular person. Since then I’ve been interested in cases where an average result hides a local failure.

For an industrial anomaly detector, I’m curious whether the anomaly score can behave in the same way. A detector may still separate normal and abnormal samples reasonably well after a regime shift, but the same score threshold may no longer mean the same thing.

I was thinking of starting with a small experiment: train under one operating regime, introduce controlled shifts in load or signal distribution, and track not only detection accuracy but how the anomaly score calibration changes. If the score drifts before the classification result visibly collapses, that could be a useful early warning.

I may be framing this too much from a calibration point of view, so I’d really value your opinion on whether the question makes sense for the kinds of systems your lab studies.

I also saw that IDEAL Lab is currently looking for undergraduate interns. If you think my background could fit, I’d be very happy to start remotely on a small task or contribute to something already underway.

My work:
GitHub: https://github.com/sushan5140
Minos-J: https://github.com/sushan5140/Minos-J

Thank you for reading.

Best regards,  
SUSAN

## Sources

- https://ideal.sejong.ac.kr/
- https://ideal.sejong.ac.kr/join
