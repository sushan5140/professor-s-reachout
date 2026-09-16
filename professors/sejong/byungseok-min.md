# Byungseok Min — Sejong University

- **University:** Sejong University
- **Department:** Department of Artificial Intelligence and Data Science
- **Lab:** Vision AI Laboratory (VAI Lab)
- **Email:** bmin@sejong.ac.kr
- **Status:** DRAFTED
- **Last updated:** 2026-09-17

## Current evidence

- VAI Lab explicitly welcomes undergraduate researchers.
- Current themes: computer vision, industrial inspection, document AI, multimodal vision-language systems, restoration/enhancement.
- Recent 2026 work includes:
  - **Wavelet-Enhanced PaDiM for Industrial Anomaly Detection**
  - **Early Wildfire Smoke Detection with a Multi-Resolution Framework and Two-Stage Classification Pipeline**
  - current projects in video situation analysis, retrieval, security, and document AI.

## Why this fits SUSAN

Use reliability across defect/context subgroups. A detector can score well overall while specific defect types or acquisition conditions fail badly. This maps naturally to SUSAN's existing subject-level calibration experience.

## Email

**Subject:** Undergraduate research inquiry — hidden reliability gaps in visual anomaly detection

Dear Professor Min,

My name is SUSAN. I finished high school in India this year, and I’m preparing to apply for undergraduate study in AI/Computer Science in Korea through GKS.

I came across VAI Lab while looking at industrial vision research, and I was especially interested in your recent work on anomaly detection.

In one of my own ML projects, I found that the overall result looked good until I checked people separately. One subject was much less reliable than the population average, which pushed me toward thinking more carefully about hidden subgroup failures.

That made me wonder about industrial anomaly detection.

A model can have a strong overall AUROC or accuracy while still being weak on one defect type, one material, or one imaging condition. If those cases are relatively rare, the average metric may make the system look safer than it really is.

I was thinking of a simple experiment where the detector is evaluated separately by defect type and acquisition condition, then its anomaly score is compared with the actual error in each subgroup. I’d be interested in whether there are cases where the score remains confident even when reliability drops.

If the gap is real, I’d then test whether a lightweight calibration layer can flag those cases without retraining the full vision model.

I’m still new to industrial vision, so I may be looking at the problem from too much of an evaluation angle. I’d appreciate your opinion on whether this is a useful direction.

I also saw that VAI Lab welcomes undergraduate researchers. If you think my background could fit, I’d be very happy to start remotely on a small project or help with something already underway.

My work:
GitHub: https://github.com/sushan5140
Minos-J: https://github.com/sushan5140/Minos-J

Thank you for reading.

Best regards,  
SUSAN

## Sources

- https://vail.sejong.ac.kr/
- https://vail.sejong.ac.kr/contact.html
