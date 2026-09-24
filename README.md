# Awesome-AI-Safety-Firewall

## Top AI Safety Firewall Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on LLM Firewalls, Guardrails, Prompt Injection & Jailbreak Defense, Output Filtering, Policy Enforcement & Runtime AI Safety*  

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **AI Safety Firewalls**. These systems sit between applications and models (or around agents) to inspect prompts and responses, block injections and jailbreaks, enforce content and policy rules, redact sensitive data, and reduce unsafe model behavior at runtime.



**Examples** include Lakera Guard, Protect AI, NVIDIA NeMo Guardrails, HiddenLayer, CalypsoAI, Arthur Shield, Aporia, Fiddler AI, Patronus AI, and Robust Intelligence (the category leaders and adjacent platforms).



**Open-source emphasis**: AI safety firewalls and guardrails have a strong open ecosystem. **NeMo Guardrails**, **LlamaFirewall**, **Guardrails AI**, **LLM Guard**, safety proxies, and red-teaming tools provide practical, self-hosted alternatives. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Lakera Guard](https://www.lakera.ai/)**  

  Runtime LLM security focused on prompt injection and application-level defenses, with practical evaluation and policy controls for production AI apps.



- **[NVIDIA NeMo Guardrails](https://www.nvidia.com/en-us/ai-data-science/)**  

  Programmable guardrails framework (open core with enterprise support paths) for input, dialog, retrieval, execution, and output rails around LLMs and agents.



- **[Protect AI, HiddenLayer](https://protectai.com/)**  

  AI security platforms covering model/supply-chain risk and runtime protection layers that complement prompt- and agent-level firewalls.



- **[CalypsoAI, Arthur Shield, Aporia, Fiddler AI](https://calypsoai.com/)**  

  Platforms for AI application security, observability, and runtime controls—guardrails, monitoring, and policy enforcement for production models.



- **[Patronus AI, Robust Intelligence](https://www.patronus.ai/)**  

  Evaluation and safety-oriented platforms that help test, score, and constrain model behavior, including adversarial and policy checks.



- **[Other commercial AI safety & LLM firewall platforms](https://www.lakera.ai/)**  

  Additional solutions for content filtering, agent safety, and enterprise AI risk management.



## Open-Source GitHub Projects



- **[NVIDIA NeMo Guardrails](https://github.com/NVIDIA/NeMo-Guardrails)**  

  Leading open-source framework for programmable rails (input, dialog, retrieval, execution, output) to control LLM and agent behavior, topical boundaries, and safety policies.



- **[LlamaFirewall (Meta)](https://ai.meta.com/research/publications/llamafirewall-an-open-source-guardrail-system-for-building-secure-ai-agents/)**  

  Open guardrail system for agents: jailbreak/prompt-injection detection, alignment checks on reasoning, and code safety scanning—intended as a final defense layer.



- **[Guardrails AI](https://github.com/guardrails-ai/guardrails)**  

  Open framework for declarative validation and corrective actions on LLM outputs (and inputs), with structured safety and quality checks.



- **[LLM Guard](https://github.com/protectai/llm-guard)**  

  Open toolkit for scanning and sanitizing LLM inputs and outputs—injection, PII, toxicity, secrets, and related filters suitable for proxy-style deployment.



- **[AISafeGuard & runtime safety proxies](https://github.com/akshaymagapu/aisafeguard)**  

  Open safety layer with prompt-injection and jailbreak detection, PII redaction, toxicity filtering, and OpenAI-compatible proxy modes.



- **[Agent / MCP safety firewalls](https://github.com/search?q=AI+agent+firewall+OR+MCP+guard+OR+LLM+firewall+open+source)**  

  Projects that inspect agent tool calls, egress, and MCP traffic for injection, secret leakage, and unsafe actions (e.g. Pipelock-style and HOL Guard–style controls).



- **[Promptfoo, garak & red-teaming](https://github.com/promptfoo/promptfoo)**  

  Open tools for automated security testing, jailbreak evaluation, and CI/CD checks that complement runtime firewalls.



- **[Community injection detectors & moderation models](https://github.com/search?q=prompt+injection+detection+OR+jailbreak+detector)**  

  Classifiers and rule libraries for detecting known injection and jailbreak patterns at the API boundary.



### Additional Strong Open-Source Options



- **Programmable guardrails**: NeMo Guardrails for policy-driven dialog and topic control.

- **Agent-centric defense**: LlamaFirewall and agent/MCP firewalls for tool-use and alignment risks.

- **Scan-and-proxy**: LLM Guard and AISafeGuard for drop-in input/output filtering.

- **Test before enforce**: Promptfoo and garak to measure residual risk.

- **Composable stacks**: Open proxy + rails config + logging for a self-hosted LLM safety firewall.

- Managed threat updates, multi-model coverage, and enterprise policy UX remain commercial strengths.



**Frameworks for building custom systems**:  

**NeMo Guardrails**, **LlamaFirewall**, **Guardrails AI**, and **LLM Guard** are the primary open building blocks for AI safety firewalls.  

Agent-focused open firewalls and red-teaming tools complete a layered approach.  

Commercial platforms (Lakera, Protect AI, HiddenLayer, CalypsoAI, Arthur, Aporia, Fiddler, Patronus, Robust Intelligence, etc.) add scale, managed detectors, and SOC-oriented workflows.  

Many teams run open guardrails in front of self-hosted or API models and adopt commercial AI safety products for broader coverage and operations. Fully open stacks work well when you can own policy design, updates, and monitoring.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- AI safety firewalls reduce risk but do not eliminate prompt injection, jailbreaks, or agent misuse. No single layer is sufficient; combine firewalls with least-privilege tools, human approval for high-impact actions, and continuous evaluation.

- Open-source tools offer transparency and control but require ongoing tuning and ownership. Commercial platforms shift detector updates and support to the vendor. Validate effectiveness against your threat model and use cases before production deployment.



---



**Made for AI security engineers, LLM application developers, and teams shipping safer AI products.**  

Let's expand open AI safety firewalls and guardrails while recognizing the coverage and operational maturity that leading commercial platforms deliver.
