# Hyeon-Ju Yoon — Kumoh National Institute of Technology

- **University:** Kumoh National Institute of Technology
- **Department:** Department of Computer Engineering
- **Lab:** System Software Lab (SSL)
- **Email:** juyoon@kumoh.ac.kr
- **Status:** DRAFTED_WITH_ELIGIBILITY_CAVEAT
- **Last updated:** 2026-09-17

## Current evidence

- SSL posted a fresh undergraduate-researcher recruitment notice on 2026-09-14 for 2–3 students, deadline 2026-09-20.
- The current opening is restricted to Kumoh School of Computer Engineering students in years 1–3, so SUSAN should **not** present herself as eligible for that specific call.
- Official Kumoh faculty pages verify Professor Yoon and the email juyoon@kumoh.ac.kr.
- Publicly indexed recent publication material is sparse. Verified older work includes Android platform performance profiling and embedded/system-software research. Do not invent a recent-paper hook.

## Why this fits SUSAN

Use SUSAN's interest in reliability under resource constraints. The clean bridge is systems profiling: when an AI workload runs on a constrained device, average latency can hide unstable tail behavior or resource contention. Ask whether lightweight system-level profiling can identify when an AI service is about to violate its latency or memory budget.

## Email

**Subject:** Undergraduate research inquiry — profiling AI workloads under system constraints

Dear Professor Yoon,

My name is SUSAN. I finished high school in India this year, and I’m preparing to apply for undergraduate study in AI/Computer Science in Korea through GKS.

I came across the recent System Software Lab undergraduate researcher notice. I understand that the current opening is for students who are already enrolled at Kumoh, so I’m not writing to apply to that specific position.

What caught my attention was the systems side of the lab. I also found your earlier work on Android performance analysis and profiling, and it made me think about a problem I’ve been running into while working with AI systems.

A lot of AI projects report an average latency or memory number and stop there. But on a constrained device, I’m curious about the cases where the average still looks fine while a few requests suddenly become much slower or use much more memory.

I was thinking of a small experiment where the same lightweight AI workload is run under controlled CPU, memory and background-load conditions, while a system-level profiler records what changes before a latency spike or failure. I’d want to see whether a small set of operating-system signals can predict those bad cases early enough to change how the workload is scheduled.

This is still a rough systems question, and I may be simplifying it too much. I’d really value your opinion on whether it is a sensible direction for someone at my stage to explore.

Since I’m only a prospective undergraduate right now, I wanted to ask whether you would ever consider a small remote research task before admission, separate from the current internal recruitment.

My work:
GitHub: https://github.com/sushan5140
Minos-J: https://github.com/sushan5140/Minos-J

Thank you for reading.

Best regards,  
SUSAN

## Sources

- https://www.kumoh.ac.kr/ai/sub0501.do?articleNo=577353&mode=view
- https://eng.kumoh.ac.kr/eng/sub02_01_01_02_02.do
