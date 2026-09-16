# Joohyung Lee — Gachon University

- **University:** Gachon University
- **School:** School of Computing
- **Lab:** iMES Lab
- **Email:** j17.lee@gachon.ac.kr
- **Status:** DRAFTED
- **Last updated:** 2026-09-17

## Current evidence

- iMES Lab explicitly says it is looking for undergraduate researchers and warns against generic broadcast emails.
- Current themes: generative AI-enabled multimedia networking, distributed AI, intelligent agents, edge/cloud computing, federated learning, multimodal AI.
- Recent 2026 work includes:
  - Resource-Aware Federated Generative AI with Adaptive Model Training and Intelligent Data Selection for Efficient Disease Diagnosis.
  - AdaSplitLoRA: Adaptive Split Federated Learning for Efficient LLM Fine-Tuning in Wireless Networks.
  - Energy- and AoI-Aware Hierarchical Personalized Federated Learning for Distributed Edge Systems with Selective LLM Module Exchange.

## Why this fits SUSAN

Very clean systems/reliability question: selective LLM-module exchange saves communication, but could leave different clients with uneven reasoning quality. Ask whether global metrics hide client-specific degradation.

## Email

**Subject:** Undergraduate research inquiry — client-level reliability in federated LLM adaptation

Dear Professor Lee,

My name is SUSAN. I finished high school in India this year and I’m preparing for undergraduate study in AI/Computer Science in Korea through GKS.

I came across iMES Lab while looking into distributed AI, and I spent some time going through your recent work on split/federated LLM fine-tuning and selective module exchange.

One thing I kept wondering about was whether communication efficiency affects every client in the same way.

A method can reduce communication and keep almost the same global accuracy, while one client may lose much more than the others because its local data or model state is different.

In some of my own ML work, I found exactly that kind of problem at the subject level: the population result looked good while one person was much less reliable.

I’d like to test the same idea in a federated LLM setting. I would keep the overall communication budget fixed, vary which modules or updates different clients receive, and track not only global performance but client-by-client error and confidence. I’d be interested in whether the worst clients can be identified before the global metric visibly drops.

I’m still learning federated systems, so I may be missing a cleaner way to define the problem. I’d really value your opinion on whether it is useful.

I saw that iMES Lab is looking for undergraduate researchers and that you specifically ask students to align their message with the lab’s actual research. If you think my reliability/evaluation background could fit, I’d be very happy to start remotely on a small task under your guidance.

My work:
GitHub: https://github.com/sushan5140
Minos-J: https://github.com/sushan5140/Minos-J

Thank you for your time.

Best regards,  
SUSAN

## Sources

- https://sites.google.com/view/imeslab/main
- https://sites.google.com/view/imeslab/publications
