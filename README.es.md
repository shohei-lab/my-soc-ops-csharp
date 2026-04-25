<!-- l10n-sync: source-file="README.md" -->

🌐 [English](README.md) | [Português (BR)](README.pt_BR.md)

<div align="center">

# 🎯 Soc Ops

### Social Bingo · GitHub Copilot Agent Lab

*Rompe el hielo en eventos presenciales — luego construye algo increíble con IA*

[![Jugar](https://img.shields.io/badge/🎮_Jugar-Demo_en_Vivo-4CAF50?style=for-the-badge)](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/)
[![Guía del Lab](https://img.shields.io/badge/📚_Guía_del_Lab-Paso_a_Paso-0078D4?style=for-the-badge)](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/)
[![.NET 10](https://img.shields.io/badge/.NET-10-512BD4?style=for-the-badge&logo=dotnet)](https://dotnet.microsoft.com/download/dotnet/10.0)
[![Blazor WASM](https://img.shields.io/badge/Blazor-WebAssembly-7B2FBE?style=for-the-badge&logo=blazor)](https://dotnet.microsoft.com/apps/aspnet/web-apps/blazor)

</div>

---

## ¿Qué es Soc Ops?

**Soc Ops** es dos cosas en una:

| 🎮 Un Juego de Social Bingo | 🤖 Un Workshop de GitHub Copilot |
|---|---|
| Encuentra personas que coincidan con las preguntas de tu tarjeta de bingo. ¡Consigue 5 en fila para ganar! Perfecto como icebreaker para meetups, conferencias y eventos de equipo. | Un laboratorio práctico donde usarás el **Modo Agente de VS Code** para transformar esta misma app — rediseñando la UI, añadiendo características y explorando flujos de trabajo multi-agente. |

---

## ✨ Características

- 🃏 **Tarjetas Dinámicas** — Tableros únicos y aleatorios en cada partida
- ✅ **Marcado Interactivo** — Haz clic en los cuadros al encontrar coincidencias
- 🏆 **Detección de Bingo** — Detección automática en filas, columnas y diagonales
- 🎉 **Modal de Celebración** — Animación satisfactoria al ganar
- 📱 **Mobile-Friendly** — Diseño responsive para cualquier dispositivo
- ⚡ **Blazor WebAssembly** — .NET rápido en el lado del cliente ejecutándose en el navegador

---

## 🧪 El Lab: Aprende el Modo Agente de GitHub Copilot

Este repositorio es el punto de partida para un **workshop práctico de ~1 hora**. Usarás las funciones de agente de GitHub Copilot para mejorar iterativamente la app — y aprenderás potentes patrones de desarrollo asistido por IA.

### Lo que Aprenderás

| # | Habilidad | Aprenderás a... |
|---|-----------|-----------------|
| 1 | **Ingeniería de Contexto** | Enseñar a Copilot sobre tu codebase con instrucciones personalizadas |
| 2 | **Agentes en Segundo Plano** | Ejecutar tareas en paralelo sin interrumpir tu flujo |
| 3 | **Desarrollo Design-First** | Iterar en temas de UI con diseño visual guiado por IA |
| 4 | **TDD Multi-Agente** | Construir características con flujos de trabajo Red → Green → Refactor |

### Partes del Lab

| Parte | Título | Tiempo |
|-------|--------|--------|
| [**00**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=00-overview) | Descripción General & Lista Rápida | — |
| [**01**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=01-setup) | Configuración & Ingeniería de Contexto | 15 min |
| [**02**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=02-design) | Frontend Design-First | 15 min |
| [**03**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=03-quiz-master) | Quiz Master Personalizado | 10 min |
| [**04**](https://dotnet-presentations.github.io/vscode-github-copilot-agent-lab/docs/step.html?step=04-multi-agent) | Desarrollo Multi-Agent | 20 min |

> 📝 Las guías del lab también están disponibles en la carpeta [`workshop/es/`](workshop/es/) para lectura offline.

---

## 🚀 Inicio Rápido

### Requisitos Previos

- [.NET 10 SDK](https://dotnet.microsoft.com/download/dotnet/10.0) o superior
- [VS Code](https://code.visualstudio.com/) con [GitHub Copilot](https://marketplace.visualstudio.com/items?itemName=GitHub.copilot)

### Opción A — GitHub Codespaces ☁️ *(más rápido)*

1. Haz clic en **Use this template** → **Create a new repository**
2. Abre tu nuevo repositorio → **Code** → **Codespaces** → **Create codespace on main**
3. Espera al devcontainer y luego ejecuta `/setup` en el panel de Chat

### Opción B — Ejecutar Localmente 💻

```bash
git clone https://github.com/TU_USUARIO/my-soc-ops-csharp
cd my-soc-ops-csharp/SocOps
dotnet run
```

### Compilar

```bash
cd SocOps
dotnet build
```

> 🚢 El deploy se hace automáticamente en GitHub Pages en cada push a `main`.

---

## 🏗️ Stack Tecnológico

| Capa | Tecnología |
|------|-----------|
| Lenguaje | C# 13 / .NET 10 |
| Framework UI | Blazor WebAssembly |
| Estilos | CSS utilities personalizadas (inspirado en Tailwind) |
| Hosting | GitHub Pages |
| CI/CD | GitHub Actions |
