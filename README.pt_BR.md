<!-- l10n-sync: source-file="README.md" -->

🌐 [English](README.md) | [Español](README.es.md)

<div align="center">

# 🎯 Soc Ops

### Social Bingo · GitHub Copilot Agent Lab

*Quebre o gelo em eventos presenciais — depois construa algo incrível com IA*

[![Jogar](https://img.shields.io/badge/🎮_Jogar-Demo_ao_Vivo-4CAF50?style=for-the-badge)](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/)
[![Guia do Lab](https://img.shields.io/badge/📚_Guia_do_Lab-Passo_a_Passo-0078D4?style=for-the-badge)](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/)
[![.NET 10](https://img.shields.io/badge/.NET-10-512BD4?style=for-the-badge&logo=dotnet)](https://dotnet.microsoft.com/download/dotnet/10.0)
[![Blazor WASM](https://img.shields.io/badge/Blazor-WebAssembly-7B2FBE?style=for-the-badge&logo=blazor)](https://dotnet.microsoft.com/apps/aspnet/web-apps/blazor)

</div>

---

## O que é o Soc Ops?

**Soc Ops** é duas coisas em uma:

| 🎮 Um Jogo de Social Bingo | 🤖 Um Workshop de GitHub Copilot |
|---|---|
| Encontre pessoas que correspondam às perguntas do seu cartão de bingo. Consiga 5 em uma fileira para ganhar! Perfeito como quebra-gelo para meetups, conferências e eventos de equipe. | Um laboratório prático onde você usará o **Modo Agente do VS Code** para transformar este próprio app — redesenhando a UI, adicionando funcionalidades e explorando fluxos de trabalho multi-agente. |

---

## ✨ Funcionalidades

- 🃏 **Cartões Dinâmicos** — Tabuleiros únicos e aleatórios a cada jogo
- ✅ **Marcação Interativa** — Clique nas casas ao encontrar correspondências
- 🏆 **Detecção de Bingo** — Detecção automática em linhas, colunas e diagonais
- 🎉 **Modal de Celebração** — Animação satisfatória ao vencer
- 📱 **Mobile-Friendly** — Layout responsivo para qualquer dispositivo
- ⚡ **Blazor WebAssembly** — .NET rápido no lado do cliente rodando no navegador

---

## 🧪 O Lab: Aprenda o Modo Agente do GitHub Copilot

Este repositório é o ponto de partida para um **workshop prático de ~1 hora**. Você usará os recursos de agente do GitHub Copilot para melhorar iterativamente o app — e aprenderá poderosos padrões de desenvolvimento assistido por IA.

### O que Você Vai Aprender

| # | Habilidade | Você vai... |
|---|------------|-------------|
| 1 | **Engenharia de Contexto** | Ensinar o Copilot sobre seu codebase com instruções personalizadas |
| 2 | **Agentes em Background** | Executar tarefas em paralelo sem interromper seu fluxo |
| 3 | **Desenvolvimento Design-First** | Iterar em temas de UI com design visual guiado por IA |
| 4 | **TDD Multi-Agente** | Construir funcionalidades com fluxos Red → Green → Refactor |

### Partes do Lab

| Parte | Título | Tempo |
|-------|--------|-------|
| [**00**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=00-overview) | Visão Geral & Lista Rápida | — |
| [**01**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=01-setup) | Configuração & Engenharia de Contexto | 15 min |
| [**02**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=02-design) | Frontend Design-First | 15 min |
| [**03**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=03-quiz-master) | Quiz Master Personalizado | 10 min |
| [**04**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=04-multi-agent) | Desenvolvimento Multi-Agent | 20 min |

> 📝 Os guias do lab também estão disponíveis na pasta [`workshop/pt_BR/`](workshop/pt_BR/) para leitura offline.

---

## 🚀 Início Rápido

### Pré-requisitos

- [.NET 10 SDK](https://dotnet.microsoft.com/download/dotnet/10.0) ou superior
- [VS Code](https://code.visualstudio.com/) com [GitHub Copilot](https://marketplace.visualstudio.com/items?itemName=GitHub.copilot)

### Opção A — GitHub Codespaces ☁️ *(mais rápido)*

1. Clique em **Use this template** → **Create a new repository**
2. Abra seu novo repositório → **Code** → **Codespaces** → **Create codespace on main**
3. Aguarde o devcontainer e execute `/setup` no painel de Chat

### Opção B — Executar Localmente 💻

```bash
git clone https://github.com/SEU_USUARIO/my-soc-ops-csharp
cd my-soc-ops-csharp/SocOps
dotnet run
```

### Compilar

```bash
cd SocOps
dotnet build
```

> 🚢 O deploy é feito automaticamente no GitHub Pages a cada push para `main`.

---

## 🏗️ Stack Tecnológico

| Camada | Tecnologia |
|--------|-----------|
| Linguagem | C# 13 / .NET 10 |
| Framework UI | Blazor WebAssembly |
| Estilos | CSS utilities personalizadas (inspirado no Tailwind) |
| Hospedagem | GitHub Pages |
| CI/CD | GitHub Actions |
