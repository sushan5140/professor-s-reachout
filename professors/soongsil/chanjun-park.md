# Chanjun Park — Soongsil University

- **University:** Soongsil University
- **School:** School of Software
- **Lab:** NLP Lab
- **Email:** chanjun.park@ssu.ac.kr
- **Status:** DRAFTED
- **Last updated:** 2026-09-17

## Current evidence

- The NLP Lab apply page explicitly says it is **currently looking for undergraduate interns**, M.S., and Ph.D. students.
- The lab currently has undergraduate researchers working on LLM evaluation and interpretability.
- Recent 2026 work includes:
  - **Beyond Consensus: Downward Bias and Role Asymmetry in Multi-Agent LLM Judges for Subjective Evaluation** (Aug 2026)
  - **Skill Following: Evaluating Actual Skill Use in Retrieval-Enabled LLM Agents** (Sep 2026)
  - **The Agent Loop: A Survey of Control Strategies, Skills, and Harnesses for LLM Agents** (2026)

## Why this fits SUSAN

This is one of the cleanest Minos-J matches. Instead of pitching another generic agent-evaluation idea, connect Minos-J's auditor/falsification philosophy to the lab's recent finding that aggregate metrics can make retrieved skills appear useful even when they hurt the exact tasks where retrieval occurred.

## Email

**Subject:** Undergraduate research inquiry — when an agent looks better but the retrieved skill hurts

Dear Professor Park,

My name is SUSAN. I finished high school in India this year, and I’m preparing to apply for undergraduate study in AI/Computer Science in Korea through GKS.

I found your NLP Lab while looking for groups working on LLM evaluation and agents, and your recent Skill Following paper caught my attention.

The part that stayed with me was the result that retrieval can look helpful in the aggregate while actually hurting the exact tasks where the model decided to retrieve a skill. I’ve been working on an independent project called Minos-J where I keep running into a similar problem from another direction: a system can look improved under the final metric while the mechanism that supposedly caused the improvement is not actually doing what we think it is.

That made me wonder whether the same matched-execution idea could be pushed one step further inside the agent loop.

For example, if an agent retrieves a skill and then succeeds, I’d like to compare that run not only against the same task without the skill, but against a run where the skill is retrieved and deliberately blocked from affecting one stage at a time — planning, tool choice, or final answer generation. I’m curious whether that would tell us where the skill is genuinely helping instead of only whether retrieval happened.

I would start with a small number of skills and tasks rather than trying to build a large benchmark immediately.

I may be overcomplicating a question your paper already answers more cleanly, so I’d really value your opinion on whether this decomposition is useful.

I saw that your lab is currently looking for undergraduate interns. If you think my background could fit, I’d be very happy to start remotely on a small research task or contribute to something already underway in the lab.

My work:
GitHub: https://github.com/sushan5140
Minos-J: https://github.com/sushan5140/Minos-J

Thank you for reading.

Best regards,  
SUSAN

## Sources

- https://nlp.ssu.ac.kr/apply
- https://nlp.ssu.ac.kr/members
- https://arxiv.org/abs/2609.00549
- https://doi.org/10.48550/arXiv.2608.30373
