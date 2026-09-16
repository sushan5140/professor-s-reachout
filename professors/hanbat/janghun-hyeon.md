# Janghun Hyeon — Hanbat National University

- **University:** Hanbat National University
- **Department:** Artificial Intelligence Software
- **Lab:** Perceptional AI Robotics Lab (PEARL Lab)
- **Email:** jhhyeon@hanbat.ac.kr
- **Status:** DRAFTED
- **Last updated:** 2026-09-17

## Current evidence
- PEARL Lab explicitly says it is always looking for undergraduate researchers.
- The lab currently has multiple undergraduate researchers.
- Current themes: robot vision, visual localization, 3D perception, anomaly detection, sensor fusion.
- Recent 2026 work includes robotic tram-wheel surface defect detection using profile-guided multi-view anomaly detection and time-series imputation work.

## Why this fits SUSAN
Use hidden reliability gaps in anomaly detection. A robot-inspection model may perform well on average but fail under reflections/background clutter, and confidence may not reveal the failure.

## Email
**Subject:** Undergraduate research inquiry — reliability of robotic anomaly detection in changing visual conditions

Dear Professor Hyeon,

My name is SUSAN. I finished high school in India this year, and I’m preparing to apply for undergraduate study in AI/Computer Science in Korea through GKS.

I found PEARL Lab while looking into practical robot vision, and your recent work on tram-wheel anomaly detection caught my attention.

What interested me was that the difficult part is not only detecting the defect. The system also has to work when the background, reflection, angle, or camera condition changes.

In one of my own ML projects, I found that an overall score could look good while one subject was much less reliable than the rest. Since then I’ve been interested in failures that get hidden inside an average metric.

I started wondering whether an anomaly detector can have the same problem. It might keep a strong overall AUROC while becoming much less trustworthy under one viewing condition.

I’d start by taking the same detector and grouping errors by viewpoint, reflection level, or background clutter, then compare the anomaly score with the actual failure rate in each group.

If some conditions are consistently overconfident, I’d then test whether a simple calibration or view-consistency check can catch them before the robot acts on the result.

I’m still early in robotics, so I may be looking at the problem too much from an evaluation angle. I’d really value your opinion.

I saw that PEARL Lab is open to undergraduate researchers. If you think my background could fit, I’d be very happy to start remotely on a small project and contribute while learning the robotics side.

My work:
GitHub: https://github.com/sushan5140
Minos-J: https://github.com/sushan5140/Minos-J

Thank you for reading.

Best regards,
SUSAN

## Sources
- https://pearl.hanbat.ac.kr/
- https://pearl.hanbat.ac.kr/members
- https://pearl.hanbat.ac.kr/contact
