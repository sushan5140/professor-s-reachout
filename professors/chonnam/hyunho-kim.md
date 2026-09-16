# Hyunho Kim — Chonnam National University

- **University:** Chonnam National University
- **School:** School of Artificial Intelligence
- **Lab:** Life Science and AI Lab (LSAIL)
- **Email:** hyunhokim@jnu.ac.kr
- **Status:** DRAFTED
- **Last updated:** 2026-09-17

## Current evidence

- LSAIL explicitly says it is actively recruiting graduate and undergraduate researchers.
- Current lab themes: AI drug discovery, generative/predictive molecular modeling, integrative biological data science, biology-aware AI, and agentic LLM frameworks.
- Recent publication: **A genotype-to-drug diffusion model for generation of tailored anti-cancer small molecules**, Nature Communications (2025).
- Another 2025 lab publication studies multi-task in-vivo toxicity prediction using chemical knowledge and in-vitro toxicity information.

## Why this fits SUSAN

Use SUSAN's reliability/calibration background, not a fake biology background. The question is whether a personalized generative drug model can look strong in aggregate while failing for rarer genotype contexts, and how to detect/calibrate that.

## Email

**Subject:** Undergraduate research inquiry — reliability in genotype-conditioned drug generation

Dear Professor Kim,

My name is SUSAN. I finished high school in India this year, and I’m preparing to apply for undergraduate study in AI/Computer Science in Korea through GKS.

I found LSAIL through the recent undergraduate researcher notice, and I ended up reading about your genotype-to-drug diffusion work.

I don’t have a biology background yet, but the AI side of that paper connected with a problem I’ve been working on in a very different setting.

In a physiological ML project, I found that a model could look reliable across the full population while becoming much less reliable for one person. That pushed me toward checking performance and calibration at the subject level instead of trusting the average.

It made me wonder about genotype-conditioned molecular generation. If the model is conditioned on many different genomic contexts, could it look good overall while being much less trustworthy for a smaller or less represented genotype pattern?

The first thing I would want to test is fairly simple: group generated candidates by how common or unusual the conditioning profile is, then compare validity, predicted activity and model confidence across those groups. If the reliability gap grows for rarer conditions, I’d then test whether a lightweight calibration or uncertainty filter could flag those cases before candidate prioritization.

I may be translating a reliability idea from another field too directly into drug discovery, so I would really value your opinion on whether the question makes biological sense before trying to develop it further.

I saw that LSAIL is actively looking for undergraduate researchers. If you think my AI/evaluation background could be useful, I’d be very happy to start remotely on a small task and learn the biological side while contributing.

My work:
GitHub: https://github.com/sushan5140
Minos-J: https://github.com/sushan5140/Minos-J

Thank you for your time.

Best regards,  
SUSAN

## Sources

- https://lsail-jnu.github.io/
- https://lsail-jnu.github.io/publications.html
- https://sw.jnu.ac.kr/bbs/sw/1038/1053364/artclView.do
