<picture>
  <source media="(prefers-color-scheme: dark)" srcset="banner-dark.svg">
  <img alt="Lekto" src="banner-light.svg" width="100%">
</picture>

**Lekto reads your documents so you don't have to.** It is an open-source, self-hosted document
management system and a small family of projects around it: Lekto reads every document, files it,
finds it again and shows why it decided what it did.

| Project | What it is | Status |
| --- | --- | --- |
| [lekto](https://github.com/lektohq/lekto) | The server: REST API, web UI, workers and MCP server; image `ghcr.io/lektohq/lekto` | beta |
| pylekto | Async Python client for the Lekto REST API | coming soon |
| lekto-homeassistant | Home Assistant integration | coming soon |

### What Lekto stands for

- **Your data stays home.** Self-hosted, no cloud required; language models run where you choose.
- **Explainable.** Every decision shows its reason, and every step can be repeated.
- **Headless.** Everything goes through one REST API; the web UI is one client among others.
- **Open for automation and AI.** Signed webhooks, server-sent events and an MCP server for Claude
  and other AI clients.

### Get started

Lekto runs as one container image with SQLite or Postgres: see the
[quick start](https://github.com/lektohq/lekto#quick-start). It is in beta, so breaking changes can
come with any release; read the release notes before you update and keep a backup.
