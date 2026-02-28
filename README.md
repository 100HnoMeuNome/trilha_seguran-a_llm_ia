Aqui está a trilha completa formatada em **Markdown**, pronta para ser copiada e colada no arquivo `README.md` do seu repositório no GitHub.

---

# 🛡️ Trilha de Estudos: Segurança em IA & LLMs (Edição 2025/2026)

Este repositório contém uma trilha de estudos estruturada para profissionais de segurança que desejam se especializar em IA Generativa, cobrindo desde fundamentos até arquiteturas avançadas de agentes, o protocolo MCP e as ameaças mais recentes do cenário "Agentic Security".

---

## 📘 Módulo 1: Fundamentos de AI & LLMs (O Motor)
*Objetivo: Entender como os modelos funcionam, desde os pesos até a operação ofensiva autônoma.*

- **Conceitos:** Transformers, Foundation Models (Proprietários vs. Open-Weights), e a transição para a **Ofensiva Agentica**.
- **Recursos:**
    - [📺] [Intro to LLMs (Andrej Karpathy)](https://www.youtube.com/watch?v=zjkBMFhNj_g)
    - [📺] [Visual intro to Transformers (3Blue1Brown)](https://www.youtube.com/watch?v=wjZofJX0v4M)
    - [📖] [OpenAI Models Documentation](https://platform.openai.com/docs/models)
    - [📖] [Anthropic Models Overview](https://docs.anthropic.com/en/docs/models-overview)
    - [📊] [State of AI Report](https://www.stateof.ai/)
    - [📰] [The tools for autonomous offensive operations are shipping (Agentic Security)](https://agenticsecurity.substack.com/p/the-agentic-security-newsletter-week-77e)

---

## 📘 Módulo 2: Arquiteturas de Aplicação (RAG, Fine-tuning, Agents & MCP)
*Objetivo: Entender como os dados de negócio são expostos e como agentes interagem com o mundo real via MCP.*

- **Conceitos:** RAG, LoRA, Orquestração com LangGraph, Protocolo MCP e **AI BOM** (AI Bill of Materials).
- **Recursos:**
    - [🎓] [Finetuning LLMs (DeepLearning.ai)](https://www.deeplearning.ai/short-courses/finetuning-large-language-models/)
    - [📺] [LoRA Explained](https://www.youtube.com/watch?v=PXWYUTMt-AU)
    - [🎓] [Advanced RAG (DeepLearning.ai)](https://www.deeplearning.ai/short-courses/building-evaluating-advanced-rag/)
    - [📄] [Model Context Protocol (MCP) Official Guide](https://modelcontextprotocol.io/)
    - [🎓] [AI Agents in LangGraph (DeepLearning.ai)](https://www.deeplearning.ai/short-courses/ai-agents-in-langgraph/)
    - [📰] [AI BOM Concept & Visibility (Agentic Security)](https://agenticsecurity.substack.com/p/the-agentic-security-newsletter-week-77e)

---

## 🔴 Módulo 3: Segurança Ofensiva (Injeção, Jailbreaks e Ataques de Camada Profunda)
*Objetivo: Domínio completo dos vetores de ataque, desde o prompt simples até a escalada de privilégios em agentes.*

- **Conceitos:** Direct/Indirect Prompt Injection, Jailbreaks (DAN), **Excessive Agency**, **Confused Deputy no MCP**, Data Poisoning e Model Extraction.
- **Recursos:**
    - [🌐] [Simon Willison: Prompt Injection Series](https://simonwillison.net/series/prompt-injection/)
    - [📺] [Advanced Prompt Injection (Johann Rehberger)](https://www.youtube.com/watch?v=OhxAdrfHVs8)
    - [💻] [Jailbreak Chat (Database de prompts)](https://www.jailbreakchat.com/)
    - [📄] [Excessive Agency: The safety risks of autonomous AI agents](https://arxiv.org/abs/2401.05566)
    - [🛠️] [LLM-Attacks (GitHub)](https://github.com/llm-attacks/llm-attacks)
    - [📰] [EchoLeak & OpenClaw: Data exfiltration via Agents (Agentic Security)](https://agenticsecurity.substack.com/p/the-agentic-security-newsletter-week-77e)

---

## 🛡️ Módulo 4: Mitigação, Correção e Hardening (Defesa Prática)
*Objetivo: Implementar "escudos" semânticos, gerir identidades não-humanas e proteger servidores MCP.*

- **Conceitos:** Validação de Input/Output, detecção de PII, **NHI (Non-Human Identity)** e Agent Behavior Analytics.
- **Recursos:**
    - [🛠️] [LLM-Guard (Scanner de Payloads)](https://github.com/protectai/llm-guard)
    - [🛠️] [Microsoft Presidio (PII Protection)](https://github.com/microsoft/presidio)
    - [🛠️] [NVIDIA NeMo Guardrails](https://github.com/NVIDIA/NeMo-Guardrails)
    - [🎓] [Red Teaming LLM Applications (DeepLearning.ai)](https://www.deeplearning.ai/short-courses/red-teaming-llm-applications/)
    - [📰] [Agent Behavior Analytics & SOC (Agentic Security)](https://agenticsecurity.substack.com/p/the-agentic-security-newsletter-week-77e)

---

## ⚖️ Módulo 5: Frameworks de Governança e Supply Chain
*Objetivo: Usar os padrões globais para auditar sistemas de IA e gerir riscos de terceiros.*

- **Conceitos:** OWASP Top 10 for LLMs 2025, **OWASP Top 10 for Agentic Applications**, MITRE ATLAS e Supply Chain Security.
- **Recursos:**
    - [📑] [OWASP Top 10 for LLM Applications v2.0](https://genai.owasp.org/)
    - [📑] [OWASP Top 10 for Agentic Applications (Analysis)](https://agenticsecurity.substack.com/p/owasp-top-10-for-agentic-applications)
    - [📑] [MITRE ATLAS Matrix](https://atlas.mitre.org/)
    - [📖] [HuggingFace Security Guide](https://huggingface.co/docs/hub/security)
    - [🏗️] [SLSA (Supply-chain Levels for Software Artifacts)](https://slsa.dev/)

---

## 🏢 Módulo 6: Estudos de Fabricantes e Laboratórios Práticos (Hands-on)
*Objetivo: Aplicar o conhecimento em ambientes de simulação e estudar implementações reais.*

- **Estudos de Caso (Whitepapers):**
    - [Google] [SAIF (Secure AI Framework)](https://safety.google/cybersecurity-advancements/saif/)
    - [Microsoft] [AI Red Teaming Guide](https://www.microsoft.com/en-us/security/blog/ai-red-team/)
    - [Anthropic] [Responsible Scaling Policy](https://www.anthropic.com/news/anthropic-responsible-scaling-policy)
    - [Sophos/Cisco] [Agentic SOC Frameworks](https://agenticsecurity.substack.com/p/the-agentic-security-newsletter-week-77e)

- **Laboratórios Práticos:**
    - [🎮] [Gandalf (Lakera)](https://gandalf.lakera.ai/) - Desafio de Injeção de Prompt.
    - [🛠️] [Garak](https://github.com/leondz/garak) - Scanner de vulnerabilidades (O "Nmap" dos LLMs).
    - [🛠️] [PyRIT (Microsoft)](https://github.com/Azure/PyRIT) - Automação de Red Teaming para IA.
    - [🏗️] [RedAiRange](https://github.com/ErdemOzgen/RedAiRange) - Laboratório completo para prática de ataques.
    - [🏗️] [AgentDojo](https://github.com/approximatelabs/agentdojo) - Segurança para Agentes Autônomos.

---

## 🔔 Atualização Contínua
IA é uma área que muda semanalmente. Para se manter atualizado com novos exploits e defesas, acompanhe a newsletter:
- [Agentic Security Substack](https://agenticsecurity.substack.com/)
