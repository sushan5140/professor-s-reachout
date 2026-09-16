# Howon Lee — Ajou University

- **University:** Ajou University
- **Lab:** AI-empowered Communication Systems Laboratory (ACELAB)
- **Email:** howon@ajou.ac.kr
- **Status:** DRAFTED
- **Last updated:** 2026-09-17

## Current evidence

- ACELAB explicitly recruits undergraduate interns in AI/ML/LLM-based communication systems, AI-RAN, 6G, UAV communication, and satellite communication.
- Recent 2026 work includes:
  - Jointly Optimizing Frequency Reuse and Transmit Power for LEO Satellite Networks via Collaborative DRL with Information Sharing.
  - MOSAIC: Multi-User OFDM-Based Sensing and Inherent Communication for 6G Mobile Networks.
  - Multiple 2026 papers on multi-agent / hierarchical DRL for UAV and LEO resource allocation.

## Why this fits SUSAN

Use reliability under multi-agent coordination rather than pretending SUSAN is already a communications researcher. The question: can cooperative agents look strong on average while one agent's local policy becomes unreliable when topology or visibility changes?

## Email

**Subject:** Undergraduate research inquiry — reliability in collaborative DRL under changing network conditions

Dear Professor Lee,

My name is SUSAN. I finished high school in India this year and I’m preparing for undergraduate study in AI/Computer Science in Korea through GKS.

I found ACELAB while looking through work on AI for communication systems, and your recent collaborative DRL work for LEO satellite networks caught my attention.

What I kept thinking about was what happens when the environment changes faster than the agents expect.

A collaborative policy may keep a strong average reward, but one satellite or node could start making much worse decisions when visibility time, interference, or traffic changes. If the other agents compensate for it, the global result may still look fine and hide that local failure.

Most of my own work has been around reliability and cases where an overall metric hides a much weaker subgroup. That made me wonder whether a similar effect can appear in collaborative DRL.

I would start small: keep the learned policy fixed, introduce controlled changes in visibility or traffic for only one agent, and compare the global reward with that agent's local decision quality. I’d want to see whether there is an early signal that tells us the policy is becoming unreliable before the full system performance drops.

I’m still new to communication systems, so I may be simplifying the network side too much. I’d really value your opinion on whether this is a useful question.

I saw that ACELAB is recruiting undergraduate interns. If you think my background could fit, I’d be very happy to start remotely on a small research task and learn the communications side while contributing.

My work:
GitHub: https://github.com/sushan5140
Minos-J: https://github.com/sushan5140/Minos-J

Thank you for reading.

Best regards,  
SUSAN

## Sources

- https://acelab.ajou.ac.kr/
- https://acelab.ajou.ac.kr/publications
