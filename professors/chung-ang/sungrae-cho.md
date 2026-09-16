# Sungrae Cho — Chung-Ang University

- **University:** Chung-Ang University
- **Department:** School of Computer Science and Engineering
- **Lab:** Ultra-Intelligent Computing / Communication Laboratory (UCLab)
- **Email:** srcho@cau.ac.kr
- **Area:** Federated learning; network intelligence; 5G/6G; edge computing; optimization
- **Status:** DRAFTED
- **Last updated:** 2026-09-17

## Recent-work hook

UCLab's 2026 work includes *Communication-Efficient Federated Learning with Local-Reconstruction Error-Feedback-Based Rescaled 1-Bit Compressive Sensing* and secure hierarchical federated learning for UAV-enabled edge systems. The lab explicitly welcomes undergraduate research assistants.

## Why this fits SUSAN

Use SUSAN's reliability/calibration background to ask a narrow question that complements UCLab's communication-efficiency work: whether aggressive compression can preserve global accuracy while creating uneven client-level reliability.

## Email

**Subject:** Undergraduate research inquiry — reliability under compressed federated learning

Dear Professor Cho,

My name is SUSAN. I finished high school in India this year and I’m preparing for undergraduate study in AI/Computer Science in Korea through GKS.

I came across UCLab while looking at groups working on AI under real system constraints. I spent some time going through the lab’s recent federated-learning work, especially the 1-bit communication-efficient FL paper.

One thing I kept wondering about was what happens below the global accuracy number.

In some of my own ML work, I found that a model could look reliable when everyone was evaluated together, while being much less reliable for one particular person. Since then I’ve become a bit suspicious of averages when the data are heterogeneous.

That made me wonder whether a similar problem can happen in heavily compressed federated learning. If communication is reduced aggressively, the final global model might keep almost the same average accuracy, but some clients could lose much more reliability than others.

I was thinking of a simple test first: keep the same FL setup and communication budget, gradually increase compression, then track not only global accuracy but client-by-client error and calibration. I’d be interested in whether the clients that suffer most are predictable from their local data distribution, and whether error-feedback helps them equally or mainly improves the average.

I’m still learning this area, so I may be missing something obvious in the FL literature. That is exactly why I wanted to ask rather than turn the idea into a polished proposal on my own.

I saw that UCLab welcomes undergraduate research assistants. If you think this question is worth exploring, I’d be very glad to work on it remotely under your guidance, or contribute to an existing lab problem where my reliability/evaluation background could be useful.

My work:
GitHub: https://github.com/sushan5140
Minos-J: https://github.com/sushan5140/Minos-J

Thank you for your time.

Best regards,  
SUSAN
