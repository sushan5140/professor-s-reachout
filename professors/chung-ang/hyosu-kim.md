# Hyosu Kim — Chung-Ang University

- **University:** Chung-Ang University
- **Lab:** Human-Centered Systems Laboratory (HCSLAB)
- **Area:** Real-time AI systems; on-device ML; resource-constrained inference
- **Email:** hskimhello@cau.ac.kr
- **Status:** DRAFTED
- **Last updated:** 2026-09-17

## Research hook

Use recent work on real-time / resource-constrained AI systems to ask whether a hard runtime budget changes not just latency but which evidence a RAG or multi-step reasoning system uses.

## Email

**Subject:** Undergraduate research inquiry — real-time constraints and AI reasoning

Dear Professor Kim,

My name is SUSAN. I finished high school in India this year and I’m currently preparing for undergraduate study in AI/Computer Science in Korea through GKS.

I came across HCSLAB while looking into on-device AI, and I spent some time reading through the lab’s recent work. CoRT especially made me think about something I hadn’t really considered before.

Most of the time when I thought about latency in an AI system, I treated it as a systems problem: how quickly can the model finish the same job?

But I started wondering whether, in systems that retrieve information or make several reasoning steps, a hard deadline might actually change the job the model ends up doing.

For example, imagine the same RAG query has one piece of evidence that is useful but relatively expensive to retrieve or process, and another that is easier to handle but weaker. Under a tight latency or resource limit, I’m curious whether the system begins consistently relying on the cheaper evidence — and whether that changes the answer rather than only changing the response time.

I’d like to test this with something small first: keep the model, questions and evidence pool fixed, vary the runtime constraint, and record which evidence survives and when the answers begin changing.

This is still a rough idea, and I may be connecting the systems and reasoning sides too aggressively. That is partly why I wanted to ask someone working directly on real-time and resource-constrained systems rather than try to turn it into a paper by myself.

I saw that HCSLAB is currently open to undergraduate researchers. If you think the question is interesting, I’d be very glad to contribute remotely and develop it under your guidance. I’d also be happy to work on an existing lab problem instead if that would be more useful.

My work:
GitHub: https://github.com/sushan5140
Minos-J: https://github.com/sushan5140/Minos-J

Thank you for reading.

Best regards,  
SUSAN
