<p align="center">
  <img src=".github/assets/zreds-logo.svg" alt="Zreds" width="120">
</p>

<h3 align="center">Zreds</h3>

<p align="center">
  Wire anything to anything.
  <br>
  A visual automation platform. Drag-and-drop blocks, real-time dashboards, dozens of integrations. No code.
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
A node-graph editor with 130+ blocks across triggers, actions, getters, and logic. Multi-page Weaves, grouping, comments, undo/redo, drawings, data inspector. Import and export as JSON.

### Live Dashboards
Real-time dashboards built from 25+ widget types. Wire any block output to a widget and it streams live over WebSockets. Resize, group, customize per-widget.

- **Display widgets:** counter, gauge, number, status, table, text, time series, log list, date/time, image, map, 3D plot, YouTube embed.
- **Input widgets:** button, switch, sync switch, slider, knob, number, text, selector, date/time, swiper, terminal, voice.

### Sharing and Embeds
- **Public Weave view** -- read-only link to the live graph, anyone can watch it run.
- **Public dashboards** -- standalone URL, optional email + password gate.
- **Embeddable widgets** -- drop any single widget into OBS, a docs page, or any site with one iframe.
- **Community Hub** -- publish a Weave snapshot so others can browse, vote, and import it.

### Workspaces and Teams
Each connected account gets isolated workspaces. Weaves, integrations, and dashboards are scoped per workspace. Invite teammates (Starter and above).

### Plugins
Extend the platform with user-built blocks. Templates accept namespaced inputs and produce structured outputs.

---

## Integrations

| Service | Capabilities |
|---|---|
| **Twitch** | Chat, moderation, EventSub (follows / subs / raids / bits / gifts / bans / timeouts / polls / predictions / ads), stream info, clip and poll creation, bring-your-own-bot |
| **Discord** | Bot messaging, embeds, reactions, message and member events, slash commands, bulk operations, bring-your-own-bot |
| **Spotify** | Now playing, recently played, queue control, skip, URL check |
| **YouTube** | Video playback control, search-and-play |
| **League of Legends** (Riot API) | Live game state, rank, summoner info, match history, champion mastery |
| **Google** | Gmail drafts, Google Sheets read / write / append |
| **MQTT** | Topic pub / sub, JSON publish, topic match, custom brokers, IoT devices |
| **OpenWeather** | Real-time weather data |
| **Telegram** | Bot messaging, message events |
| **GitHub** | Webhook events (push / PR / issues), issue and comment creation |
| **AI** | Claude, ChatGPT -- text generation and processing |
| **Device Tunnels** | Expose local devices to your Weaves over a secure tunnel |
| **Database** | Per-Weave history append / get / clear |

Plus 40+ core utility blocks: cooldowns, rate limiters, string formatting, debug, branching, math, JSON, HTTP.

---

## Pricing

| Tier | Price | Weaves | Runs / month | Widgets / dashboard | Retention | Workspaces |
|---|---|---|---|---|---|---|
| Free | $0 | 5 | 1,000 | 10 | 7 days | 1 |
| Starter | $9 / mo | 25 | 10,000 | 50 | 30 days | 3 |
| Pro | $29 / mo | 50 | 100,000 | 200 | 90 days | 10 |

Sign in with Google, GitHub, Twitch, or Spotify.

---

## Getting Started

1. Sign up at [beta.zreds.com](https://beta.zreds.com).
2. Connect a service from your workspace settings.
3. Build your first Weave with the [Quick Start Guide](https://docs-beta.zreds.com).

---

## Feedback and Bug Reports

This repository is the public issue tracker for Zreds. If you run into a bug or have a feature idea:

- **Bug reports** -- [Open a bug report](https://github.com/SlimeCodex/Zreds/issues/new?template=bug_report.md)
- **Feature requests** -- [Open a feature request](https://github.com/SlimeCodex/Zreds/issues/new?template=feature_request.md)
- **General discussion** -- Join the [Discord server](https://discord.gg/sEcY2Hmfnd)

---

## About

Zreds is closed-source. This repository is the community hub for issue tracking and announcements. The source code for the platform is not publicly available.

---

## Contact

- Email: support@zreds.com
- Discord: [discord.gg/sEcY2Hmfnd](https://discord.gg/sEcY2Hmfnd)
