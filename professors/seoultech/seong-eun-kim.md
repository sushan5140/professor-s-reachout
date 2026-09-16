# Seong-Eun Kim — SeoulTech

- **University:** Seoul National University of Science and Technology (SeoulTech)
- **Department:** Applied Artificial Intelligence
- **Lab:** Brain and Artificial Intelligence Lab (BrAIn Lab)
- **Email:** sekim@seoultech.ac.kr
- **Status:** DRAFTED
- **Last updated:** 2026-09-17

## Current evidence

- BrAIn Lab explicitly says it is always seeking undergraduate research assistants.
- Current themes: brain science, physiological signals, brain-inspired AI, biomedical AI.
- Recent 2026 work includes:
  - **MILFNet: Multiple Instance Learning-Based FastSlow Network with Multitask Autoencoder for Cross-Subject EEG Emotion Recognition**
  - **Measurement and Evaluation of Evoked Dual-Channel Ear-EEG Biometrics...**
  - **Smartphone-Based Detection of Abnormal Lung Sounds Using Domain-Adaptive Deep Learning**.

## Why this fits SUSAN

Very strong direct overlap with SUSAN's physiological ML work on subject-conditional calibration. Keep it concrete: cross-subject EEG models may preserve average accuracy while confidence becomes unreliable for specific unseen subjects.

## Email

**Subject:** Undergraduate research inquiry — subject-level calibration in cross-subject EEG models

Dear Professor Kim,

My name is SUSAN. I finished high school in India this year, and I’m preparing to apply for undergraduate study in AI/Computer Science in Korea through GKS.

I found BrAIn Lab while looking for groups working on physiological signals and reliable AI, and your recent cross-subject EEG emotion-recognition work felt very close to a problem I’ve been working on myself.

In one of my physiological ML experiments, the model looked good when I checked the whole population together. But when I looked at the person it struggled with most, the reliability dropped much more than the average suggested.

That pushed me toward subject-conditional calibration.

Seeing your cross-subject EEG work made me wonder whether the same issue appears there: a representation may transfer well enough to keep the overall accuracy strong, while the confidence for certain unseen subjects becomes poorly calibrated.

The first experiment I had in mind is simple. I’d keep a leave-one-subject-out setup, measure both accuracy and calibration for every held-out person, and identify the subjects where confidence and correctness separate most. Then I’d test whether a lightweight subject-adaptive calibration step can reduce that gap without retraining the whole model.

This is still a rough idea, and I may be missing a better physiological explanation for why those subjects fail. I’d really value your opinion on whether the question is worth pursuing.

I saw that BrAIn Lab welcomes undergraduate research assistants. If you think my background could be useful, I’d be very happy to start remotely on a small task and contribute to something already happening in the lab.

My work:
GitHub: https://github.com/sushan5140
Minos-J: https://github.com/sushan5140/Minos-J

Thank you for your time.

Best regards,  
SUSAN

## Sources

- https://www.brainailab.com/
- https://pure.seoultech.ac.kr/en/persons/seong-eun-kim/
