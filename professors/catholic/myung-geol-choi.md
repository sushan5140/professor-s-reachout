# Myung Geol Choi — The Catholic University of Korea

- **University:** The Catholic University of Korea
- **Lab:** Computer Graphics Lab
- **Email:** mgchoi@catholic.ac.kr
- **Status:** DRAFTED
- **Last updated:** 2026-09-17

## Current evidence
- The lab explicitly says it is actively recruiting undergraduate interns.
- Current internship areas include 3D urban modeling, Unity crowd simulation, and crowd-simulation game development.
- Recent 2026 work: **An Interactive Crowd Simulation Technique for Supporting Decision-Making in Crowd Congestion Response**.

## Why this fits SUSAN
Use simulation reliability rather than Minos-J. Ask whether a crowd simulator can look stable at aggregate density level while local congestion predictions are wrong.

## Email
**Subject:** Undergraduate research inquiry — reliability of crowd-simulation decisions under local errors

Dear Professor Choi,

My name is SUSAN. I finished high school in India this year and I’m preparing to apply for undergraduate study in AI/Computer Science in Korea through GKS.

I found your Computer Graphics Lab through the undergraduate-intern recruitment page, and your recent work on interactive crowd simulation for congestion response caught my attention.

What interested me was the decision-support side rather than only the graphics.

A crowd simulation can match the overall density fairly well while still getting one local bottleneck or movement pattern wrong. If a decision is based on that local region, the average simulation quality may not tell us enough.

Most of my own work has been around reliability and cases where a strong overall metric hides a weaker local failure.

I was thinking of a small experiment where the same crowd scenario is run with controlled changes in one local condition — exit width, route preference, entry timing — and the simulator’s predicted congestion point is compared with the actual outcome.

I’d be interested in whether there is an early signal that tells us when the simulation is becoming unreliable locally, even while the global statistics still look reasonable.

I’m still new to crowd simulation, so I may be simplifying the modeling assumptions too much. I’d really value your opinion.

I saw that your lab is actively recruiting undergraduate interns. If you think my background could fit, I’d be very happy to start remotely on a small simulation/evaluation task and learn the graphics side while contributing.

My work:
GitHub: https://github.com/sushan5140
Minos-J: https://github.com/sushan5140/Minos-J

Thank you for your time.

Best regards,
SUSAN

## Sources
- https://cg.catholic.ac.kr/contact/
- https://kci.go.kr/kciportal/ci/sereArticleSearch/ciSereArtiView.kci?sereArticleSearchBean.artiId=ART003371448
