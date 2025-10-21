# ChatAI

✨ A lightweight, fast, and privacy-first AI Assistant — built and maintained by **Afnan Sharif**, supporting GPT-4, Claude, DeepSeek, and Gemini Pro.

---

## Overview

**NextChat** is a modern, secure, and easy-to-deploy AI assistant designed for personal and enterprise use.  
It integrates multiple AI models under a unified chat interface with support for local, cloud, and hybrid deployments.

---

## Enterprise Edition

NextChat offers a complete enterprise-ready solution with:

- **Custom Branding:** UI/UX tailored to your company’s visual identity.  
- **Centralized Resource Management:** Manage multiple AI models and configurations easily.  
- **Access Control:** Fine-grained permissions for users, data, and resources.  
- **Knowledge Base Integration:** Combine your private data with AI models for smarter insights.  
- **Security Auditing:** Track all chat activity and ensure compliance with company policies.  
- **Private Cloud Deployment:** Deploy securely in your own environment.  
- **Continuous Updates:** Stay ahead with ongoing improvements in multimodal AI.

For enterprise inquiries, please contact **business@nextchat.dev**.

---

## Features

- One-click deployment on Vercel  
- Lightweight cross-platform desktop client (~5MB)  
- Supports self-hosted or local models (RWKV, LocalAI, etc.)  
- Privacy-first design — all chat data is stored locally in your browser  
- Markdown rendering (LaTeX, Mermaid, syntax highlighting)  
- Fast loading speed (~100KB first screen)  
- Responsive interface with dark mode and PWA support  
- Streaming responses  
- Custom prompt templates for reusable chat setups  
- Integration with community prompt libraries  
- Automatic chat compression for long sessions  
- Multilingual interface support

---

## Roadmap

- ✅ Custom system and user prompts  
- ✅ Prompt templates for chat initialization  
- ✅ Shareable conversation exports  
- ✅ Desktop app for Windows, macOS, and Linux  
- ✅ Plugin support (search, calculator, APIs)  
- ✅ Realtime chat support  
- ⏳ Local knowledge base (in development)

---

## What’s New

- **v2.15.8** — Added realtime chat support  
- **v2.15.4** — Enhanced API security using Tauri fetch  
- **v2.15.0** — Plugin system released  
- **v2.14.0** — Artifact and SD model integration  
- **v2.10.1** — Added Gemini Pro model  
- **v2.9.11** — Azure endpoint support  
- **v2.8** — Released unified cross-platform client  
- **v2.7** — Added conversation sharing  
- **v2.0** — Introduced prompt templates

---

## Getting Started

1. Get your [OpenAI API Key](https://platform.openai.com/account/api-keys).  
2. Deploy on Vercel:  
   [![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/afnansharif/NextChat&env=OPENAI_API_KEY&env=CODE&project-name=nextchat&repository-name=NextChat)  
3. Set your access `CODE` and start chatting instantly.

---

## Environment Variables

### Required
- `OPENAI_API_KEY` — Your OpenAI API key (supports multiple keys separated by commas)

### Optional
- `CODE` — Comma-separated list of access passwords  
- `BASE_URL` — Custom API endpoint  
- `ENABLE_MCP` — Enable MCP protocol support  
- `DISABLE_GPT4` — Disable GPT-4 for users  
- `CUSTOM_MODELS` — Add, remove, or rename model options  
- `DEFAULT_MODEL` — Set default model  
- `HIDE_USER_API_KEY` — Hide user API key input field  
- `ENABLE_BALANCE_QUERY` — Allow users to check API balance  

---

## Local Development

```bash
# 1. Install Node.js (>= 18) and Yarn
# 2. Create a .env.local file
OPENAI_API_KEY=your_api_key_here
# 3. Run the development server
yarn install
yarn dev
