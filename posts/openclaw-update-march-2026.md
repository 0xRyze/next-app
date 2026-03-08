---
title: "OpenClaw 2026.3.2: ACPX Streaming and Security Hardening"
date: "2026-03-08"
excerpt: "The latest OpenClaw updates introduce ACPX streaming improvements, robust security hardening for Anthropic auth, and a massive milestone of 250,000 GitHub stars."
---

# OpenClaw Major Update: March 2026

The OpenClaw ecosystem continues to evolve at a breakneck pace. This week's releases (v2026.3.1 and v2026.3.2) bring significant performance optimizations and security enhancements to the multi-channel AI gateway.

## Key Updates

### 1. ACPX Streaming & Performance
We've streamlined how ACP (Agent Control Protocol) delivers tool events. 
- **Reduced Noise:** Tool events are now cleaner, with `final_only` delivery set as the default to reduce stream overhead.
- **ACPX Plugin Support:** Version 2026.3.1 pins ACPX support to `0.1.15`, adding configurable command and version probing.

### 2. Security Hardening
In response to community feedback and vulnerability reporting:
- **Anthropic Auth:** Subscription authentication is now "setup-token-only," significantly hardening the integration.
- **Improved Abort Logic:** We've expanded standalone stop phrases to include multilingual support (ES/FR/ZH/HI/AR/JP/DE/PT/RU), ensuring you can halt agent actions instantly in any language.

### 3. Developer Experience
- **Shell Environment Markers:** A new `OPENCLAW_SHELL` marker is now injected across all shell-like runtimes (`exec`, `acp`, `tui-local`). This allows your shell scripts and configs (`.zshrc`, `.bashrc`) to target OpenClaw contexts specifically.

## A Massive Milestone
As of March 4, 2026, **OpenClaw has surpassed 250,000 GitHub stars**, officially overtaking React in popularity. This milestone reflects the growing shift towards autonomous, multi-channel AI agents.

---
*Stay updated by following the [Official Repository](https://github.com/openclaw/openclaw).*
