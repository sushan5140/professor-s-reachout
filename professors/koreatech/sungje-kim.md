# Sungje Kim — KOREATECH

- **University:** Korea University of Technology and Education (KOREATECH)
- **Lab:** Multimodal Intelligence and Computing Laboratory (MIC Lab)
- **Email:** sungjei.kim@koreatech.ac.kr
- **Status:** DRAFTED
- **Last updated:** 2026-09-17

## Current evidence
- MIC Lab explicitly lists an open position for undergraduate interns.
- Several undergraduates joined the lab in 2026.
- Current themes: efficient vision models for edge devices, multimodal representation learning, motion analysis, physically grounded AI.
- Recent work includes **User-feedback-based On Device AI Alignment System for AR HUDs in Automotive Applications** (IEEE ISMAR 2025) and work on efficient/quantized vision models for mobile devices.

## Why this fits SUSAN
Use reliability under edge constraints rather than generic multimodal AI. The question is whether an on-device perception model's confidence remains trustworthy after quantization/compression or changing real-world conditions.

## Email
**Subject:** Undergraduate research inquiry — reliability of on-device vision after compression

Dear Professor Kim,

My name is SUSAN. I finished high school in India this year, and I’m preparing to apply for undergraduate study in AI/Computer Science in Korea through GKS.

I found MIC Lab while looking into on-device and multimodal AI, and I was especially interested in the lab’s work on efficient vision models for edge devices and the AR HUD alignment project.

One thing I’ve been thinking about is what happens to confidence after a model is made smaller or cheaper to run.

In some of my own ML work, I found that a model could keep a good overall result while becoming much less reliable for one part of the data. That made me wonder whether a similar thing happens after quantization or compression.

A lightweight vision model may keep almost the same average accuracy, but I’m curious whether its confidence becomes less trustworthy for certain motion patterns, lighting conditions, or difficult examples.

I’d start with a simple experiment: compare the same model before and after an efficiency change, keep the test conditions fixed, and track not only accuracy but which samples change from correct to wrong and how the confidence shifts.

If those failures concentrate in a predictable set of conditions, I’d then test whether a small calibration step can flag them without undoing the efficiency gain.

I’m still early in edge-AI systems, so I may be simplifying the deployment side too much. I’d really value your opinion on whether this is a sensible question.

I saw that MIC Lab is currently welcoming undergraduate interns. If you think my background could fit, I’d be very happy to start remotely on a small task and contribute while learning the systems side.

My work:
GitHub: https://github.com/sushan5140
Minos-J: https://github.com/sushan5140/Minos-J

Thank you for reading.

Best regards,
SUSAN

## Sources
- https://miclab-koreatech.github.io/
- https://miclab-koreatech.github.io/publications/
