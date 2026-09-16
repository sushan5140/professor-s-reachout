# Jemin Lee — Jeonbuk National University

- **University:** Jeonbuk National University
- **Department:** Computer Science & Artificial Intelligence
- **Lab:** Efficient Computing Lab (ECLab)
- **Email:** jemin.lee@jbnu.ac.kr
- **Status:** DRAFTED
- **Last updated:** 2026-09-17

## Current evidence

- ECLab currently has several undergraduate research interns and states that it is looking for motivated students.
- Current research includes efficient AI systems, LLM inference optimization, hardware-aware quantization, AI model compression, and systems for agentic AI.
- A current 2026 project studies hardware-aware quantization for LLM inference optimization on resource-constrained hardware.

## Why this fits SUSAN

Use the same broad systems/reliability theme as Han, but avoid repeating the RAG-deadline proposal. Ask whether quantization preserves average benchmark accuracy while changing confidence or failure concentration on hard prompts.

## Email

**Subject:** Undergraduate research inquiry — hidden reliability changes after LLM quantization

Dear Professor Lee,

My name is SUSAN. I finished high school in India this year and I’m preparing for undergraduate study in AI/Computer Science in Korea through GKS.

I found ECLab while looking through work on efficient AI systems, and I was especially interested in your current hardware-aware quantization work for LLM inference.

One thing I’ve been wondering about is what gets hidden by the usual “accuracy is almost unchanged” result.

A quantized model can keep nearly the same average benchmark score while the errors move around. The same number of questions may be wrong, but perhaps they become concentrated in harder prompts, certain reasoning steps, or cases where the original model was already uncertain.

Most of my own work has been around reliability and finding failures that disappear inside an average metric, so that felt like a useful question to test.

I’d start by comparing the same model across several quantization settings and tracking not only final accuracy, but confidence shifts and which examples change from correct to wrong. I’d be especially interested in whether those failures are predictable from the full-precision model’s uncertainty.

If they are, that might give a simple way to decide which requests should avoid the most aggressive quantization.

I’m still learning the systems and hardware side, so I may be missing a much better way to measure this. I’d really value your opinion.

I saw that ECLab already works with undergraduate research interns. If you think my evaluation background could be useful, I’d be very happy to start remotely on a small research task.

My work:
GitHub: https://github.com/sushan5140
Minos-J: https://github.com/sushan5140/Minos-J

Thank you for reading.

Best regards,  
SUSAN

## Sources

- https://eclab.jbnu.ac.kr/members/
- https://eclab.jbnu.ac.kr/research/4_research/
- https://csai.jbnu.ac.kr/
