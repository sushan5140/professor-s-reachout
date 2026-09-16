# Wonbo Shim — SeoulTech

- **University:** Seoul National University of Science and Technology (SeoulTech)
- **Department:** Electrical and Information Engineering
- **Lab:** Semiconductor Devices and Circuits Laboratory (SDCL)
- **Email:** wbshim@seoultech.ac.kr
- **Status:** DRAFTED
- **Last updated:** 2026-09-17

## Current evidence

- SDCL explicitly says it is currently looking for undergraduate students and undergraduate interns.
- The lab works on memory systems and processing-in-memory for modern AI models.
- Recent 2026 work includes:
  - **E-Flash: Energy-Efficient LLM Mapping on NAND Flash-Based In-Storage Inference Computing**
  - **A Configurable Analog In-Memory Computing Evaluation Framework for Transformer-based Large Language Model Inference**
  - **Design Space Exploration of High-Bandwidth 3D NAND for LLM Inference**.

## Why this fits SUSAN

SUSAN is not a hardware researcher yet, so keep the question at the hardware/software boundary: energy-efficient approximation or mapping may preserve average task accuracy while changing token-level reliability, especially on difficult or rare cases.

## Email

**Subject:** Undergraduate research inquiry — reliability tradeoffs in memory-based LLM inference

Dear Professor Shim,

My name is SUSAN. I finished high school in India this year, and I’m preparing to apply for undergraduate study in AI/Computer Science in Korea through GKS.

I found SDCL while looking into efficient AI inference, and I was interested in your recent work on NAND-based and in-memory LLM inference.

I’m still very new to the device side, but one question came to mind from the evaluation side.

When an AI system is made more efficient through a different memory architecture or approximation, we usually compare energy, latency and an overall accuracy number. I’m curious whether that can hide smaller reliability changes inside the model.

For example, two hardware configurations may have almost the same average task accuracy, while one of them makes more mistakes on low-probability tokens or difficult prompts because small numerical errors accumulate differently.

I was thinking of a simple software-level experiment first: emulate several precision or memory-noise conditions during transformer inference, then compare not only final accuracy but token-level probability shifts and which examples fail first. That could help identify which errors would actually matter before moving closer to hardware.

I may be approaching a hardware problem too much from the ML side, so I’d really value your opinion on whether this kind of evaluation would be useful.

I saw that SDCL is currently open to undergraduate interns. If you think my background could fit, I’d be very happy to start with a small simulation or evaluation task and learn the hardware side under your guidance.

My work:
GitHub: https://github.com/sushan5140
Minos-J: https://github.com/sushan5140/Minos-J

Thank you for reading.

Best regards,  
SUSAN

## Sources

- https://sites.google.com/view/sdclseoultech/home
- https://eie.seoultech.ac.kr/en/intro/faculty/?menu=1143&profidx=02633&togo=list
