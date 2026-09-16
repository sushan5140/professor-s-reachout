# Hyung Seok Kim — Sejong University

- **University:** Sejong University
- **Department:** AI and Robotics / Intelligent Mechatronics
- **Lab:** MINES Lab
- **Email:** hyungkim@sejong.ac.kr
- **Status:** DRAFTED
- **Last updated:** 2026-09-17

## Current evidence

- MINES Lab explicitly invites undergraduate students to contact Professor Kim; the lab page says there are no formal qualification conditions for joining.
- Current themes: AI robots, wearable AI, on-device AI, VLM/LLM, embedded intelligent systems.
- A 2026 JCCI project from the lab is **On-device AI-based Wearable Vision System for Visually Impaired**, using an on-device YOLO-based obstacle detection pipeline.

## Why this fits SUSAN

Use reliability under real-world constraints. The student-level question is whether detection confidence remains trustworthy across lighting, motion, and resource conditions in a wearable system, rather than proposing another full system.

## Email

**Subject:** Undergraduate research inquiry — reliability of wearable on-device vision

Dear Professor Kim,

My name is SUSAN. I finished high school in India this year, and I’m preparing to apply for undergraduate study in AI/Computer Science in Korea through GKS.

I found MINES Lab while looking into on-device and wearable AI. I was especially interested in the lab’s recent wearable vision work for helping visually impaired users avoid obstacles.

It made me think about something slightly different from raw detection accuracy.

In a wearable system, the same confidence score may not mean the same thing when lighting changes, the camera is moving, or the device is under a tighter compute load. A detection can still look confident even when the input has become much harder.

Most of my own work has been around reliability and calibration, so I wondered whether it would be useful to test that directly.

The first experiment I had in mind is small: keep the detector fixed, vary only one condition at a time — motion, lighting, blur or compute budget — and compare its confidence against the actual detection error. I’d want to see whether there are conditions where confidence stays high even though the system is becoming less dependable.

If that happens consistently, I’d then try a lightweight calibration or warning rule rather than changing the full detector.

I’m still early in embedded and robotics work, so I may be simplifying the systems side too much. I’d really value your opinion on whether this is a useful question.

I saw that your lab is open to undergraduate students who want to participate in research. If you think my background could fit, I’d be very happy to start remotely on a small task and learn the hardware side while contributing.

My work:
GitHub: https://github.com/sushan5140
Minos-J: https://github.com/sushan5140/Minos-J

Thank you for your time.

Best regards,  
SUSAN

## Sources

- https://prof.sejong.ac.kr/hyungkim/html/lab.do
- JCCI 2026: On-device AI-based Wearable Vision System for Visually Impaired
