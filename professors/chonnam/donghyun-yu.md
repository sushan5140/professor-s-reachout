# Donghyun Yu — Chonnam National University

- **University:** Chonnam National University
- **School:** School of Artificial Intelligence
- **Lab:** Cryptography & Security Protocol Lab
- **Email:** donghyun.yu@jnu.ac.kr
- **Status:** DRAFTED
- **Last updated:** 2026-09-17

## Current evidence

- 2026 undergraduate-research recruitment is active/recent, with preference for 3rd-year+ students.
- Current lab themes include post-quantum cryptography, attribute-based encryption, digital signatures, federated learning, and AI security.
- Recent work includes the 2026 paper **Secure Data Sharing Framework With Fine-Grained Access Control and Privacy Protection for IoT Data Marketplace**.
- His current publication list also includes work on **secure/verifiable contribution evaluation in privacy-preserving federated learning** and a July 2026 research article on future directions for verifiable federated learning.

## Why this fits SUSAN

The strongest bridge is not pretending SUSAN is already a cryptography researcher. It is her existing interest in reliability and adversarial evaluation: asking whether a federated-learning system can verify that a client update is actually useful or harmful while still preserving privacy.

## Email

**Subject:** Undergraduate research inquiry — verifying unreliable updates in federated learning

Dear Professor Yu,

My name is SUSAN. I finished high school in India this year and I’m preparing to apply for undergraduate study in AI/Computer Science in Korea through GKS.

I came across your lab through the recent undergraduate researcher notice, and I spent some time looking through your work on secure data sharing and verifiable federated learning.

I’m not coming from a cryptography background yet, so the part that interested me most was the verification problem rather than the encryption itself.

In some of my own ML work, I’ve been focusing on cases where an overall result looks fine but one part of the system is quietly unreliable. That made me wonder about federated learning: if a client sends an update that is low-quality, misleading, or simply harmful to a subgroup, how much can the server actually tell about that without seeing the client’s private data?

A small experiment I’d like to try would be to simulate clients with different data quality and a few deliberately bad updates, then compare contribution or verification scores against the actual effect each update has on the global model and on individual client groups. I’d want to see where the verification signal stops matching the real usefulness of the update.

I’m still very new to the cryptographic side, so I may be framing this too much like an ML evaluation problem. That is partly why I wanted to ask you rather than make the idea sound more finished than it is.

I understand the current undergraduate-research notice mainly targets students already further into their degree, so I’m not assuming I qualify for that specific opening. I wanted to ask more generally whether you would ever consider letting a prospective undergraduate contribute remotely to a small research task before admission.

My work:
GitHub: https://github.com/sushan5140
Minos-J: https://github.com/sushan5140/Minos-J

Thank you for reading.

Best regards,  
SUSAN

## Sources

- https://sites.google.com/view/donghyunyuweb/home
- https://cloudweb.jnu.ac.kr/bbs/sw/1038/1054280/artclView.do
