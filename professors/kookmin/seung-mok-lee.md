# Seung-Mok Lee — Kookmin University

- **University:** Kookmin University
- **Lab:** Robot Navigation & Intelligence Lab (RoNI Lab)
- **Email:** seungmok@kookmin.ac.kr
- **Status:** DRAFTED
- **Last updated:** 2026-09-17

## Current evidence

- RoNI Lab states that it is looking for talented individuals in AI and robotics and provides Professor Lee's contact.
- The lab recommends its UROP route for undergraduates interested in graduate research, and two undergraduate research assistants joined in March 2026.
- Current 2026 funded projects include:
  - commonsense-reasoning-based cooperative navigation for bimodal robotic swarms
  - modular Physical AI UGV and control for integrated safety management
  - AI-SAT mobility
- Recent papers include **Model predictive trajectory optimization and control for UAV replacement in close formation flight with local minima avoidance** (IEEE Access, 2025) and environment-adaptive multi-robot formation planning.

## Why this fits SUSAN

Use a reliability/failure-detection angle in multi-robot planning. A planner may generate a valid trajectory in simulation but become brittle under state-estimation error or unexpected obstacles. Ask whether disagreement between a planning model and a simple safety auditor can predict impending failure before execution.

## Email

**Subject:** Undergraduate research inquiry — detecting brittle multi-robot plans before execution

Dear Professor Lee,

My name is SUSAN. I finished high school in India this year, and I’m preparing to apply for undergraduate study in AI/Computer Science in Korea through GKS.

I found RoNI Lab while looking through Physical AI and autonomous-navigation research, and I spent some time reading about your work on multi-robot formation planning and trajectory optimization.

The part that made me curious was what happens between a plan being mathematically valid and actually being robust enough to execute.

In some of my own AI work, I’ve been interested in systems that look correct at the final output but contain a failure that only becomes visible when the environment changes slightly. I started wondering whether a similar thing happens with robot plans.

For example, a trajectory may satisfy the planner under the current state estimate, but a small localization error, obstacle shift, or another robot moving differently than expected could make that same plan unsafe very quickly.

A small experiment I’d like to try is to generate plans under the normal model, then perturb only one part of the assumed state at a time and measure which plans fail first. I’d then test whether a lightweight second checker — using simpler geometric or safety constraints rather than the same planning logic — can identify the fragile plans before execution.

I’m still early in robotics, so I may be describing a problem that already has a better formulation in motion planning or model predictive control. I’d appreciate your opinion on whether the idea is worth exploring.

I saw that your lab already works with undergraduate research assistants and encourages undergraduate research participation. If you think my evaluation/reliability background could fit, I’d be very happy to start remotely on a small project or contribute to something already underway.

My work:
GitHub: https://github.com/sushan5140
Minos-J: https://github.com/sushan5140/Minos-J

Thank you for reading.

Best regards,  
SUSAN

## Sources

- https://ronil.kookmin.ac.kr/
- https://ronil.kookmin.ac.kr/publications/
