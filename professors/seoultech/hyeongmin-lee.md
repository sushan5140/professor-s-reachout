# Hyeongmin Lee — SeoulTech

- **University:** Seoul National University of Science and Technology (SeoulTech)
- **Department:** Electronic Engineering
- **Lab:** Vision and Video Dynamics Lab (ViViD Lab)
- **Email:** hyeongmin.lee@seoultech.ac.kr
- **Status:** DRAFTED
- **Last updated:** 2026-09-17

## Current evidence

- ViViD Lab is actively recruiting undergraduate interns, M.S., and Ph.D. students.
- Current themes: diffusion/generative models, video, 3D vision, compression, world models.
- Recent 2026 work includes:
  - **Not All Prediction Targets Keep Training-Free Diffusion Guidance on the Manifold** — ECCV 2026
  - **Probing Intrinsic Bias: Internal Attention Feature Analysis for Social Bias Evaluation in Diffusion Models** — Neurocomputing 2026.

## Why this fits SUSAN

The ECCV paper explicitly shows that standard accuracy-style evaluation can miss manifold damage. This aligns strongly with SUSAN's falsification/evaluation mindset. Ask whether a per-sample diagnostic can predict off-manifold failure before the final image is produced.

## Email

**Subject:** Undergraduate research inquiry — detecting diffusion guidance failure before the final sample

Dear Professor Lee,

My name is SUSAN. I finished high school in India this year, and I’m preparing to apply for undergraduate study in AI/Computer Science in Korea through GKS.

I came across ViViD Lab while reading about diffusion-model evaluation, and your recent ECCV work on training-free guidance caught my attention.

The part I liked most was that a normal accuracy-style metric could miss a failure that becomes obvious once you look at whether the sample has actually stayed on the data manifold.

A lot of my own work has been about that kind of mismatch — when the final score says a system is fine, but a more targeted check reveals that something important has already gone wrong.

It made me wonder whether the failure can be detected before the final image is produced.

For example, during guided sampling, could a simple signal from the intermediate clean-image estimate, attention pattern or classifier gradient predict that the trajectory is starting to leave the manifold? If so, the system might be able to weaken or change the guidance before the visible artifact appears.

I’d start with a very small experiment using the same guidance setup and compare successful and failed trajectories step by step, rather than proposing another diffusion model.

I may be misunderstanding what information is actually available early enough in the sampling process, so I’d really value your opinion on whether this is a sensible question.

I saw that ViViD Lab is actively recruiting undergraduate interns. If you think my evaluation background could fit, I’d be very happy to start remotely on a small research task under your guidance.

My work:
GitHub: https://github.com/sushan5140
Minos-J: https://github.com/sushan5140/Minos-J

Thank you for reading.

Best regards,  
SUSAN

## Sources

- https://vivid.seoultech.ac.kr/join/
- https://vivid.seoultech.ac.kr/publications/
- https://arxiv.org/abs/2607.00647
