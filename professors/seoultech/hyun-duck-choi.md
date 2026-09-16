# Hyun-Duck Choi — SeoulTech

- **University:** Seoul National University of Science and Technology (SeoulTech)
- **Department:** Smart ICT Convergence Engineering
- **Lab:** Control & Computer Vision Robotics Lab (Ctrl+CV / CVR Lab)
- **Email:** ducky.choi@seoultech.ac.kr
- **Status:** DRAFTED
- **Last updated:** 2026-09-17

## Current evidence

- CVR Lab is currently recruiting motivated undergraduate, M.S., and Ph.D. students.
- Current themes: robust Physical AI, reinforcement learning, robot vision, robust nonlinear control.
- Recent 2026 work includes:
  - **Exponentially dissipative vehicle path tracking control considering roll safety under network communications**
  - **Toward Smooth Depth Driven by Selective Attention and Selective Aggregation**
  - **Towards maximizing feature efficiency: All-in-one image restoration via radial basis attention**.

## Why this fits SUSAN

Use failure-detection under perturbations. A learned policy can perform well in nominal conditions while becoming brittle under localization, communication, or perception errors. Ask whether a simple independent safety checker can identify fragile plans before execution.

## Email

**Subject:** Undergraduate research inquiry — detecting fragile robot decisions before execution

Dear Professor Choi,

My name is SUSAN. I finished high school in India this year, and I’m preparing to apply for undergraduate study in AI/Computer Science in Korea through GKS.

I came across your lab while looking into Physical AI, and I liked the way your work combines learned perception and control with robustness rather than treating them as separate problems.

Your recent work on vehicle path tracking under network communication constraints made me wonder about something.

A learned controller or policy can work very well under the state it expects, but a small communication delay, localization error or perception mistake may make the same decision unsafe very quickly.

Most of my own work has been around finding cases where a system looks correct overall but contains a hidden failure. I was wondering whether that idea could be useful here.

A small experiment I’d like to try is to take a learned navigation or control policy, perturb one part of the observed state at a time, and measure which decisions become unsafe first. I’d then compare the policy’s own confidence with a much simpler independent safety check based on geometry or control constraints.

I’m curious whether disagreement between the two can identify brittle decisions before they are executed.

I’m still early in robotics and control, so I may be describing a problem that already has a cleaner formulation in robust control. I’d really value your opinion.

I saw that your lab is currently recruiting undergraduate students. If you think my evaluation/reliability background could fit, I’d be very happy to start remotely on a small research task.

My work:
GitHub: https://github.com/sushan5140
Minos-J: https://github.com/sushan5140/Minos-J

Thank you for your time.

Best regards,  
SUSAN

## Sources

- https://cvr.seoultech.ac.kr/
- https://icte.seoultech.ac.kr/en/about/faculty?menu=77097&profidx=02708&togo=list
