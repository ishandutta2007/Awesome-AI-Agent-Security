# Awesome-AI-Agent-Security

# Top AI Agent Security Platforms Ecosystem
**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Guardrails, Prompt Injection Defense, Memory Poisoning Protection, Runtime Safety & Agent Trustworthiness*
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **AI Agent Security**. These tools protect agents against prompt injection, memory poisoning, tool misuse, data leakage, and other agent-specific threats through guardrails, runtime monitoring, and independent verification.

**Examples** include Lakera, HiddenLayer, Protect AI, Patronus AI, Arthur Shield, Robust Intelligence, CalypsoAI, NVIDIA NeMo Guardrails, Fiddler AI, and Aporia (the category leaders).

**Open-source emphasis**: Agent security has strong open foundations. **Agent Memory Guard (OWASP)**, **NVIDIA NeMo Guardrails**, **Guardrails AI**, **LlamaFirewall**, and related projects enable self-hosted protection against memory poisoning, injection, and unsafe outputs. This section is heavily expanded.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms
- **[Lakera](https://www.lakera.ai/)**  
  AI security platform focused on prompt injection defense, content filtering, and runtime guardrails for LLM applications and agents.

- **[HiddenLayer](https://hiddenlayer.com/)**  
  AI security and model protection platform covering adversarial threats, model integrity, and runtime monitoring for AI systems.

- **[Protect AI](https://protectai.com/)**  
  Platform for securing the AI/ML supply chain and runtime, including model scanning, vulnerability detection, and agent-related risks.

- **[Patronus AI](https://www.patronus.ai/)**  
  Evaluation and safety platform that helps detect hallucinations, policy violations, and unsafe agent behaviors.

- **[Arthur Shield / Arthur AI](https://www.arthur.ai/)**  
  Monitoring and governance platform providing performance, fairness, and safety controls for ML and generative AI systems.

- **[Robust Intelligence](https://www.robustintelligence.com/)**  
  AI security and validation platform focused on testing models and applications against adversarial and robustness threats.

- **[CalypsoAI](https://calypsoai.com/)**  
  Enterprise AI security platform for controlling, monitoring, and securing generative AI and agent deployments.

- **[NVIDIA NeMo Guardrails (Enterprise / NIM offerings)](https://www.nvidia.com/en-us/ai-data-science/products/nemo/)**  
  Commercial and enterprise support around the open-source NeMo Guardrails framework for programmable safety rails.

- **[Fiddler AI](https://www.fiddler.ai/)**  
  Model performance and responsible AI platform with monitoring, explainability, and governance features relevant to agent safety.

- **[Aporia](https://www.aporia.com/)**  
  ML observability and guardrails platform that helps detect drift, anomalies, and unsafe outputs in production AI systems.

## Open-Source GitHub Projects
- **[Agent Memory Guard (OWASP)](https://github.com/OWASP/www-project-agent-memory-guard)**  
  OWASP incubator project that detects and blocks memory poisoning attacks in AI agent memory stores — runtime defense that screens memory reads/writes with detectors and declarative policies (also available as `agent-memory-guard` on PyPI).

- **[NVIDIA NeMo Guardrails](https://github.com/NVIDIA/NeMo-Guardrails)**  
  Open-source toolkit for adding programmable guardrails (input, dialog, retrieval, execution, output) to LLM applications and agents.

- **[Guardrails AI](https://github.com/guardrails-ai/guardrails)**  
  Open-source framework for validating, structuring, and applying safety rails to LLM and agent outputs.

- **[LlamaFirewall](https://github.com/meta-llama/PurpleLlama)** (and related Meta safety tools)  
  Open-source scanners and safety components for auditing agent reasoning and defending against injection and policy violations.

- **[mguard](https://github.com/mguard-ai/mguard)**  
  Memory defense library aimed at stopping memory-poisoning style attacks (e.g., MINJA, AgentPoison) before they reach agent context.

- **[promptfoo](https://github.com/promptfoo/promptfoo)**  
  Open-source evaluation and red-teaming tool frequently used to test agents and prompts for injection and safety failures.

- **[iFixAi](https://github.com/ifixai-ai/iFixAi)**  
  Independent auditing tool for AI agents that checks misalignment, authority boundaries, and behavioral compliance.

- **[Garak](https://github.com/NVIDIA/garak)**  
  Open-source LLM vulnerability scanner used to probe models and agent setups for known attack classes.

- **[Rebuff / related injection detectors](https://github.com/protectai/rebuff)**  
  Open-source and community tools focused on detecting and mitigating prompt injection attempts.

- **[Documentation and OWASP agent security resources](https://owasp.org/www-project-agent-memory-guard/)**  
  Official guides, benchmarks, and contribution paths for hardening agent memory and runtime behavior with open tools.

### Additional Strong Open-Source Options
- Protecting persistent memory with **Agent Memory Guard** (OWASP) or **mguard**.
- Adding programmable conversational and tool-execution rails with **NeMo Guardrails**.
- Validating outputs and schemas with **Guardrails AI**.
- Red-teaming agents via **promptfoo**, **Garak**, or **iFixAi**.
- Combining open guardrails with self-hosted observability (Langfuse, Phoenix) for full visibility.
- Accepting that commercial platforms (Lakera, HiddenLayer, Protect AI, CalypsoAI, etc.) still lead in managed detection, threat intelligence, and enterprise SLAs.

**Frameworks for building custom systems**: Insert **Agent Memory Guard** between agents and memory stores → wrap LLM/tool calls with **NeMo Guardrails** or **Guardrails AI** → continuously test with **promptfoo** / **Garak**. Suitable for teams that need transparent, auditable security controls. Many organizations still adopt commercial agent security platforms for operational support and threat feeds.

## How to Contribute
1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer
- This is a **community-curated** list — not exhaustive and not an endorsement.
- Agent security tools reduce risk but do not eliminate it. Combine automated defenses with least-privilege tool access, human oversight, and regular red-teaming. This list is not security, compliance, or legal advice.

---
**Made for AI security engineers, red teams, and trustworthy-agent builders.**
Let's keep AI agents safer, more transparent, and as open as practical.
