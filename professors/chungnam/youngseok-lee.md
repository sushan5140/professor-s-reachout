# Youngseok Lee — Chungnam National University

- **University:** Chungnam National University
- **Department:** Computer Engineering / Computer AI
- **Lab:** Data Networks Lab (DNLAB)
- **Email:** lee@cnu.ac.kr
- **Status:** DRAFTED
- **Last updated:** 2026-09-17

## Current evidence

- DNLAB explicitly advertises 2026 recruitment for undergraduate researchers alongside graduate students.
- Current topics include LLM fine-tuning, network-data analysis, AI agents for radio/BGP analysis, and automated music-light systems.
- The current lab page specifically calls for students interested in AI-agent research.

## Why this fits SUSAN

Use Minos-J's auditor mindset for network-analysis agents. An LLM agent can produce a plausible diagnosis of a BGP/radio event while grounding itself in the wrong evidence. Ask whether a separate evidence-checking agent catches these failures better than self-review.

## Email

**Subject:** Undergraduate research inquiry — auditing AI agents for network-data analysis

Dear Professor Lee,

My name is SUSAN. I finished high school in India this year and I’m preparing for undergraduate study in AI/Computer Science in Korea through GKS.

I found DNLAB through the 2026 undergraduate-research notice, and the current work on AI agents for radio and BGP analysis caught my attention.

I’ve been building an independent project called Minos-J where I separate a generator from an auditor whose only job is to look for reasons the answer may be wrong.

That made me wonder how useful the same separation would be for network-analysis agents.

A language-model agent can give a very plausible explanation for a routing or radio event even if it has relied on the wrong log entries or skipped one piece of evidence. If the same agent then reviews its own answer, I’m not sure it will notice the mistake that led it there.

A small experiment I’d like to try is to create network-analysis cases with a known evidence trail, then compare self-review against an independent auditor that only sees the raw evidence and the proposed diagnosis. I’d want to measure not just whether the final answer is right, but whether the system can point to the evidence that actually supports it.

I’m still new to network measurement, so I may be describing a problem that is much easier to formulate with domain-specific checks. I’d really value your opinion.

I saw that DNLAB is recruiting undergraduate researchers for AI-agent topics. If you think my background could fit, I’d be very happy to start remotely and work on a small research task under your guidance.

My work:
GitHub: https://github.com/sushan5140
Minos-J: https://github.com/sushan5140/Minos-J

Thank you for reading.

Best regards,  
SUSAN

## Sources

- https://dnlab.cs-cnu.org/
- https://yslee.cs-cnu.org/
