<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/nolgia-logo-white.png">
  <source media="(prefers-color-scheme: light)" srcset="./assets/nolgia-logo-black.png">
  <img alt="NOLGIA" src="./assets/nolgia-logo-black.png" width="360">
</picture>

### The production layer for AI creative

Image, video and audio generation through one app, API, CLI and MCP server.

[![Website](https://img.shields.io/badge/nolgia.ai-111111?style=for-the-badge&logo=googlechrome&logoColor=white)](https://nolgia.ai)
[![Docs](https://img.shields.io/badge/docs-docs.nolgia.ai-ff6a13?style=for-the-badge&logo=readthedocs&logoColor=white)](https://docs.nolgia.ai)
[![npm](https://img.shields.io/npm/v/@nolgia/cli?style=for-the-badge&logo=npm&label=%40nolgia%2Fcli&color=cb3837)](https://www.npmjs.com/package/@nolgia/cli)
[![Release](https://img.shields.io/github/v/release/nolgiainc/nolgia-cli?style=for-the-badge&logo=github&label=cli&color=24292f)](https://github.com/nolgiainc/nolgia-cli/releases)

[![X](https://img.shields.io/badge/@nolgiaai-000000?style=flat-square&logo=x&logoColor=white)](https://x.com/nolgiaai)
[![Instagram](https://img.shields.io/badge/@nolgia.ai-E4405F?style=flat-square&logo=instagram&logoColor=white)](https://instagram.com/nolgia.ai)
[![TikTok](https://img.shields.io/badge/@nolgia.ai-000000?style=flat-square&logo=tiktok&logoColor=white)](https://tiktok.com/@nolgia.ai)

</div>

---

## What we build

NOLGIA brings the best image, video and audio models into one place, with the tools to turn single generations into finished work.

| Product | What it does |
|---|---|
| 🎬 **Create** | Text, images and your own footage into video, images, voiceover, music and sound, on the leading models, with credits priced per generation. |
| ✂️ **Studio** | A timeline editor for assembling clips, audio and overlays into a finished piece, ready to export. |
| 🧩 **Presets** | Guided recipes for ads, product shots, logo reveals, music videos and more. Answer a few questions, get a production. |
| 🔁 **Miroge** | Remake a clip you already have: transfer its motion to your own photos, swap a person or product, or move the scene to a new world. |
| 🎥 **Multicam** | Turn one steady take into every camera angle you pick, in sync over your original sound, with a free highlight edit. |
| 🤖 **NOLGIA Agent** | An AI producer that plans, generates and edits with you, on the reasoning model of your choice. |

## For developers

Everything in the app is available through the API, so your code and your agents can create too.

```bash
# CLI (macOS, Linux, Windows)
brew tap nolgiainc/nolgia && brew install nolgia
# or
npm install -g @nolgia/cli
# or
curl -fsSL https://raw.githubusercontent.com/nolgiainc/nolgia-cli/main/install.sh | bash

nolgia auth login
nolgia models list
```

**MCP server** for Claude, Cursor, Codex and any MCP client:

```
https://mcp.nolgia.ai/mcp
```

**Agent skills** that teach coding agents to generate media with NOLGIA:

```bash
npx skills add nolgiainc/nolgia-skills
```

## Open source

| Repository | What it is |
|---|---|
| [**nolgia-cli**](https://github.com/nolgiainc/nolgia-cli) | The `nolgia` command line tool for images, video and audio |
| [**homebrew-nolgia**](https://github.com/nolgiainc/homebrew-nolgia) | Homebrew tap for the CLI |
| [**nolgia-skills**](https://github.com/nolgiainc/nolgia-skills) | Skills for Claude Code, Cursor, Codex and other agents |
| [**cursor-plugin**](https://github.com/nolgiainc/cursor-plugin) | A `/nolgia` command for Cursor over the MCP server |
| [**nolgia-plugins**](https://github.com/nolgiainc/nolgia-plugins) | Connect Blender and other creative apps so your agent can work in them |

## Security

Found a vulnerability? Please report it privately to **security@nolgia.ai**. See [nolgia.ai/security](https://nolgia.ai/security) for how we protect your work and our disclosure policy.

## Get in touch

[contact@nolgia.ai](mailto:contact@nolgia.ai) · [nolgia.ai](https://nolgia.ai) · [Pricing](https://nolgia.ai/pricing) · [Docs](https://docs.nolgia.ai)

<div align="center"><sub>© NOLGIA Inc.</sub></div>
