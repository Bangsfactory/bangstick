# Bangstick

**Ideas into action.**  
Build apps. Work with AI.

Bangstick is a Windows workspace that brings AI agents, a browser, files, and creative tools together on your computer. Connect local models, external AI services, or CLI agents and work with them in the same environment.

[Website](https://bangstick.space/) · [Download for Windows](https://github.com/Bangsfactory/bangstick/releases/latest) · [Watch the demo](https://www.youtube.com/watch?v=HkWL2XxfNn0)

## One workspace for AI and apps

| Feature | What you can do |
| --- | --- |
| **Your choice of AI** | Connect local LLMs, model APIs, and CLI agents such as Codex and Claude Code. Choose the connection and model that suit your task. |
| **Browser and web tools** | Browse, search, read pages, and work with websites alongside your files and apps. Agents can inspect page content and interact with browser controls. |
| **Built-in creative tools** | Write documents, work with spreadsheets, edit images, and create or edit video and audio in the workspace. |
| **App creation and AppHub** | Build and run apps with AI, preview your work, and find additional apps through AppHub. |
| **Multiple agents** | Configure agents for different tasks and let them exchange requests and results within Bangstick. |
| **History and memory** | Keep conversations and work history in your local workspace, search previous work, and save lasting instructions. |
| **Scheduled work** | Set up future or recurring tasks. Scheduled work runs while the Bangstick host is running. |

Inside Bangstick, agents access workspace tools through the `bangs` command interface, including tool discovery, app inspection, file and history search, and task execution.

## Get started

The current public distribution is **Windows x64**.

1. Open the [latest release](https://github.com/Bangsfactory/bangstick/releases/latest) and download `Bangstick-win-x64-<version>.zip` from **Assets**.
2. Extract the **entire ZIP** to a folder on your computer.
3. Run **`Bangstick.exe` in the top-level extracted folder**. Keep the accompanying files and folders together.
4. Open Settings to configure your AI connection, select a model or CLI agent, and start a conversation or open an app.

For version-specific download details, see the release notes. Each release also provides `SHA256SUMS.txt` for file verification, `SOURCE-DELIVERY.md` for third-party source delivery details, and a corresponding `ThirdPartySources-<id>.zip` archive.

## AI connections and setup

- **Local models:** Use a compatible local model setup. Model files, runtimes, and hardware requirements depend on the model you choose.
- **Model APIs:** Configure the provider connection and any required API credentials. Provider availability, usage limits, and charges follow the provider's terms.
- **CLI agents:** Configure a supported executor such as Codex or Claude Code and complete the CLI's installation and authentication setup.

Available tools and behavior depend on the selected model, connection, installed apps, and permissions. External services use their own network connections; choosing a local model does not make every workspace feature offline.

## Why Bangstick exists

Bangstick grew out of a game developer's attempt to make local AI useful for everyday work. The goal is to keep AI work, files, and tools together on one computer, with a shared interface that agents can use to carry out real tasks.

The project evolved from experiments with hierarchical coding agents and task graphs into a workspace focused on using apps, making things, and continuing work across different AI connections.

## About this repository

This is the official repository for Bangstick's product information, Windows releases, and update notices. It does not contain the proprietary application source code or account and server operations data. Third-party source archives supplied with releases are described in each release's `SOURCE-DELIVERY.md`.

For questions or bug reports, open a [GitHub issue](https://github.com/Bangsfactory/bangstick/issues). Include your Bangstick version, Windows version, steps to reproduce the issue, and relevant screenshots or logs. Remove API keys and other private information before posting.

## License and terms

Bangstick is **proprietary software**. All rights in the original contributions are reserved. Installation and use are governed by the [End User License Agreement (EULA)](EULA.md). Personal and business use are permitted under those terms; unauthorized redistribution, sale, or modification of the proprietary program is not permitted. You may share the official download links.

- [Copyright and proprietary license](LICENSE)
- [End User License Agreement](EULA.md)
- [Third-party license notices](THIRD_PARTY_NOTICES.md)

Rights granted by third-party open-source licenses, applicable law, and GitHub's terms remain unaffected. Apps and content created by users remain the property of the user or the original rights holder.

---

Copyright © 2026 Bangsfactory. All rights reserved in original contributions.  
Made by [Bangsfactory](https://github.com/Bangsfactory)
