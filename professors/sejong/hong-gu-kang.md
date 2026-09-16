# Hong-Gu Kang — Sejong University

- **University:** Sejong University
- **Department:** Department of Artificial Intelligence and Information Technology
- **Lab:** AI-to-Reality Technology Lab (ART Lab)
- **Email:** hkang@sejong.ac.kr
- **Status:** DRAFTED
- **Last updated:** 2026-09-17

## Current evidence

- ART Lab says it **always looks for undergraduate interns** and that suitable applicants can start on a small project before formal admission.
- Current research: on-device AI, edge-cloud collaboration, learning to defer, federated learning, model compression, domain adaptation/generalization, test-time adaptation, computer vision, NLP and robotics.
- Current 2026 projects explicitly study federated learning for heterogeneous on-device AI clients.
- Recent verified papers:
  - **FedSplitX: Federated Split Learning for Computationally-Constrained Heterogeneous Clients** — Neurocomputing, accepted 2026
  - **GeFL: Model-Agnostic Federated Learning with Generative Models** — IEEE TMC, 2026
  - **NeFL: Nested Model Scaling for Federated Learning with System Heterogeneous Clients** — IEEE TMC, 2025

## Why this fits SUSAN

Use reliability/calibration to study an edge-cloud cascade. A defer/routing rule based on confidence can fail when device heterogeneity or compression changes calibration. This is more specific to ART Lab than simply repeating the KNU on-device RAG idea.

## Email

**Subject:** Undergraduate research inquiry — when confidence decides edge vs cloud routing

Dear Professor Kang,

My name is SUSAN. I finished high school in India this year, and I’m preparing to apply for undergraduate study in AI/Computer Science in Korea through GKS.

I found ART Lab while looking into on-device AI, and I spent some time going through the lab’s work on heterogeneous clients, edge-cloud collaboration and learning to defer.

The routing part especially made me curious.

If an on-device model sends a difficult case to the cloud when its confidence is low, the decision sounds straightforward. But I started wondering what happens when different devices are running different model sizes, compression levels or hardware configurations.

In some of my own ML work, I found that confidence could look well behaved at the population level while being much less reliable for one person. That made me wonder whether the same thing can happen across devices: two local models may output the same confidence score even though that score means very different things after pruning, quantization or client-specific adaptation.

A small experiment I’d like to try is to keep the task fixed, run several heterogeneous local-model variants, and compare confidence-based defer decisions against the actual error each model makes. I’d then test whether a lightweight per-device calibration step improves the edge-vs-cloud routing decision without adding much extra compute.

I’m still learning the systems side of this, so I may be overlooking a cleaner formulation. I’d appreciate your opinion on whether the question is worth pursuing.

I also saw that ART Lab welcomes undergraduate interns and that small projects can begin before formal admission. If you think my background could fit, I’d be very happy to start remotely and contribute to a project under your guidance.

My work:
GitHub: https://github.com/sushan5140
Minos-J: https://github.com/sushan5140/Minos-J

Thank you for reading.

Best regards,  
SUSAN

## Sources

- https://artlab.sejong.ac.kr/home
- https://artlab.sejong.ac.kr/research
- https://artlab.sejong.ac.kr/publications
