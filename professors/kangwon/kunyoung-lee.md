# Kunyoung Lee — Kangwon National University

- **University:** Kangwon National University
- **Department:** Computer Science and Engineering
- **Lab:** Pattern Recognition Lab (KNU-PRLAB)
- **Email:** kyle@kangwon.ac.kr
- **Area:** Computer vision; remote physiological sensing (rPPG); affective computing; driver monitoring
- **Status:** DRAFTED
- **Last updated:** 2026-09-17

## Recent-work hook

Professor Lee's recent work includes *Quality-Based rPPG Compensation With Temporal Difference Transformer for Camera-Based Driver Monitoring* (IEEE TITS, 2025). The lab also explicitly recruits undergraduate research interns and works on rPPG, physiological sensing, facial expression analysis, and affective computing.

## Why this fits SUSAN

SUSAN's physiological-ML work found that population-level performance can hide large subject-level reliability failures, which led to subject-conditional calibration. This gives a direct, believable bridge into rPPG reliability rather than forcing an unrelated LLM project into the email.

## Email

**Subject:** Undergraduate research inquiry — rPPG reliability across people and conditions

Dear Professor Lee,

My name is SUSAN. I finished high school in India this year, and I’m preparing to apply for undergraduate study in AI/Computer Science in Korea through GKS.

I found your lab while looking for groups working on physiological AI, and your rPPG work caught my attention because it is very close to a problem I ran into in my own project.

I was especially interested in your work on quality-based rPPG compensation for driver monitoring. What I liked about it was that the system is not only trying to estimate the signal, but also asking how trustworthy that estimate is when the environment becomes noisy.

In a physiological ML project I’ve been working on, I found something similar from a different direction. The model looked good when I only checked the overall result, but its reliability dropped quite a lot for one person. That pushed me toward subject-conditional calibration instead of assuming one confidence estimate would work equally well for everyone.

It made me wonder about rPPG systems: if a model learns to estimate signal quality under motion or driving noise, does that quality estimate stay reliable when the person changes too?

The first experiment I had in mind is quite small. I would use a leave-one-subject-out setup, compare the model's quality score with the actual physiological estimation error for each unseen person, and see where the two stop matching. If there is a consistent gap, I’d then test whether a lightweight calibration step can reduce it without retraining the full model.

I may be simplifying the problem too much, so I’d really value your opinion on whether this is a sensible question to pursue.

I also saw that KNU-PRLAB is openly recruiting undergraduate research interns. If you think my background could be useful, I’d be very happy to start remotely and help with something already going on in the lab as well.

My work:
GitHub: https://github.com/sushan5140
Minos-J: https://github.com/sushan5140/Minos-J

Thank you for reading.

Best regards,  
SUSAN
