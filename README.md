<p align="center">
  <img src=".github/assets/zreds-logo.svg" alt="Zreds" width="120">
</p>

<h3 align="center">Zreds</h3>

<p align="center">
  Wire anything to anything.
  <br>
  A visual automation platform with real-time dashboards. Drag-and-drop blocks. No code.
</p>

<p align="center">
  <a href="https://beta.zreds.com"><img src="https://img.shields.io/website?url=https%3A%2F%2Fbeta.zreds.com&label=beta.zreds.com" alt="Website"></a>
  <a href="https://docs-beta.zreds.com"><img src="https://img.shields.io/website?url=https%3A%2F%2Fdocs-beta.zreds.com&label=docs" alt="Docs"></a>
  <a href="https://discord.gg/sEcY2Hmfnd"><img src="https://img.shields.io/discord/1466139260519452859?label=discord&color=5865F2" alt="Discord"></a>
  <img src="https://img.shields.io/badge/status-beta-orange" alt="Beta">
</p>

<p align="center">
  <a href="https://beta.zreds.com">Website</a> ·
  <a href="https://docs-beta.zreds.com">Documentation</a> ·
  <a href="https://discord.gg/sEcY2Hmfnd">Discord</a>
</p>

---

## What is a Weave?

A Weave is a graph of triggers, actions, and logic blocks that runs whenever an event hits it. Signal in, your logic in the middle, something happens out. Every Weave is the same shape.

You build them by dragging blocks onto a canvas and connecting them. They run on our infrastructure as soon as you save.

---

## Features

### Visual Weave Builder
A node-graph editor with 180+ blocks. Triggers, actions, getters, and logic across 16 services. Multi-page Weaves, node grouping, inline comments, undo and redo, import and export.

### Live Dashboards
25 widget types that stream live over WebSockets. Wire any block output to a widget and watch it update in real time.

Display widgets: Number, Status, Counter, Text, Gauge, Table, Time Series, Map, Date and Time, 3D Plot, Log List, YouTube, Image.

Input widgets: Button, Switch, Sync Switch, Slider, Knob, Text Input, Number Input, Selector, Date and Time Input, Swiper, Voice Input, Terminal.

### Sharing
Three public surfaces, each with its own URL.

1. Public Weave view. A read-only link to the live graph. Visitors watch it run, they cannot edit it.
2. Public dashboard. A standalone dashboard URL. Optional viewer gating by email and password.
3. Embeddable widget. Drop any single widget into OBS, a docs page, or any iframe-friendly site.

### Community Hub
Publish a Weave so others can browse, vote, and import it. Snapshot is frozen at publish time. Credentials are never exposed.

### Workspaces
Each connected account gets isolated workspaces. Weaves, integrations, and dashboards are scoped per workspace. Team seats available on paid tiers.

### Plugins
Extend the platform with user-built blocks. Plugin blocks declare ports and a template, and run as part of any Weave.

---

## Integrations

| Service | What it does |
|---|---|
| Twitch | Chat, moderation, EventSub (follows, subs, raids, bits, gifts, bans, timeouts, polls, predictions, ads), stream info, clip and poll creation. Bring your own bot. |
| Discord | Bot messaging, embeds, reactions, message and member events, slash commands, bulk delete. Bring your own bot. |
| Spotify | Now playing, recently played, queue control, skip, URL check. |
| YouTube | Video playback control, search and play. |
| League of Legends (Riot API) | Live game state, rank compare, summoner info, active game, ranked stats, last match, champion mastery. |
| Google | Gmail draft creation, Google Sheets read range, write, append row. |
| MQTT | Topic publish and subscribe, JSON publish, topic match, custom brokers. |
| OpenWeather | Current weather lookup. |
| Telegram | Bot messaging, message events. |
| GitHub | Webhook events (push, pull request, issue), issue and comment creation. |
| AI | Claude and ChatGPT. Text generation and processing. |
| Device Tunnels | Bidirectional channel to a local device with named filter rules. |
| Database | Per-key persistent history with TTL and size cap (append, get, clear). |

Plus a Core Utilities palette: cooldowns, rate limiters, string formatting, debug, branching, math, JSON, HTTP.

---

## Pricing

| Tier | Price | Weaves | Runs / month | Widgets / dashboard | Retention | Workspaces |
|---|---|---|---|---|---|---|
| Free | $0 | 5 | 1,000 | 10 | 7 days | 1 |
| Starter | $9 / mo | 25 | 10,000 | 50 | 30 days | 3 |
| Pro | $29 / mo | 50 | 100,000 | 200 | 90 days | 10 |

Sign in with Google, GitHub, Twitch, or Discord.

---

## Getting Started

1. Sign up at [beta.zreds.com](https://beta.zreds.com).
2. Connect a service from your workspace settings.
3. Build your first Weave with the [Quick Start Guide](https://docs-beta.zreds.com).

---

## Feedback and Bug Reports

This repository is the public issue tracker for Zreds.

- Bug reports: [Open a bug report](https://github.com/SlimeCodex/Zreds/issues/new?template=bug_report.md)
- Feature requests: [Open a feature request](https://github.com/SlimeCodex/Zreds/issues/new?template=feature_request.md)
- General discussion: join the [Discord server](https://discord.gg/sEcY2Hmfnd)

---

## About

Zreds is closed-source. This repository is the community hub for issue tracking and announcements. The source code for the platform is not publicly available.

---

## Contact

- Email: support@zreds.com
- Discord: [discord.gg/sEcY2Hmfnd](https://discord.gg/sEcY2Hmfnd)
