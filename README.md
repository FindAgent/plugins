<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./.github/logo-dark.svg">
    <img alt="FindAgent" src="./.github/logo.svg" width="360">
  </picture>
</p>

<p align="center"><strong>FindAgent agents as plugins — for Claude, GitHub Copilot, VS Code, Codex and Cursor.</strong></p>

<p align="center">
  <a href="https://findagent.cloud">findagent.cloud</a> ·
  <a href="https://findagent.cloud/browse">Browse agents</a> ·
  <a href="https://findagent.cloud/security">Security</a> ·
  <a href="https://findagent.cloud/docs/connect">Connect guides</a>
</p>

---

This repository is a **generated mirror** of the [FindAgent](https://findagent.cloud) catalog. Every plugin here is an
agent that passed FindAgent's automated scan and human review, exported as the exact copy that was reviewed.
Do not open pull requests against it — changes are overwritten on the next sync. Publish or update an agent on
[findagent.cloud/submit](https://findagent.cloud/submit) instead.

## Add the marketplace

| Client | Command |
|---|---|
| Claude Code | `/plugin marketplace add team886/findagent-plugins` |
| Claude (claude.ai, Desktop) | Settings → Plugins → add marketplace `team886/findagent-plugins` |
| GitHub Copilot CLI | `copilot plugin marketplace add team886/findagent-plugins` |
| VS Code | add `team886/findagent-plugins` to `chat.plugins.marketplaces` |
| Codex | add the marketplace `team886/findagent-plugins` |
| Cursor (teams) | an admin imports `team886/findagent-plugins` as a team marketplace |

Then install any plugin by name, for example `/plugin install <agent>@findagent` in Claude Code.

## What a plugin contains

- **Skills and commands** the agent ships, as reviewed.
- **An MCP connection** to the agent on FindAgent's hosted gateway, so its tools run behind FindAgent's
  guardrails and your credentials stay bound to the hosts the agent declared.
- **Paid agents** carry only their listing and the gateway connection; the content is served after purchase.

Plugins that run code on your own computer (scripts, hooks, local servers) are kept in a separate marketplace,
[team886/findagent-plugins-local](https://github.com/team886/findagent-plugins-local), so installing one is
always a deliberate choice.

## Any other AI app

Every FindAgent agent also works over MCP in any MCP-capable client, no plugin needed — see
[findagent.cloud/docs/connect](https://findagent.cloud/docs/connect).

## License

Each plugin keeps its creator's own license, stated inside the plugin. This repository's generated catalog files
carry no separate license.
