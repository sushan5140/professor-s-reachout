# Eunji Jun — Sejong University

- **University:** Sejong University
- **Department:** Department of Computer Science and Engineering
- **Lab:** Biomedical Intelligence & Machine Learning Lab (BIML)
- **Email:** eunji.jun@sejong.ac.kr
- **Status:** DRAFTED
- **Last updated:** 2026-09-17

## Current evidence

- BIML explicitly states that it is looking for undergraduate interns in computer vision, machine learning and AI.
- Current lab themes include biomedical imaging, medical report generation, brain decoding, multimodal learning, multimodal LLMs and explainability.
- Verified work includes:
  - **Medical Transformer: Universal Encoder for 3D Brain MRI Analysis** (IEEE TNNLS, 2024)
  - **Uncertainty-Aware Variational-Recurrent Imputation Network for Clinical Time Series**
  - **Multi-view Integrative Attention-based Deep Representation Learning for Irregular Clinical Time-series Data**
  - 2025 ICCV work on sparse-view transparent-object depth reconstruction.

## Why this fits SUSAN

Do not duplicate the Hyun-Chul Kim email. The strongest distinct angle here is **uncertainty propagation**: when missing clinical/physiological data are imputed, the downstream model may become confident even though the reconstructed input was uncertain. SUSAN's calibration work gives a natural bridge.

## Email

**Subject:** Undergraduate research inquiry — when imputation uncertainty disappears downstream

Dear Professor Jun,

My name is SUSAN. I finished high school in India this year, and I’m preparing to apply for undergraduate study in AI/Computer Science in Korea through GKS.

I found BIML while looking for groups working on biomedical AI, and I spent some time reading through your work on irregular clinical time-series data and uncertainty-aware imputation.

One part of it made me wonder about what happens after the missing data have already been filled in.

In a physiological ML project I’ve been working on, I found that a model could look reliable overall while being much less reliable for a particular person. Since then I’ve been paying a lot more attention to whether confidence actually matches the uncertainty in the input.

With imputed clinical data, I’m curious whether the downstream prediction model can become too confident because it only sees the reconstructed value and not how uncertain that reconstruction was.

The first experiment I had in mind is small: take the same downstream prediction task, compare clean observations with progressively more missing data, and track both imputation uncertainty and final prediction confidence. I’d want to see where the downstream model starts acting more certain than the reconstructed input really justifies.

If that gap is consistent, I’d then test whether passing a simple uncertainty signal from the imputation stage into the predictor improves calibration without changing the whole model.

I may be connecting the two stages too simply, so I’d really value your opinion on whether this is a useful question.

I also saw that BIML is currently open to undergraduate interns. If you think my background could be useful, I’d be very happy to start remotely on a small task or contribute to something already happening in the lab.

My work:
GitHub: https://github.com/sushan5140
Minos-J: https://github.com/sushan5140/Minos-J

Thank you for your time.

Best regards,  
SUSAN

## Sources

- https://biml.sejong.ac.kr/
- https://biml.sejong.ac.kr/contact
- https://biml.sejong.ac.kr/publications
