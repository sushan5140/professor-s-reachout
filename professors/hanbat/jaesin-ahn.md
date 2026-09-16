# Jaesin Ahn — Hanbat National University

- **University:** Hanbat National University
- **Lab:** Safe & Applied Intelligence Lab (SAIL)
- **Email:** ajs0420@hanbat.ac.kr
- **Status:** DRAFTED
- **Last updated:** 2026-09-17

## Current evidence
- SAIL is explicitly recruiting undergraduate research interns.
- Current themes: trustworthy AI, generative AI, NLP, computer vision, machine unlearning, mechanistic interpretability.
- Recent 2026 work: **Do Backdoored LLMs Share Internal Trigger Representations? Evidence from Frozen SAE Feature Banks** (Findings of EMNLP 2026).

## Why this fits SUSAN
Strong Minos-J overlap. Use the difference between detecting a backdoor behaviorally and identifying whether internal trigger features are actually shared across models.

## Email
**Subject:** Undergraduate research inquiry — auditing hidden trigger representations in LLMs

Dear Professor Ahn,

My name is SUSAN. I finished high school in India this year and I’m preparing to apply for undergraduate study in AI/Computer Science in Korea through GKS.

I found SAIL while looking into trustworthy AI, and your recent EMNLP work on backdoored LLMs and SAE feature banks caught my attention.

I’ve been building an independent project called Minos-J around a simple idea: if a system looks reliable at the output, try to actively find the hidden condition where that confidence breaks.

Your paper made me wonder about a similar distinction inside the model.

If two backdoored models show the same trigger behavior, does that necessarily mean they are using the same internal representation to get there? And if not, could an auditor that only looks for one known feature pattern miss a different implementation of the same failure?

I’d start with a small comparison: keep the trigger behavior fixed, compare several models or fine-tuning runs, and measure how stable the SAE features are across them. I’d then test whether behavior-level detection and representation-level detection disagree on the same examples.

I may be simplifying the interpretability side too much, so I’d really value your opinion on whether this is a useful question.

I saw that SAIL is currently recruiting undergraduate research interns. If you think my background could fit, I’d be very happy to start remotely on a small research task under your guidance.

My work:
GitHub: https://github.com/sushan5140
Minos-J: https://github.com/sushan5140/Minos-J

Thank you for reading.

Best regards,
SUSAN

## Sources
- https://sail-hanbat.github.io/
- https://sail-hanbat.github.io/publications/international/
