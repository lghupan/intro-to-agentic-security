# On Securing AI Agents: From Chatbots to Autonomous Systems

An introduction to AI agent security — covering how agents work, how they can be attacked, and how to defend them.

[**Download slides (PDF)**](https://github.com/lghupan/intro-to-agentic-security/blob/main/ai-agents-security-slides.pdf)

## Overview

- **Part 1 — Understanding Agents**: What AI agents are, real-world examples, and levels of autonomy (L1–L5)
- **Part 2 — Threats & Attacks**: Threat taxonomy, prompt injection, tool misuse, MCP supply chain attacks, OWASP Top 10 for Agentic Applications
- **Part 3 — Defenses**: Model training, safeguard models, intent classifiers, sandboxing, application hooks, and Agent Detection & Response (ADR)

## Building

Requires a TeX Live installation with the `metropolis` beamer theme.

```bash
pdflatex ai-agents-security-slides.tex
pdflatex ai-agents-security-slides.tex  # run twice for correct outlines
```

> For best font rendering, compile with `xelatex` or `lualatex` instead of `pdflatex`.
