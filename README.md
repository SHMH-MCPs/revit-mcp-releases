# Revit MCP

**Let AI assistants read and edit the Revit 2024–2027 model open on your PC.**

Revit MCP is a free add-in for Autodesk Revit with a built-in [Model Context Protocol](https://modelcontextprotocol.io)
(MCP) server. Claude, ChatGPT, Codex, Cursor, VS Code and other AI assistants use it to work with the model that is open
in Revit — and learn, with your team, from every mistake and its fix.

**Website:** https://aecomcps.com/revit · **Download:** [Install-Revit-MCP.cmd (latest release)](https://github.com/SHMH-MCPs/revit-mcp-releases/releases/latest/download/Install-Revit-MCP.cmd)

[![Install Revit MCP and start using it — about 2 minutes](https://aecomcps.com/media/install-revit-mcp.jpg)](https://aecomcps.com/revit#video)

## What it does

- **Read the model** — categories, elements, types, levels, schedules, warnings and parameter values, in plain language
- **Model and edit** — create and change elements, data and geometry in the open model
- **Families and types** — load, edit and create families, duplicate types
- **Views and sheets** — create and edit views, tag and annotate, read sheets, export (PDF, DWG, IFC, NWC, FBX, images)
- **Shared parameters** — add them, set values in bulk, find and replace text with a preview
- **Links and worksharing** — link and import models, copy between documents, check worksets
- **Scripts and recipes** — C# against the Revit API when no tool fits; working scripts can be saved for the team
- **Learns from fixes** — when a request fails and is then fixed, the lesson helps the whole team

Every change is one Undo step in Revit, and large or destructive changes can be previewed first.

## Supported versions

| | |
|---|---|
| Revit | 2024, 2025, 2026, 2027 (Revit 2024 alone also needs the .NET 8 Desktop Runtime; setup tells you) |
| Windows | 10 or 11, 64-bit |
| Account | Google or GitHub (sign in once per PC) |
| Price | Free |

## Install

1. Download **[Install-Revit-MCP.cmd](https://github.com/SHMH-MCPs/revit-mcp-releases/releases/latest/download/Install-Revit-MCP.cmd)**
   and open it. If Windows asks, choose **Run** (or **More info › Run anyway**). No administrator rights needed.
2. Setup downloads the newest version (checksum verified, see `SHA256SUMS.txt` in each release) and sets it up for the
   Revit versions on your PC.
3. Sign in once with **Google** or **GitHub** in the window that opens.
4. Restart your AI assistant, start Revit, and ask. Updates install themselves.

Step by step: [How to connect Claude and other AI assistants to Revit](https://aecomcps.com/guides/connect-claude-to-revit).

## Supported AI apps

- **Connected automatically:** Claude Code, the Claude app, Codex, Cursor, VS Code, Windsurf, Gemini CLI, Cline
- **Any MCP client:** `http://localhost:48884/mcp`, or `revit-mcp.exe` over stdio (`revit-mcp.exe --setup show` prints the details)
- **ChatGPT and claude.ai in the browser:** optional *Cloud AI access* (off until you switch it on), connector address
  `https://aecomcps.com/mcp/revit`

## Privacy

Model, project, client, file and element names and values stay on your PC. Revit MCP shares only what the AI learns
about using its tools — which tool failed and what fixed it — with names and numbers removed on the PC and again on
arrival. The AI assistant you connect reads the tool results under its own provider's terms.
Details: [privacy policy](https://aecomcps.com/privacy) ·
[what is shared](https://aecomcps.com/guides/revit-mcp-privacy).

## Questions

shady.hefilla@hotmail.com · [Navisworks MCP](https://github.com/SHMH-MCPs/navis-mcp-releases) works the same way for Navisworks Manage.

---

Revit and Navisworks are trademarks of Autodesk, Inc. AECO MCPs is independent and not affiliated with Autodesk.
