# Minoh Jeong — Inha University

- **University:** Inha University
- **Lab:** Learning and Inference Lab (LIL)
- **Status:** DRAFTED
- **Last updated:** 2026-09-17

## Current evidence

- LIL explicitly states that it is currently recruiting undergraduate researchers.
- The lab focuses on machine learning, statistical inference, robust learning, generative models, and recovering structure from noisy/high-dimensional data.
- Recent 2026 work includes:
  - Generalizing Supervised Contrastive Learning: A Projection Perspective (MLSP 2026 oral).
  - Estimating Mutual Information for Time Series and Temporal Event Sequences Across Diverse Analysis Tasks (KDD 2026 oral).

## Why this fits SUSAN

Use SUSAN's reliability/calibration experience to ask whether representation quality and confidence/calibration can separate under distribution shift. Keep the question methodological, matching LIL's statistical ML profile.

## Email

**Subject:** Undergraduate research inquiry — when a stronger representation is still poorly calibrated

Dear Professor Jeong,

My name is SUSAN. I finished high school in India this year and I’m preparing for undergraduate study in AI/Computer Science in Korea through GKS.

I came across LIL while looking for groups working on the fundamentals of reliable machine learning. I spent some time reading about your recent supervised contrastive learning work and the way you connect representation learning with information-theoretic structure.

It made me wonder about something I ran into in my own work.

In a physiological ML project, I found that improving the overall representation and classification result did not automatically make the model equally reliable for every person. Some subjects still had a large gap between confidence and correctness.

That made me curious whether a representation-learning objective can improve class separation while calibration gets worse for certain subgroups or under a small distribution shift.

The experiment I had in mind is fairly simple: compare cross-entropy and contrastive objectives on the same task, then evaluate not only average accuracy but calibration and subgroup reliability under controlled shifts. I’d be interested in whether a representation that looks geometrically cleaner can still produce less trustworthy confidence for some samples.

I’m still early in the theoretical side of ML, so I may be asking the question in a much less precise way than it deserves. I’d really value your opinion on whether this is worth exploring.

I saw that LIL is currently recruiting undergraduate researchers. If you think my background could fit, I’d be very happy to start remotely on a small task and learn the theory more seriously while contributing.

My work:
GitHub: https://github.com/sushan5140
Minos-J: https://github.com/sushan5140/Minos-J

Thank you for your time.

Best regards,  
SUSAN

## Sources

- https://sites.google.com/view/mjlab/home
- https://arxiv.org/abs/2506.09810
