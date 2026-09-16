# Yeonho Yoo — Dongguk University

- **University:** Dongguk University
- **Department:** Computer Science & Artificial Intelligence
- **Lab:** Intelligent Systems & Networking Lab (iSN Lab)
- **Email:** yhyoo@dgu.ac.kr
- **Status:** DRAFTED
- **Last updated:** 2026-09-17

## Current evidence

- iSN Lab explicitly states that it is recruiting undergraduate and graduate students.
- The lab currently has/has recently had multiple undergraduate interns.
- Current themes: AI systems, distributed AI training, MoE serving/compression, cloud/datacenter networking, edge computing, federated learning, lightweight AI.
- Recent 2026 work includes:
  - Residual Sparsification via Output Importance for Compressing Mixture-of-Experts LLMs (EMNLP 2026 main).
  - Xronos: Heterogeneity-Aware Tensor Parallelism for Collaborative LLM Fine-Tuning on Edge CPUs (MASCOTS 2026).
  - Accurate Simulation of Distributed Training Jobs with Network Contention Modeling (MASCOTS 2026).
  - Prediction-based GPU Sharing for Distributed Training (FGCS 2026).

## Why this fits SUSAN

Ask whether MoE compression preserves benchmark accuracy while quietly changing expert-routing behavior on difficult inputs. This is specific to the recent EMNLP work and aligns with SUSAN's reliability interest.

## Email

**Subject:** Undergraduate research inquiry — hidden routing changes after MoE compression

Dear Professor Yoo,

My name is SUSAN. I finished high school in India this year and I’m preparing for undergraduate study in AI/Computer Science in Korea through GKS.

I found iSN Lab while looking into efficient AI systems, and your recent EMNLP work on compressing Mixture-of-Experts models caught my attention.

The part I kept thinking about was what happens to routing after compression.

A compressed MoE model can keep almost the same final benchmark score, but the experts it relies on may change for certain inputs. If those changes are concentrated in difficult or unusual prompts, the average metric might not make them obvious.

Most of my own work has been around reliability and cases where a system looks fine overall while a smaller group of examples fails badly, so I thought this could be worth checking.

I’d start by comparing the same MoE model before and after residual sparsification, then track which tokens change expert routes and which examples change from correct to wrong. I’d be interested in whether routing instability can predict the failures better than the final confidence score.

I’m still new to model-serving and compression systems, so I may be approaching the problem too much from the evaluation side. I’d really value your opinion on whether this is a useful question.

I saw that iSN Lab is currently recruiting undergraduate students. If you think my background could fit, I’d be very happy to start remotely on a small research task and learn the systems side while contributing.

My work:
GitHub: https://github.com/sushan5140
Minos-J: https://github.com/sushan5140/Minos-J

Thank you for reading.

Best regards,  
SUSAN

## Sources

- https://isn.dongguk.edu/
- https://ai.dongguk.edu/professor/list
