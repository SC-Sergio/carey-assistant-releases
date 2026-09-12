<div align="center">

# Carey Assistant

### Desktop AI assistant for Windows

Local AI · Ollama · Optional cloud AI · Productivity tools · Project workflows

[![Latest Release](https://img.shields.io/github/v/release/SC-Sergio/carey-assistant-releases?display_name=tag&sort=semver&style=for-the-badge&label=Latest%20Release)](https://github.com/SC-Sergio/carey-assistant-releases/releases/latest)
![Platform](https://img.shields.io/badge/Platform-Windows%20x64-0078D4?style=for-the-badge&logo=windows11&logoColor=white)
![Source](https://img.shields.io/badge/Source-Private-6E7681?style=for-the-badge)

[**Download latest release**](https://github.com/SC-Sergio/carey-assistant-releases/releases/latest) · [**View all releases**](https://github.com/SC-Sergio/carey-assistant-releases/releases) · [**Sergio Carey's GitHub profile**](https://github.com/SC-Sergio)

</div>

---

## What is Carey Assistant?

**Carey Assistant** is a Windows desktop assistant focused on practical AI workflows, local model usage and day-to-day productivity.

The project is designed around a **local-first AI experience** with Ollama, while still allowing optional cloud-backed AI when appropriate. Its public releases expose the product and installation artifacts without publishing the private source repository.

This repository is the **official public distribution channel** for Carey Assistant.

## Highlights

- **Local AI with Ollama** — use supported local models directly from the desktop app.
- **Model guidance** — recommendations and installation guidance for local models.
- **Fast model switching** — select the effective local model from the assistant experience.
- **Optional cloud AI** — cloud providers can complement the local workflow; recent releases include optional DeepSeek integration with local fallback.
- **Project-oriented tools** — project exploration and permission-aware workflows are part of the desktop experience.
- **AI provider configuration** — configure local and optional cloud AI paths from the application.
- **Privacy-oriented controls** — recent releases include clearer permission and memory-consent flows.
- **Windows desktop delivery** — distributed as an x64 installer through GitHub Releases.

## Current release

| Item | Status |
|---|---|
| **Latest release** | [`v0.1.19`](https://github.com/SC-Sergio/carey-assistant-releases/releases/tag/v0.1.19) |
| **Platform** | Windows x64 |
| **Distribution** | Manual installer |
| **Source code** | Private |
| **Local AI** | Ollama |
| **Cloud AI** | Optional |

### v0.1.19 focus

The current public release includes improvements around the local-AI workflow, including:

- local-AI phases 1–5;
- local model recommendations;
- quick model selection in chat;
- local model installation guidance;
- smarter effective-model selection;
- clearer chat messaging around the model actually in use;
- optional DeepSeek cloud support with local fallback;
- additional QA and chat-experience fixes.

> **Updater status:** `v0.1.19` is currently distributed as a manual installer. The automatic updater/signing flow is planned to be restored in a future release.

## Installation

1. Open the [latest release](https://github.com/SC-Sergio/carey-assistant-releases/releases/latest).
2. Download the Windows x64 installer attached to the release.
3. Run the installer and follow the Windows installation flow.

For `v0.1.19`, the current installer asset is:

```text
Carey.Assistant_0.1.19_x64-setup.exe
```

> Windows may show additional security prompts for manually distributed installers depending on the release and signing state. Always download Carey Assistant from this repository's official Releases page.

## Local AI workflow

Carey Assistant is built to make local AI practical rather than requiring a cloud connection for every interaction.

A typical local setup is:

```text
Carey Assistant
      │
      ├── Local AI → Ollama → installed local model
      │
      └── Optional cloud AI → configured provider
```

The application can help surface suitable local models, guide installation and keep the active-model state visible in the chat experience.

## Recent release history

### [`v0.1.19`](https://github.com/SC-Sergio/carey-assistant-releases/releases/tag/v0.1.19)

Local-AI workflow expansion, model recommendations, quick model selection, installation guidance, optional DeepSeek cloud fallback and additional QA fixes.

### [`v0.1.18`](https://github.com/SC-Sergio/carey-assistant-releases/releases/tag/v0.1.18)

Major desktop-experience update including the modern assistant landing experience, local-AI chat panel, AI-provider configuration, project explorer, project permissions, memory-consent preview, security improvements and expanded smoke/config testing.

### [`v0.1.17`](https://github.com/SC-Sergio/carey-assistant-releases/releases/tag/v0.1.17)

Stable release focused on security and internal permissions, persistence/state clarity, modernized visual states, briefing/news cards and configuration smoke tests. This release also includes updater metadata and signature artifacts.

For the complete history, see [**GitHub Releases**](https://github.com/SC-Sergio/carey-assistant-releases/releases).

## Release artifacts

Artifacts vary by version. Depending on the release, the public distribution package can include:

| Artifact | Purpose |
|---|---|
| `Carey.Assistant_*_x64-setup.exe` | Windows x64 installer |
| `*.sig` | Updater/signature artifact when available for that release |
| `latest.json` | Updater metadata when available for that release |

Not every release contains every artifact. The assets attached to each GitHub Release are the authoritative source for that version.

## Technology overview

Carey Assistant is a desktop software project built around a modern application stack and AI integrations.

| Area | Technologies / approach |
|---|---|
| Desktop | Tauri |
| Frontend | React · TypeScript |
| Native layer | Rust |
| Local AI | Ollama · local LLMs |
| Cloud AI | Optional provider integrations |
| Distribution | GitHub Releases · Windows x64 installer |

This table describes the product at a high level. Implementation details remain in the private source repository.

## Repository scope

This public repository is intentionally focused on **distribution and product presentation**.

### This repository contains

- official Carey Assistant releases;
- Windows installers;
- public release notes;
- updater metadata and signature artifacts when applicable;
- public-facing product documentation.

### This repository does not contain

- Carey Assistant's private source code;
- private configuration;
- API keys or secrets;
- signing keys;
- internal project documentation.

## Source code

Carey Assistant is developed in a **private source repository**.

Keeping the source private allows this repository to remain a clean public distribution channel while still providing transparent release notes, downloadable installers and a public overview of the product.

## About the project

Carey Assistant is developed by **Sergio Carey**, Software Engineer from Chile, with a focus on backend development, applied AI, automation and useful software products.

- GitHub: [@SC-Sergio](https://github.com/SC-Sergio)
- Portfolio: [carey-ai.vercel.app](https://carey-ai.vercel.app/)
- Releases: [Carey Assistant Releases](https://github.com/SC-Sergio/carey-assistant-releases/releases)

---

<div align="center">

**Carey Assistant** — local AI, desktop productivity and practical automation.

</div>
