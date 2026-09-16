# Seung Hun Choi — Soongsil University

- **University:** Soongsil University
- **School:** School of Computer Science and Engineering
- **Lab:** Intelligent Computing Systems (ICS) Lab
- **Email:** shchoi@ssu.ac.kr
- **Status:** DRAFTED
- **Last updated:** 2026-09-17

## Current evidence

- ICS Lab explicitly says it is looking for undergraduate, M.S., and Ph.D. students.
- Several undergraduate interns joined in 2026.
- Recent 2026 work: **X-DTM: Intelligent Coordination of Cross-Layer Dynamic Thermal Management for Reliable Mobile Experience**, accepted to IEEE/ACM ICCAD.

## Why this fits SUSAN

Do not pitch generic AI. Use the systems/reliability angle: average latency can hide tail failures caused by thermal throttling. Ask whether a small predictive signal can identify imminent AI-service degradation before user-visible failure.

## Email

**Subject:** Undergraduate research inquiry — predicting AI-service degradation under thermal limits

Dear Professor Choi,

My name is SUSAN. I finished high school in India this year, and I’m preparing to apply for undergraduate study in AI/Computer Science in Korea through GKS.

I found the ICS Lab while looking for groups working on reliable AI systems, and your recent X-DTM work caught my attention.

What interested me was that thermal management is not only a hardware problem. Once the system starts throttling, the user can experience a very different AI service even if the model itself has not changed.

I started wondering whether average latency hides the most important failures.

For example, an on-device model may have an acceptable average response time, but a small number of requests could suddenly become much slower once temperature, memory pressure and scheduler behavior line up badly.

A small experiment I’d like to try is to run the same AI workload under controlled thermal and background-load conditions, then record which system signals change just before the worst latency spikes. I’d be interested in whether a lightweight predictor can flag those bad cases early enough to change scheduling or inference settings.

I’m still learning the systems side, so I may be reducing a cross-layer problem too much. I’d really value your opinion on whether that question is worth exploring.

I saw that ICS Lab is currently looking for undergraduate students. If you think my background could be useful, I’d be very happy to start remotely on a small task or contribute to something already underway in the lab.

My work:
GitHub: https://github.com/sushan5140
Minos-J: https://github.com/sushan5140/Minos-J

Thank you for your time.

Best regards,  
SUSAN

## Sources

- https://sites.google.com/view/icsl-ssu/
