# Byungkook Oh — Konkuk University

- **University:** Konkuk University
- **Lab:** Graph & Language Intelligence Lab (GLI Lab)
- **Email:** bkoh@konkuk.ac.kr
- **Status:** DRAFTED
- **Last updated:** 2026-09-17

## Current evidence

- GLI Lab explicitly states that it is currently seeking undergraduate research interns.
- Current themes: graph ML, knowledge-based systems, NLP, anomaly detection, recommender systems, GraphRAG and agentic systems.
- Recent 2026 work includes:
  - Causality-Guided Spurious Evidence Pruning with GFlowNet for Faithful Graph Retrieval (CIKM 2026).
  - Internalizing Negation-Gated Logical Rules into LLMs for Document-Level Relation Extraction (Findings of EMNLP 2026).
  - Ongoing Temporal Knowledge Graph Question Answering with GraphRAG.

## Why this fits SUSAN

Very strong Minos-J overlap. Ask whether retrieval systems can look correct because the answer is right while still depending on spurious evidence. The natural extension is a falsification test that removes/replaces evidence and observes whether the answer remains stable for the right reason.

## Email

**Subject:** Undergraduate research inquiry — testing whether GraphRAG answers are right for the right evidence

Dear Professor Oh,

My name is SUSAN. I finished high school in India this year and I’m preparing for undergraduate study in AI/Computer Science in Korea through GKS.

I found GLI Lab while looking through work on reliable retrieval and graph reasoning, and your recent paper on causality-guided spurious evidence pruning caught my attention.

I’ve been building an independent project called Minos-J around a simple idea: instead of only asking whether an answer is correct, try to actively break the reason the system used to get there.

Your retrieval work made me wonder about that exact distinction.

A GraphRAG system can produce the right answer while depending on evidence that is only accidentally correlated with it. If we only score the answer, that failure is invisible.

I was thinking of a small falsification-style experiment: take correctly answered questions, remove or replace one retrieved subgraph at a time, and compare the answer change with the model’s claimed evidence importance. I’d want to separate cases where the answer is stable because the system has redundant valid evidence from cases where it is stable because the model is ignoring retrieval altogether.

I’m not treating this as a finished proposal, and your current work may already have a much cleaner causal formulation. I’d really value your opinion on whether this would add anything useful.

I saw that GLI Lab is currently looking for undergraduate research interns. If you think my background could fit, I’d be very happy to start remotely on a small research task under your guidance.

My work:
GitHub: https://github.com/sushan5140
Minos-J: https://github.com/sushan5140/Minos-J

Thank you for reading.

Best regards,  
SUSAN

## Sources

- https://gli.konkuk.ac.kr/
- https://gli.konkuk.ac.kr/publications/papers/
