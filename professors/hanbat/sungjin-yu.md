# Sungjin Yu — Hanbat National University

- **University:** Hanbat National University
- **Lab:** Next-generation Convergence Security Lab (NCSL)
- **Email:** sj.yu@hanbat.ac.kr
- **Status:** DRAFTED
- **Last updated:** 2026-09-17

## Current evidence
- NCSL explicitly says it is always open to motivated graduate and undergraduate students.
- The lab currently lists multiple undergraduate researchers.
- Current themes: AI security, post-quantum cryptography, authentication, IoT/network security.
- Recent 2026 work: **A Modeling Attack-Resistant PUF-Enabled Robust Authentication and Key Agreement Scheme for Industrial Wireless Sensor Networks** (IEEE IoT Journal).

## Why this fits SUSAN
Use adversarial evaluation without pretending to be a cryptographer. Ask whether a learned attack detector/authentication model can look robust under average testing while failing on specific attack families or environment shifts.

## Email
**Subject:** Undergraduate research inquiry — finding hidden failure cases in ML-assisted security systems

Dear Professor Yu,

My name is SUSAN. I finished high school in India this year, and I’m preparing to apply for undergraduate study in AI/Computer Science in Korea through GKS.

I found NCSL while looking into AI security, and I was interested in your recent work on authentication schemes designed to remain robust against modeling attacks.

I’m not coming from a cryptography background yet, so the part that interested me most was the failure-testing side.

In some of my own ML work, a model looked reliable when everything was averaged together, but a much weaker case appeared when I checked the data more carefully.

That made me wonder about ML-assisted security systems. A detector or authentication component may look robust across a standard attack set while one family of attacks or one operating condition remains much easier to exploit.

I’d like to test that systematically rather than only add another attack model: keep the security mechanism fixed, vary one property of the attacker or environment at a time, and look for regions where the system’s confidence no longer matches its actual robustness.

I’m still early in security research, so I may be framing the problem too much like an ML evaluation task. I’d really value your opinion on whether this kind of stress testing would be useful.

I saw that NCSL is open to undergraduate researchers. If you think my background could fit, I’d be very happy to start remotely on a small evaluation task and learn the security side while contributing.

My work:
GitHub: https://github.com/sushan5140
Minos-J: https://github.com/sushan5140/Minos-J

Thank you for your time.

Best regards,
SUSAN

## Sources
- https://ncsllab.netlify.app/
