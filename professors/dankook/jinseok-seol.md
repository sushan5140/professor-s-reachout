# Jinseok Seol — Dankook University

- **University:** Dankook University
- **Lab:** Information Retrieval & Data Mining Lab (IRDM Lab)
- **Email:** jinseok.seol@dankook.ac.kr
- **Status:** DRAFTED
- **Last updated:** 2026-09-17

## Current evidence
- IRDM Lab explicitly says it is looking for undergraduate interns.
- Current topics include LLM-based recommender systems, Text-to-SQL, bias detection/correction, model interpretability, pruning and distillation.
- Recent 2026 work includes **Task-aware Block Pruning with Output Distribution Signals for Large Language Models** (Findings of EACL 2026) and **PALRec** on LLM-based sequential recommendation.

## Why this fits SUSAN
Use the reliability angle around pruning. A pruned model may preserve average task accuracy while changing confidence or internal behavior on the hardest examples.

## Email
**Subject:** Undergraduate research inquiry — hidden reliability changes after LLM pruning

Dear Professor Seol,

My name is SUSAN. I finished high school in India this year, and I’m preparing to apply for undergraduate study in AI/Computer Science in Korea through GKS.

I found IRDM Lab while looking through work on efficient LLMs and evaluation, and your recent EACL paper on task-aware block pruning caught my attention.

The part I kept thinking about was what “preserving performance” really means after pruning.

A smaller model can keep almost the same average task score, but the mistakes may move around. Some hard examples may become much less reliable even if the benchmark number barely changes.

Most of my own work has been around exactly that kind of hidden reliability gap, so I thought this could be worth testing directly.

I’d start with the same model before and after pruning, then track not only final accuracy but confidence shifts and which examples change from correct to wrong. I’d be especially interested in whether the blocks that look unimportant on average matter much more for a small subset of difficult inputs.

I’m still early in model compression, so I may be looking at the problem too much from the evaluation side. I’d really value your opinion on whether this is a useful question.

I saw that IRDM Lab is currently looking for undergraduate interns. If you think my background could fit, I’d be very happy to start remotely on a small research task and learn the efficiency side while contributing.

My work:
GitHub: https://github.com/sushan5140
Minos-J: https://github.com/sushan5140/Minos-J

Thank you for reading.

Best regards,
SUSAN

## Sources
- https://dku-irdm.github.io/
- https://dku-irdm.github.io/about/
- https://aclanthology.org/people/jinseok-seol/
