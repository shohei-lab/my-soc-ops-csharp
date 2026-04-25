🌐 [Português (BR)](README.pt_BR.md) | [Español](README.es.md)

<div align="center">

# 🎯 Soc Ops

### Social Bingo · GitHub Copilot Agent Lab

*Break the ice at in-person events — then build something amazing with AI*

[![Play the Game](https://img.shields.io/badge/🎮_Play_Now-Live_Demo-4CAF50?style=for-the-badge)](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/)
[![Lab Guide](https://img.shields.io/badge/📚_Lab_Guide-Step_by_Step-0078D4?style=for-the-badge)](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/)
[![.NET 10](https://img.shields.io/badge/.NET-10-512BD4?style=for-the-badge&logo=dotnet)](https://dotnet.microsoft.com/download/dotnet/10.0)
[![Blazor WASM](https://img.shields.io/badge/Blazor-WebAssembly-7B2FBE?style=for-the-badge&logo=blazor)](https://dotnet.microsoft.com/apps/aspnet/web-apps/blazor)

</div>

---

## What is Soc Ops?

**Soc Ops** is two things in one:

| 🎮 A Social Bingo Game | 🤖 A GitHub Copilot Workshop |
|---|---|
| Find people who match the prompts on your bingo card. Get 5 in a row to win! Perfect icebreaker for meetups, conferences, and team events. | A hands-on lab where you'll use **VS Code Agent Mode** to transform this very app — redesigning the UI, adding features, and exploring multi-agent workflows. |

---

## ✨ Features

- 🃏 **Dynamic Bingo Cards** — Unique randomized boards every game
- ✅ **Interactive Marking** — Click squares as you find matches
- 🏆 **Win Detection** — Automatic bingo detection across rows, columns, and diagonals
- 🎉 **Celebration Modal** — Satisfying win animation
- 📱 **Mobile-Friendly** — Responsive layout for any device
- ⚡ **Blazor WebAssembly** — Fast, client-side .NET running in the browser

---

## 🧪 The Lab: Learn GitHub Copilot Agent Mode

This repo is the starting point for a **~1 hour hands-on workshop**. You'll use GitHub Copilot's agent features to iteratively improve the app — and learn powerful AI-assisted development patterns along the way.

### What You'll Learn

| # | Skill | You'll... |
|---|-------|-----------|
| 1 | **Context Engineering** | Teach Copilot about your codebase with custom instructions |
| 2 | **Background Agents** | Run parallel tasks without breaking your flow |
| 3 | **Design-First Development** | Iterate on UI themes with AI-guided visual design |
| 4 | **Multi-Agent TDD** | Build features with Red → Green → Refactor agent workflows |

### Lab Parts

| Part | Title | Time |
|------|-------|------|
| [**00**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=00-overview) | Overview & Checklist | — |
| [**01**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=01-setup) | Setup & Context Engineering | 15 min |
| [**02**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=02-design) | Design-First Frontend | 15 min |
| [**03**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=03-quiz-master) | Custom Quiz Master | 10 min |
| [**04**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=04-multi-agent) | Multi-Agent Development | 20 min |

> 📝 Lab guides are also available in the [`workshop/`](workshop/) folder for offline reading.

---

## 🚀 Quick Start

### Prerequisites

- [.NET 10 SDK](https://dotnet.microsoft.com/download/dotnet/10.0) or higher
- [VS Code](https://code.visualstudio.com/) with [GitHub Copilot](https://marketplace.visualstudio.com/items?itemName=GitHub.copilot)

### Option A — GitHub Codespaces ☁️ *(fastest)*

1. Click **Use this template** → **Create a new repository**
2. Open your new repo → **Code** → **Codespaces** → **Create codespace on main**
3. Wait for the devcontainer, then run `/setup` in the Chat panel

### Option B — Run Locally 💻

```bash
git clone https://github.com/YOUR_USERNAME/my-soc-ops-csharp
cd my-soc-ops-csharp/SocOps
dotnet run
```

Open your browser to `http://localhost:5166` and start playing!

### Build

```bash
cd SocOps
dotnet build
```

> 🚢 Deploys automatically to GitHub Pages on every push to `main`.

---

## 🏗️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Language | C# 13 / .NET 10 |
| UI Framework | Blazor WebAssembly |
| Styling | Custom CSS utilities (Tailwind-inspired) |
| Hosting | GitHub Pages |
| CI/CD | GitHub Actions |

---

## 🤝 Contributing

This repo is a workshop template. Feel free to fork it, make it your own, and share what you build!

See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.
