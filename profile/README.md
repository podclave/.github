<div align="center">

<a href="https://podclave.com">
  <img src="./assets/podclave-og.png" alt="Podclave — Platform engineering, out of the box." width="720">
</a>

### We build AI-native development infrastructure.

Real, persistent, fully-loaded dev machines for your agents and projects —
plus the platform engineering that normally surrounds them — so you don't
hand-roll it.

<a href="https://podclave.com"><strong>podclave.com&nbsp;→</strong></a>

</div>

---

## ◉ Podclave — the flagship

**A control plane for renting and managing [Sprites.dev](https://sprites.dev) sandboxes, shaped for AI-assisted development.** Sign in, connect a Sprites.dev org, click **+ Sprite**, and you have a real Linux box in seconds — reachable from your phone, with `claude` pre-logged-in and `gh` pre-authed. Claude Code first.

**BYOFly — your org, your bill, your root.** Each Sprite stays yours: your Sprites.dev org, your Fly bill, your data. We orchestrate the fleet; you own the boxes. No resold compute, no metered overage.

- **A workstation in your browser** — PTY shell, file management (upload/download), and a per-Sprite control page from any device, phone and Chromebook included. Close the tab, reopen on another device, your shell comes back.
- **Credential federation** — paste your Anthropic key and OAuth GitHub once; every Sprite you provision arrives pre-authed.
- **Live-task keepalive** — while a `claude` task is running, the box stays awake; when work hits zero, it idles back down. No daemon on the box.
- **Services & scheduler** — run Postgres/Redis/etc. as managed services, route the Sprite's URL to any of them, and run commands on a schedule (which also wakes a sleeping box).
- **Send from mobile** — kick off an exposed Claude session from the control page; it shows up in Anthropic's native Remote Control automatically.
- **Org & team** — invite members who never touch the Fly token; credentials and config federate across the org.

<div align="center">

**[Get started at podclave.com →](https://podclave.com)** &nbsp;·&nbsp; First seat free.

</div>

---

## ◉ [`know`](https://github.com/podclave/know) — open source

[![License: MIT](https://img.shields.io/badge/license-MIT-15a64c.svg)](https://github.com/podclave/know/blob/main/LICENSE)

**A small, self-hosted team brain** — shared, durable memory for everyone's Claude. Ask a question and **recall** returns what the team has learned; learn something durable and your Claude **saves** it. A server-side secretary keeps it organized.

The whole thing is a git repo of one-fact-per-file markdown — **git is the truth** — wrapped in an MCP-over-HTTP server you connect to as a single URL. No vector DB; just git + markdown + a cheap `claude` agent. We build it in the open, and run it ourselves.

→ **[github.com/podclave/know](https://github.com/podclave/know)**

---

<div align="center">

<sub>

[podclave.com](https://podclave.com) &nbsp;·&nbsp; [`know`](https://github.com/podclave/know) &nbsp;·&nbsp; Built on [Sprites.dev](https://sprites.dev) + [Fly.io](https://fly.io)

</sub>

</div>
