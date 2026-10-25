# MCP Foundations

Tracking repository for the **MCP Foundations** course build — a self-paced, three-module onboarding course on the Model Context Protocol (MCP).

## Course Overview

Each module is anchored on a short video from an active MCP educator, and each closes with a 100-point assignment due one week apart (starting Monday 2026-10-26).

| Module | Video | Channel | Length | Published |
|---|---|---|---|---|
| 1 | [MCP In 26 Minutes (Model Context Protocol)](https://www.youtube.com/watch?v=kOhLoixrJXo) | Tina Huang | 26m 23s | 2025-10-15 |
| 2 | [Claude's Model Context Protocol is here... Let's test it](https://www.youtube.com/watch?v=HyzlYwjoXOQ) | Fireship | 8m 8s | 2025-03-31 |
| 3 | [you need to learn MCP RIGHT NOW!! (Model Context Protocol)](https://www.youtube.com/watch?v=GuTcle5edjk) | NetworkChuck | 38m 40s | 2025-09-12 |

## Module Blurbs

### Module 1: MCP In 26 Minutes (Model Context Protocol) — Tina Huang

What you'll learn: What the Model Context Protocol is and why Anthropic created it, using the "USB-C for AI" analogy; the fundamentals of how MCP works under the hood; the three primitives every MCP server exposes — tools, resources, and prompt templates; the MCP communication life cycle; and how to build your own MCP server both no-code and with code (a Python Google Sheets & Forms server tested with MCP Inspector and registered in Claude Desktop). Four in-video quizzes check your understanding along the way.

### Module 2: Claude's Model Context Protocol is here... Let's test it — Fireship

What you'll learn: A fast, code-first reinforcement of Module 1: why MCP is described as "USB-C for AI," and a hands-on build of a TypeScript MCP server that gives an AI model additional context and the ability to modify server data. You'll go from concept to a working server in about eight minutes.

### Module 3: you need to learn MCP RIGHT NOW!! (Model Context Protocol) — NetworkChuck

What you'll learn: A production-tilted, hands-on deep dive: running MCP servers inside Docker containers; connecting three different clients (Claude Desktop, LM Studio for local models, and Cursor); building your own custom MCP servers; a Kali Linux / security-focused MCP example; and the Docker MCP Gateway, including running it with n8n.

## Repository Layout

- `README.md` — this overview
- `OUTLINE.md` — the detailed course outline (submitted via pull request for review before landing on `main`)

## Build Tracking

The course build is tracked via GitHub issues:

- Parent tracking issue: see [Issues](https://github.com/mcpmark-eval-liuhezi/mcp-foundations/issues)
- One sub-issue per module, ordered Module 1 → Module 2 → Module 3

## Notes

- The course outline is reviewed via pull request (not committed directly to `main`).
- Canvas course creation was blocked during this build (API token lacks account-admin rights); see the parent tracking issue for details.
