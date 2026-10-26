# 🎙️ Voice Agent Launchpad

**One front door to the scattered voice-agent samples for Teams Phone Extensibility (TPE) and custom voice agents.**

Useful voice samples live across many personal and organization GitHub accounts. This page curates them in one place so partners and customers can find a strong starting point quickly. Nothing is copied here: every entry links to its externally maintained source repository.

> [!IMPORTANT]
> This is a curated index, not an official Microsoft catalog. Inclusion does not imply endorsement, production readiness, support, or license approval. Review each source repository's license, security posture, and maintenance status before you use it.

**Jump to:** [Start here](#-start-here) · [Teams Phone Extensibility](#-teams-phone-extensibility-tpe) · [Voice Live and Foundry voice agents](#-voice-live-and-foundry-voice-agents) · [Templates and scenario demos](#-templates-and-scenario-demos) · [How to read this page](#-how-to-read-this-page) · [Suggest a sample](#-suggest-a-sample)

---

## ⭐ Start here

Not sure where to begin? Pick the row that matches your goal.

| I want to… | Start with | Why |
| --- | --- | --- |
| Browse many TPE and custom voice scenarios | [voice-ai-template-gallery](https://github.com/anujb-msft/voice-ai-template-gallery) → [`docs/templates`](https://github.com/anujb-msft/voice-ai-template-gallery/tree/main/docs/templates) | 11 scenarios with guides, code, and presenter assets |
| Understand a TPE contact-center architecture | [agentic-ai-contact-center](https://github.com/colincmac/agentic-ai-contact-center) → [`docs/architecture`](https://github.com/colincmac/agentic-ai-contact-center/tree/main/docs/architecture) | End-to-end reference architecture plus a [TPE onboarding guide](https://github.com/colincmac/agentic-ai-contact-center/blob/main/docs/runbooks/teams-configuration/tpe-onboarding-guide.md) |
| Build a phone or browser voice agent on Voice Live | [call-center-voice-agent-accelerator](https://github.com/Azure-Samples/call-center-voice-agent-accelerator) | Voice Live reference solution with browser and telephony adapters |

---

## 📞 Teams Phone Extensibility (TPE)

Samples that work **directly** with Teams Phone Extensibility.

> [!WARNING]
> Some TPE components below depend on Azure Communication Services (ACS) for call handling or resource-account authorization. Check each repository's current dependencies before you build on it.

| Repository | What it is | Owner | Created | Last commit | License |
| --- | --- | --- | --- | --- | --- |
| ⭐ [agentic-ai-contact-center](https://github.com/colincmac/agentic-ai-contact-center) | TPE contact-center reference architecture with [architecture docs](https://github.com/colincmac/agentic-ai-contact-center/tree/main/docs/architecture) and a [TPE onboarding guide](https://github.com/colincmac/agentic-ai-contact-center/blob/main/docs/runbooks/teams-configuration/tpe-onboarding-guide.md). Uses ACS dependencies. | [colincmac](https://github.com/colincmac) | 2026-08-21 | 2026-09-17 | MIT |
| ⭐ [voice-ai-template-gallery](https://github.com/anujb-msft/voice-ai-template-gallery) | Gallery of 11 TPE and custom voice scenarios. See [Templates and scenario demos](#-templates-and-scenario-demos). Demo-grade. | [anujb-msft](https://github.com/anujb-msft) | 2026-09-02 | 2026-10-20 | MIT |
| [tpcli](https://github.com/anujb-msft/tpcli) | CLI that connects TPE with Voice Live. Early implementation; not production-ready. | [anujb-msft](https://github.com/anujb-msft) | 2026-09-21 | 2026-09-21 | [None detected](https://github.com/anujb-msft/tpcli) |

### Supporting TPE tools

Narrow building blocks, not complete AI voice agents.

| Repository | What it is | Owner | Created | Last commit | License |
| --- | --- | --- | --- | --- | --- |
| [SimpleAcsCallBot](https://github.com/LucaVitali/SimpleAcsCallBot) | Minimal demo that answers incoming Teams calls through TPE using ACS. No complete AI agent. Default branch: `master`. | [LucaVitali](https://github.com/LucaVitali) | 2025-11-15 | 2025-11-22 | [None detected](https://github.com/LucaVitali/SimpleAcsCallBot) |
| [ACS-TPEResourceAccountAuthManager](https://github.com/RasoliDavide/ACS-TPEResourceAccountAuthManager) | Tool for TPE resource-account authorization. Not an agent demo. | [RasoliDavide](https://github.com/RasoliDavide) | 2025-11-17 | 2025-11-17 | [None detected](https://github.com/RasoliDavide/ACS-TPEResourceAccountAuthManager) |

> [!NOTE]
> **Teams Phone Agent (TPA):** no public TPA implementation repository has been verified yet, so none is listed. The general voice samples below are **not** TPA samples.

---

## 🔊 Voice Live and Foundry voice agents

General voice-agent samples. They are not TPE-specific; use them for voice pipelines, architecture, and agent patterns.

### Reference solutions

| Repository | What it is | Owner | Created | Last commit | License |
| --- | --- | --- | --- | --- | --- |
| ⭐ [call-center-voice-agent-accelerator](https://github.com/Azure-Samples/call-center-voice-agent-accelerator) | Voice Live reference solution with browser and multiple telephony adapters. | [Azure-Samples](https://github.com/Azure-Samples) | 2025-07-22 | 2026-09-30 | MIT |
| [art-voice-agent-accelerator](https://github.com/Azure-Samples/art-voice-agent-accelerator) | Voice Live and STT → LLM → TTS pipelines, with architecture and orchestration guidance. Includes ACS components. | [Azure-Samples](https://github.com/Azure-Samples) | 2025-09-04 | 2026-09-09 | MIT |

### Quickstarts and SDK samples

For broad catalogs, links go straight to the voice-specific folders.

| Repository | Voice-specific entry points | Owner | Created | Last commit | License |
| --- | --- | --- | --- | --- | --- |
| [voicelive-samples](https://github.com/microsoft-foundry/voicelive-samples) | Voice Live quickstarts, function calling, MCP, and Foundry: [`python`](https://github.com/microsoft-foundry/voicelive-samples/tree/main/python) · [`csharp`](https://github.com/microsoft-foundry/voicelive-samples/tree/main/csharp) | [microsoft-foundry](https://github.com/microsoft-foundry) | 2025-11-07 | 2026-10-22 | [See repository](https://github.com/microsoft-foundry/voicelive-samples) |
| [foundry-samples](https://github.com/microsoft-foundry/foundry-samples) | Voice folders only: [`python/voice-agents`](https://github.com/microsoft-foundry/foundry-samples/tree/main/samples/python/voice-agents) · [`javascript/.../browser-voice-console`](https://github.com/microsoft-foundry/foundry-samples/tree/main/samples/javascript/voice-agents/browser-voice-console) · [`csharp/VoiceAgents`](https://github.com/microsoft-foundry/foundry-samples/tree/main/samples/csharp/VoiceAgents) | [microsoft-foundry](https://github.com/microsoft-foundry) | 2025-04-22 | 2026-10-26 | MIT |
| [voice-agent](https://github.com/microsoft/voice-agent) | Foundry Voice Agent docs, videos, and samples, including [`samples/voice_live_to_voice_agent`](https://github.com/microsoft/voice-agent/tree/main/samples/voice_live_to_voice_agent). Not packaged TPA source. | [microsoft](https://github.com/microsoft) | 2026-10-03 | 2026-10-26 | [See repository](https://github.com/microsoft/voice-agent) |

---

## 🧩 Templates and scenario demos

| Repository | What it is | Owner | Created | Last commit | License |
| --- | --- | --- | --- | --- | --- |
| ⭐ [voice-ai-template-gallery](https://github.com/anujb-msft/voice-ai-template-gallery) | 11 TPE and custom voice scenarios; [`docs/templates`](https://github.com/anujb-msft/voice-ai-template-gallery/tree/main/docs/templates) holds guides, code, and presenter assets. Demo-grade. | [anujb-msft](https://github.com/anujb-msft) | 2026-09-02 | 2026-10-20 | MIT |
| [voice-first-sme-agent-template](https://github.com/Azure-Samples/voice-first-sme-agent-template) | React and FastAPI voice template with deployment scaffolding and optional RAG. No verified TPE or TPA support. | [Azure-Samples](https://github.com/Azure-Samples) | 2026-06-11 | 2026-06-11 | MIT |
| [voicelive-webapp](https://github.com/Azure-Samples/voicelive-webapp) | WebRTC voice and avatar web app. Its [`teams-meeting-delegate`](https://github.com/Azure-Samples/voicelive-webapp/tree/main/samples/teams-meeting-delegate) sample targets Teams **meetings**, not TPE or TPA. | [Azure-Samples](https://github.com/Azure-Samples) | 2025-11-03 | 2026-09-18 | [None detected](https://github.com/Azure-Samples/voicelive-webapp) |
| [voicelive-api-salescoach](https://github.com/Azure-Samples/voicelive-api-salescoach) | Voice-based customer simulations for sales training and feedback. | [Azure-Samples](https://github.com/Azure-Samples) | 2025-08-22 | 2026-09-21 | MIT |
| [voice-live-gradio](https://github.com/Azure-Samples/voice-live-gradio) | Side-by-side demos comparing realtime, Voice Live, and Foundry voice. | [Azure-Samples](https://github.com/Azure-Samples) | 2025-08-12 | 2026-05-28 | MIT |

---

## 📖 How to read this page

- **⭐ Strong starting point:** a curated recommendation for first exploration, not a quality or support guarantee.
- **Owner:** the GitHub account or organization that hosts the repository. It is **not** a verified original author. No individual authorship has been verified for these entries, and latest committers are never treated as authors.
- **Created:** the date the GitHub repository was created (UTC). It is not a verified first-publication date.
- **Last commit:** the latest commit on the default branch (UTC). Dates apply to the whole repository, not to individual subfolders.
- **License:** as detected on GitHub. "None detected" or "See repository" means you must check the source yourself before reuse.
- **TPE vs. general voice:** only the [TPE section](#-teams-phone-extensibility-tpe) lists samples that work directly with Teams Phone Extensibility.

_Metadata last verified: 2026-10-26._

---

## ➕ Suggest a sample

Know a public voice sample that belongs here? See [CONTRIBUTING.md](CONTRIBUTING.md) for what qualifies and what details to include.
