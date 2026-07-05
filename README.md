> *Small, composable pieces of a digital construct.*

## Apps

**[warden](https://github.com/Lockyc/warden)** — Curated terminals - a macOS console of grouped project tabs of embedded libghostty terminal surfaces.

**[curator](https://github.com/Lockyc/curator)** — Curated browser keeper-tabs - a macOS console of grouped webview tabs, useful for dashboards, chat, and other persistent webview surfaces.

**[lector](https://github.com/Lockyc/lector)** — Curated rendered docs - a macOS console of grouped tabs, each a local Markdown repo rendered live with hot-reload and simple editing.

## Tools

**[agentmux](https://github.com/Lockyc/agentmux)** — A configurable tmux launcher for agent sessions. Define your AI agents — or any CLI — in TOML; each opens in its own colour-coded tmux window and prefix-m cycles between them. Runs in any terminal.

**[mycelium](https://github.com/Lockyc/mycelium)** — A cross-repo ecosystem map for agents. Each repo carries a small mycelium.toml describing what it is and what it provides; mycelium merges them into one graph an agent reads to discover the repos, services and capabilities around it.

**[docgraph](https://github.com/Lockyc/docgraph)** — Audits a repo's agent-facing documentation graph — orphans, broken links, untracked markdown — plus content leak scan and diff-scoped footgun-drift pre-push check.

**[compositor](https://github.com/Lockyc/compositor)** — A Rust static-site generator for Markdown doc repos — a from-scratch MkDocs replacement (reusable render engine + CLI).

## Building blocks

Shared guts behind the apps above.

**[config-core](https://github.com/Lockyc/config-core)** — The shared config engine behind warden, curator and lector — parses, validates and house-formats each app's TOML config (preserving your comments), resolves its path, reads accent colours, and writes a starter config on first run.

**[shell-core](https://github.com/Lockyc/shell-core)** — The shared Tauri app-shell + release tooling for warden, curator, and lector.

**[chrome-core](https://github.com/Lockyc/chrome-core)** — The shared sidebar UI for the warden, curator, and lector apps — the grouped tab rows, resize-drag and density styling, written once as framework-free CSS + vanilla JS the apps embed at build time.

**[libghostty-build](https://github.com/Lockyc/libghostty-build)** — CI that builds Ghostty's embedding library from a pinned, unmodified upstream commit and publishes it as a release asset — build tooling, no library source of its own.
