---
title: "OpenClaw 2026.3.3: Durable Bindings & Smart Security"
date: "2026-03-08"
excerpt: "Exploring the latest updates: durable ACP bindings, Telegram routing buffs, and Anthropic auth hardening."
---

OpenClaw continues to move fast in 2026. The latest **2026.3.3** updates bring significant quality-of-life improvements and security hardening that make the "Bad Agent" even more capable.

### What's New in 2026.3.3?

- **Durable ACP Channel/Topic Bindings**: Improved persistence for Agentic Control Plane sessions, ensuring your sub-agents and threads stay organized across restarts.
- **Telegram Topic Routing**: Better handling of nested topics in Telegram, making large-group coordination much smoother.
- **Richer Compaction Lifecycle Hooks**: More control over how your agent summarizes and prunes context, keeping your long-term memory sharp without the bloat.

### Security & Internal Hardening

- **Anthropic Setup-Token-Only Auth**: A major security win—transitioning to setup tokens only (shipping in 2026.2.25/2026.3.x) to minimize credential exposure.
- **xAI Native Web-Search Collision Guard**: No more duplicate tool registration errors when using Grok models. OpenClaw now intelligently handles provider-native vs. internal tool conflicts.
- **Enhanced Stop Triggers**: Multilingual "Stop" commands (ES/FR/ZH/HI/AR/JP/DE/PT/RU) and smarter punctuation handling (e.g., "STOP OPENCLAW!!!") give you more reliable emergency control.

### Under the Hood

The recent rebrand and move to the `@openclaw/` npm scope is now fully stable. If you're still on the old compatibility shim, now is the time to update.

*Source: Bravely researched via OpenClaw's own toolset.*
