# Kyungsu Lee — Jeonbuk National University

- **University:** Jeonbuk National University
- **Lab:** Medical AI & Computational Science Laboratory (MACS Lab)
- **Email:** ksl@jbnu.ac.kr
- **Status:** DRAFTED
- **Last updated:** 2026-09-17

## Current evidence

- MACS Lab has an explicit Fall 2026 undergraduate research assistant recruitment notice.
- The lab currently lists eight undergraduate researchers.
- Current themes: trustworthy medical AI, multimodal medical AI, vision-language intelligence, domain/test-time adaptation, uncertainty.
- Recent 2026 work includes:
  - Uncertainty-Aware Bayesian Prompt Adaptation for Robust Cross-Modality Medical Segmentation (MICCAI 2026).
  - Dynamic Sub-domain Modeling for Robust Medical Image Segmentation (MICCAI 2026).
  - Human-Intervention Segmentation via Federated Intent Embedding and Multi-Mask Recommendation (CVPR 2026).

## Why this fits SUSAN

Strong reliability fit. Ask whether uncertainty-aware adaptation actually remains calibrated across hospitals/modalities, instead of only improving segmentation metrics.

## Email

**Subject:** Undergraduate research inquiry — calibration after cross-modality medical adaptation

Dear Professor Lee,

My name is SUSAN. I finished high school in India this year and I’m preparing for undergraduate study in AI/Computer Science in Korea through GKS.

I found MACS Lab through the Fall undergraduate-research notice, and your recent work on uncertainty-aware prompt adaptation for cross-modality medical segmentation caught my attention.

The uncertainty part is what made me stop and think.

In a physiological ML project I’ve been working on, a model could look reliable across the full population while being much less reliable for one person. That pushed me toward checking calibration at the subject level rather than trusting the overall number.

I started wondering whether a similar problem can happen after medical-domain adaptation.

An adaptation method may improve Dice or segmentation accuracy on a new modality, but does the model’s uncertainty become more trustworthy too? Or can performance improve while confidence remains badly calibrated for some hospitals, scanners, or sub-domains?

I’d start by taking an adapted segmentation model and measuring performance and calibration separately across the target sub-domains. If the two move differently, I’d then test whether the adaptation uncertainty itself can be used to flag the least reliable cases.

I may be translating a reliability question from another area too directly into medical imaging, so I’d really value your opinion on whether it makes sense clinically and technically.

I saw that MACS Lab is currently recruiting undergraduate researchers. If you think my background could fit, I’d be very happy to start remotely on a small evaluation task and learn the medical side while contributing.

My work:
GitHub: https://github.com/sushan5140
Minos-J: https://github.com/sushan5140/Minos-J

Thank you for your time.

Best regards,  
SUSAN

## Sources

- https://jbnu.macs.or.kr/en/
- https://jbnu.macs.or.kr/en/publication/
- https://jbnu.macs.or.kr/en/people/
