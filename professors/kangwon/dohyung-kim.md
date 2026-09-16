# Dohyung Kim — Kangwon National University

- **University:** Kangwon National University
- **Department:** Computer Science and Engineering
- **Lab:** Intelligence in Computing & Networking Lab (ICN Lab)
- **Email:** d.kim@kangwon.ac.kr
- **Status:** DRAFTED
- **Last updated:** 2026-09-17

## Current evidence
- ICN Lab states that it is looking for talented and highly motivated students; it currently has an undergraduate intern working on efficient AI/LLMs.
- Current themes include energy-efficient LLM systems, AI-driven networking, caching, ML/RL for networks.
- Current 2026 NRF project: **Energy-Efficient LLM Services Through Adaptive Prompt Caching**.
- Recent paper: **LLM-Based System for Enhanced Text-to-Braille Translation: Incorporating Contextual Awareness and Automated Verification** (ACM SAC 2026).

## Why this fits SUSAN
Use the prompt-cache project. Ask whether cache reuse can save compute while accidentally carrying stale reasoning/context into a new request.

## Email
**Subject:** Undergraduate research inquiry — reliability of adaptive prompt caching for LLM services

Dear Professor Kim,

My name is SUSAN. I finished high school in India this year, and I’m preparing to apply for undergraduate study in AI/Computer Science in Korea through GKS.

I found ICN Lab while looking into efficient LLM systems, and your current project on adaptive prompt caching caught my attention.

I like the idea because caching looks like a systems optimization, but it can also change what context the model actually receives.

That made me wonder about the failure cases.

If two prompts look similar enough for the system to reuse cached information, but differ in one detail that matters to the answer, the system may save compute while quietly carrying the wrong context forward.

I was thinking of a small experiment where the cache policy is kept fixed and prompt pairs are constructed with gradually increasing semantic differences. I’d compare the compute saved against the first point where reuse begins changing the answer or evidence used.

I’d also like to see whether a simple uncertainty or contradiction check can identify unsafe cache hits before the model completes the response.

I’m still learning the systems side, so I may be simplifying how the cache is actually implemented. I’d really value your opinion on whether this is worth exploring.

I saw that ICN Lab currently works with undergraduate interns. If you think my background could fit, I’d be very happy to start remotely on a small research task.

My work:
GitHub: https://github.com/sushan5140
Minos-J: https://github.com/sushan5140/Minos-J

Thank you for reading.

Best regards,
SUSAN

## Sources
- https://www.icnlab.dev/
- https://www.icnlab.dev/projects
- https://www.icnlab.dev/publications
