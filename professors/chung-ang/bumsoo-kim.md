# Bumsoo Kim — Chung-Ang University

- **University:** Chung-Ang University
- **Lab:** MULTI Lab
- **Area:** Multimodal models; multi-agent reasoning; efficient AI
- **Email:** bumsoo@cau.ac.kr
- **Status:** DRAFTED
- **Last updated:** 2026-09-17

## Research hook

Connect Minos-J's generator/auditor separation with confidence-guided adaptive multi-agent debate. Core question: can multiple agents become confidently wrong for the same underlying reason?

## Email

**Subject:** Undergraduate research inquiry — reliable multi-agent reasoning

Dear Professor Kim,

My name is SUSAN. I recently finished high school in India and I’m preparing for undergraduate study in AI/Computer Science in Korea through GKS.

I found MULTI Lab while looking through work on multimodal and agentic AI, but the paper that caught my attention most was your recent work on confidence-guided adaptive debate.

I’ve been building an independent project called Minos-J around a slightly related problem. Instead of asking an LLM to generate another answer when something looks wrong, I’ve been experimenting with separating the system into a generator and an auditor whose job is to actively try to break the answer.

That made me wonder about the stopping side of multi-agent debate.

If several agents begin agreeing and their confidence becomes high, the system has a good reason to stop spending computation. But what if they are becoming confidently wrong for the same reason? In that case agreement itself could make the error harder to notice.

A small experiment I’d like to try is to keep the same models and roughly the same compute budget, but compare confidence-based stopping against a version where one independent agent is only allowed to search for contradictions or missing evidence. I’d want to see when that extra check actually helps and when it just wastes another reasoning round.

I’m still early enough that I may be framing the question badly, so I wouldn’t want to call this novel before getting feedback from someone working directly on the problem.

I saw that MULTI Lab also works with undergraduate researchers. If you think there is a useful direction here, I’d be very happy to start remotely, either on this question or by helping with something already underway in the lab.

My work:
GitHub: https://github.com/sushan5140
Minos-J: https://github.com/sushan5140/Minos-J

Thank you for your time.

Best regards,  
SUSAN
