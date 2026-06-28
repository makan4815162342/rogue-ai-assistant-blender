<img width="1664" height="928" alt="1782524481" src="https://github.com/user-attachments/assets/7fd0c5f1-2298-41cf-88dd-b2061039769a" />


# 🤖 Rogue AI Assistant + MCP for Blender

> AI-powered assistant + MCP server for Blender. Talk to your scene, let AI build it.

<img width="2560" height="1080" alt="Desktop Screenshot 2026 06 27 - 03 07 53 32" src="https://github.com/user-attachments/assets/b7b7835b-8181-47cc-9abd-ed652c25cd9c" />


## What is this?

Rogue AI Assistant is a Blender add-on that brings AI directly into your 3D workflow. Chat with an AI assistant inside Blender's sidebar — and it can actually *modify your scene*. No copy-pasting code, no switching windows. Just talk.

It also runs an **MCP (Model Context Protocol) server**, letting external AI tools like Claude, Cursor, or VS Code connect to and control Blender remotely.

### 🔒 Runs 100% Locally — Your Data Stays on Your Machine

No cloud uploads, no data leaving your computer. The AI runs on **your** hardware:
- **LM Studio (FREE)** — Run AI models locally, no API key, no internet required
- **OpenCode Zen** — Free models (DeepSeek V4 Flash), API key required
- Or use cloud providers (OpenAI, Claude, Gemini, etc.)

<img width="2560" height="1080" alt="Desktop Screenshot 2026 06 24 - 03 22 18 30" src="https://github.com/user-attachments/assets/88849647-6b96-4f51-8a56-72f1002b0740" />

<img width="2560" height="1080" alt="Desktop Screenshot 2026 06 20 - 08 18 35 26" src="https://github.com/user-attachments/assets/a9c02feb-90bf-49f3-951d-d50d50c8e1af" />


## ✨ Features

### 🗣️ AI Chat Panel
- Chat directly inside Blender's 3D viewport sidebar
- Streaming responses — watch the AI think in real-time
- Auto-execute AI-generated code or review it first
- Build mode (full control) and Plan mode (analysis only)
- Session management — start new chats, switch between them

### 🔌 MCP Server
- Start/stop MCP server from the sidebar
- Lets Claude, Cursor, VS Code, and other AI tools control Blender
- Works locally or via tunnel (ngrok/localtunnel) for remote access
- 7 tools exposed: execute code, scene summary, selection info, run operators, object info, list addons, scene inspection

<img width="2523" height="980" alt="Desktop Screenshot 2026 06 28 - 01 26 04 97" src="https://github.com/user-attachments/assets/df89dd86-01f5-47f2-bd42-bcd4ab2d811a" />


### 🌐 Multi-Provider Support
Works with almost any OpenAI-compatible API:

| Provider | Notes |
|----------|-------|
| **LM Studio (Recommended)** | Run models locally — FREE, no API key, no data leaves your machine |
| **Ollama** | Cloud |
| **OpenCode Zen** | Free models (DeepSeek V4 Flash), API key required |
| **OpenAI** | GPT-4o, o3, etc. |
| **Anthropic Claude** | Sonnet 4, etc. |
| **Google Gemini** | 2.5 Flash |
| **OpenRouter** | Access to hundreds of models |
| **Groq** | Fast inference |
| **Custom** | Any OpenAI-compatible endpoint |

### 🔧 Full Blender API Access
The AI can do **everything** in Blender:
- **Modeling:** Meshes, curves, NURBS, text, metaballs, grease pencil
- **Materials:** Principled BSDF, node groups, textures, UV mapping
- **Geometry Nodes:** Add/connect/remove any node, custom groups
- **Modifiers:** Subdivision, mirror, array, boolean, solidify, bevel, and more
- **Animation:** Keyframes, NLA, drivers, constraints, physics
- **Rigging:** Armatures, bones, IK/FK, shape keys
- **Rendering:** Cycles/Eevee settings, lights, camera
- **Import/Export:** FBX, OBJ, glTF 2.0, USD, Alembic, STL

<img width="2560" height="1080" alt="Desktop Screenshot 2026 06 24 - 07 45 06 32" src="https://github.com/user-attachments/assets/e077c3fe-c89e-4340-8920-6741dfbed3a2" />

<img width="2560" height="1080" alt="Desktop Screenshot 2026 06 18 - 04 09 20 35" src="https://github.com/user-attachments/assets/8f3da140-7907-4604-be3d-bf3d62111789" />


### 🛡️ Other Features
- **100% local option** — LM Studio, no internet needed
- Proxy support for restricted networks
- SSL certificate toggle
- Reasoning effort control (low → max)
- Custom system prompts
- JSONL logging with export
- Session persistence across Blender restarts

## ⚡ Quick Start

1. Download from [itch.io](https://makan-ansari.itch.io/rogue-ai-assistant-mcp)
2. In Blender: Edit → Preferences → Add-ons → Install → select the .zip
3. Enable "Rogue AI Assistant + MCP"
4. Open sidebar: View3D → Sidebar → Rogue AI Assistant
5. Click Settings tab → pick a provider
   - **Local (recommended):** Start LM Studio, load any model, pick "LM Studio" provider
   - **Free models:** OpenCode Zen (DeepSeek V4 Flash, API key required)
   - **Cloud:** Paste your API key for OpenAI/Claude/Gemini
6. Switch to Chat tab → start talking!

<img width="2560" height="1080" alt="Desktop Screenshot 2026 06 26 - 06 17 09 46" src="https://github.com/user-attachments/assets/631969c5-20b9-405d-a271-8944b201e1d6" />


## 🌐 Connecting Claude / Cursor via MCP

1. Start the MCP server in the sidebar
2. Run a tunnel: npx localtunnel --port 8090
3. Copy the URL and add /mcp at the end
4. In Claude: Settings → Extensions → Add MCP Server → paste URL
5. In Cursor: Settings → MCP → Add Server → paste URL

## 📋 Requirements

- Blender 4.1+ (tested on 5.1)
- An AI provider (LM Studio for local, or API key for cloud)
- Python 3.x (comes with Blender)

## 📝 License

Free to use. Do not redistribute or repackage.

## 🙋 Support

- Open an issue on GitHub
- Twitter/X: [@MakanAnsariCG](https://x.com/MakanAnsariCG)

<img width="1664" height="928" alt="1782525488" src="https://github.com/user-attachments/assets/a85257ea-7c0d-4ec8-a199-3858b1b9291d" />

---

**Made with ❤️ by [Makan Ansari](https://x.com/MakanAnsariCG)**
```

---
