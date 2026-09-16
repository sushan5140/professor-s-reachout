# Sangyup Lee — Incheon National University

- **University:** Incheon National University
- **Department:** Computer Science & Engineering
- **Lab:** SecAI Lab
- **Email:** sangyup.lee@inu.ac.kr
- **Status:** DRAFTED_WITH_INTERNAL_PATH_NOTE
- **Last updated:** 2026-09-17

## Current evidence
- INU CSE operates a standing undergraduate internship route for enrolled students.
- SecAI Lab focuses on trustworthy AI, AI security, anomaly detection, representation learning, and LLM vulnerabilities.
- Recent 2026 work: **Mapping and comparing climate equity policy practices using RAG LLM-based semantic analysis and recommendation systems**.

## Why this fits SUSAN
Use RAG reliability and vulnerability monitoring. Ask whether semantic recommendations are stable when the retrieved evidence changes slightly.

## Email
**Subject:** Undergraduate research inquiry — stress-testing RAG recommendations under evidence changes

Dear Professor Lee,

My name is SUSAN. I finished high school in India this year and I’m preparing to apply for undergraduate study in AI/Computer Science in Korea through GKS.

I found SecAI Lab while looking through trustworthy AI and RAG security work, and your recent RAG-based semantic analysis paper made me think about a reliability question.

A recommendation can look reasonable even when it depends heavily on one retrieved document or one similarity match.

I’ve been building Minos-J around the idea of actively trying to break the reason a system gives for its answer, so I wondered whether the same approach could be useful here.

I’d start with correctly answered or recommended cases, then remove, replace, or slightly perturb one retrieved item at a time. I’d compare how much the final recommendation changes with how important the system claimed that evidence was.

I’m especially interested in cases where the output remains confident even though the supporting evidence has changed substantially.

I’m still early in RAG security, so I may be missing a better threat model. I’d really value your opinion.

I know INU’s undergraduate internship program is primarily for enrolled students, so I’m not assuming I qualify for that internal route. I wanted to ask whether you would consider a small remote pre-admission research task if you think my background could fit.

My work:
GitHub: https://github.com/sushan5140
Minos-J: https://github.com/sushan5140/Minos-J

Thank you for your time.

Best regards,
SUSAN

## Sources
- https://www.inu.ac.kr/isis_eng/10122/subview.do
- https://sites.google.com/view/secai-lab-inu/professor
- https://link.springer.com/article/10.1007/s43762-026-00279-0
