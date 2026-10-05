<div align="center">
  <a href="https://composal.ai">
    <img src="https://raw.githubusercontent.com/ComposalAI/cli/main/assets/composal-silver-sticker.svg" width="320" alt="Composal silver foil sticker">
  </a>
  <h1>Composal CLI</h1>
  <p><strong>Verify changes. Ship apps. Equip your agents.</strong></p>
  <p>
    <a href="https://www.npmjs.com/package/@composal/cli">npm</a> ·
    <a href="https://github.com/ComposalAI/cli">GitHub</a> ·
    <a href="https://composal.ai/docs">Documentation</a> ·
    <a href="https://composal.ai">Composal</a>
  </p>
</div>

---

`com` brings Composal to your terminal and coding agents. Verify real user journeys,
deploy applications, manage secrets, and connect your agent to the same tools you
use to ship.

## Install

> The first npm release is being published. The standalone installer is available now.

With **Node.js 18 or newer**:

```sh
npm install -g @composal/cli
```

Prefer the standalone installer? No Node.js required:

```sh
curl -fsSL https://dl.composal.ai/install.sh | sh
```

Both options install the `com` command. Supported platforms are **macOS Apple
Silicon** and **Linux x64 with glibc**. On Windows, use an x64 WSL distribution.

You can also run without a global installation:

```sh
npx @composal/cli --help
```

For a project, install with `npm install --save-dev @composal/cli` and run `npx com`.
Pin a version with `npm install -g @composal/cli@<version>`.

## Get started

```sh
com login
com whoami
com --help
```

Follow the [quickstart](https://composal.ai/docs/quickstart) to connect your account
and run your first commands.

## What you can do

| | From your terminal |
| --- | --- |
| **[Verify](https://composal.ai/docs/verify)** | Test real browser journeys and inspect screenshots, recordings, and traces. |
| **[Ship applications](https://composal.ai/docs/hosting)** | Deploy apps, manage services and preview environments, and inspect logs. |
| **[Manage secrets](https://composal.ai/docs/cli)** | Store and retrieve secrets, or run commands with secrets injected into their environment. |
| **[Equip your agents](https://composal.ai/docs/agents)** | Set up Composal skills and MCP tools for your coding agent. |

Explore commands with `com verify --help`, `com deploy --help`, and
`com secrets --help`. The [CLI reference](https://composal.ai/docs/cli) covers the
full command set.

### Connect your coding agent

For Codex, install the skills and configure MCP together:

```sh
com setup --targets codex --mcp
```

Run `com setup --help` for other supported agents and setup options.

## Stay up to date

For a global npm installation:

```sh
npm install -g @composal/cli@latest
```

For a project installation, run `npm install --save-dev @composal/cli@latest`.

For the standalone installer:

```sh
com update
```

## Explore Composal

- [Quickstart](https://composal.ai/docs/quickstart) — install, sign in, and get started.
- [CLI reference](https://composal.ai/docs/cli) — commands and examples.
- [Verify](https://composal.ai/docs/verify) — browser testing for your application.
- [Hosting](https://composal.ai/docs/hosting) — deploy and operate your apps.
- [Agent setup](https://composal.ai/docs/agents) — bring Composal to your coding workflow.

Found an issue or have an idea? [Let us know](https://github.com/ComposalAI/cli/issues).
