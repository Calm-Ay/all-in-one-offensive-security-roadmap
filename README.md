# Offensive AI + Cloud Red Teaming Roadmap 2026

![Type](https://img.shields.io/badge/Type-Specialization%20Roadmap-red?style=for-the-badge&logo=hackaday)
![Focus](https://img.shields.io/badge/Focus-AI%20%2B%20Cloud%20Offensive-critical?style=for-the-badge)
![Duration](https://img.shields.io/badge/Plan-12%20Weeks-brightgreen?style=for-the-badge)
![Author](https://img.shields.io/badge/Author-Rasaq%20Ayomide-blue?style=for-the-badge)

> The ultimate specialization path for penetration testers — layering **Offensive AI/LLM Red Teaming** and **Offensive Cloud Pentesting** on top of a strong offensive foundation to become a high-value hybrid Red Teamer in 2026. Step-by-step learning path (free + paid), key concepts and tools, hands-on labs, a 12-week action plan, portfolio builders, and certifications that actually matter.

---

## Overview

This roadmap layers two high-demand specializations on an existing offensive foundation (Web/API, exploits, malware dev, endpoint security, reverse engineering + basic AI knowledge):

- **Offensive AI/LLM Red Teaming** — the fastest path to differentiation
- **Offensive Cloud Pentesting** — for volume and modern relevance

The real power is in the **combination**. In 3–4 months you can confidently red team modern AI systems running in cloud environments — a rare and extremely valuable skill set in 2026.

---

## Contents

| File | Description |
|------|-------------|
| `Offensive_AI_Cloud_RedTeaming_Roadmap_2026.pdf` | The full roadmap — phases, resources, tools, YouTube channels, 12-week plan, projects, and certifications |

---

## The Four Phases

| Phase | Timeline | Focus |
|-------|----------|-------|
| **Phase 0 — Foundation** | 1 week | Current skills + basic AI/Cloud concepts |
| **Phase 1 — AI/LLM Offensive** | 4–5 weeks | Prompt injection → agent attacks → advanced red teaming |
| **Phase 2 — Cloud Offensive** | 4–5 weeks | IAM → misconfigs → K8s/serverless → CI/CD attacks |
| **Phase 3 — Integration** | Ongoing | Attack cloud-hosted AI systems + combined red team scenarios |

---

## Must-Master Concepts

**Phase 1 — AI / LLM Red Teaming**
- Prompt injection (direct + indirect) & jailbreaking
- RAG poisoning & data poisoning
- Model extraction & membership inference
- Agent / tool abuse & supply chain attacks on AI pipelines
- Guardrail bypass, multi-turn / conversational attacks
- Adversarial examples for LLMs & vision models

**Phase 2 — Cloud Attack Surfaces**
- IAM — privilege escalation via roles, policies, trust relationships
- Misconfigurations — S3 buckets, security groups, metadata service abuse
- Container & Kubernetes — container escapes, RBAC, pod security
- Serverless — event injection, permission boundaries, supply chain
- CI/CD pipelines — pipeline compromise, secret exfiltration, poisoned builds
- Storage & data services — S3/Blob attacks + snapshot abuse

---

## 12-Week Action Plan

| Week | Focus | Key Activities |
|------|-------|----------------|
| 1–2 | AI Foundations | OWASP LLM Top 10 + Microsoft AI Red Teaming 101 + Lakera Gandalf |
| 3–4 | AI Offensive Core | OffSec LLM Path or COASP. Daily tool practice (Garak, Promptfoo). Break 5+ LLMs |
| 5–6 | Cloud Foundations | CloudGoat + FLAWS labs. IAM deep dive. PwnedLabs. Day Cyberwox videos |
| 7–8 | Cloud Offensive | SANS SEC588 or OffSec Cloud Path. K8s + serverless attacks. CI/CD focus |
| 9–10 | Integration | Deploy LLM on cloud. Full-stack attacks. Chain IAM → LLM access → prompt injection |
| 11–12 | Portfolio + Polish | Document 4–5 full attack chains. Write reports. Update LinkedIn. Apply to roles |

**Daily habit:** 1–2 hours minimum. Watch video → immediate lab practice. Never watch more than 30–40 min without breaking something.

---

## Example Integration Attack Chains

1. Compromise cloud IAM role → access to SageMaker / Azure ML endpoint → extract model or poison training data
2. Find exposed cloud storage with LLM training data → poison dataset → retrain attack
3. Compromise CI/CD pipeline that deploys an LLM app → inject backdoor into model or prompt
4. Serverless function hosting an LLM agent → abuse tool permissions → lateral movement in cloud

---

## Live Project Page

View the full breakdown at: [calm-ay.github.io/offensive-ai-cloud-roadmap](https://calm-ay.github.io/offensive-ai-cloud-roadmap/)

---

## Author

**Rasaq Ayomide**
Offensive Security Engineer | AI Red Teaming · Cloud Security · AppSec · Red Team
- Portfolio: [calm-ay.github.io](https://calm-ay.github.io)
- GitHub: [@Calm-Ay](https://github.com/Calm-Ay)
- Email: ayomiderasq6@gmail.com
