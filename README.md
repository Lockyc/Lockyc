> *Small, composable pieces of a digital construct.*

<!-- fleet.sh profile: begin -->

## Apps

**[warden](https://github.com/Lockyc/warden)** — Curated terminals - a macOS console of grouped project tabs of embedded libghostty terminal surfaces.

**[excerpt](https://github.com/Lockyc/excerpt)** — macOS screenshot tool: capture, scrolling capture and annotation, plus a cut tool that removes the middle of a screenshot and marks it with a torn seam

**[curator](https://github.com/Lockyc/curator)** — Curated browser keeper-tabs - a macOS console of grouped webview tabs, useful for dashboards, chat, and other persistent webview surfaces.

**[flotilla](https://github.com/Lockyc/flotilla)** — A macOS workspace where any tab can head a group of documents (usually a Google Drive folder), each document open once, the session restored on relaunch.

**[glance](https://github.com/Lockyc/glance)** — Fast, keyboard-driven macOS image viewer: instant arrow-key navigation through a folder, a full-window thumbnail grid with hover-enlarge preview, and the default handler for every image type except PDF.

**[manicule](https://github.com/Lockyc/manicule)** — macOS menu-bar default browser that routes each link to the right browser profile, with a fast icon-strip picker and rules learned from your picks.

**[jot](https://github.com/Lockyc/jot)** — Hotkey-toggled macOS scratchpad — plain-text tabs, code-editor line ops, and text actions including stripping Claude's quote gutter

**[linkboy](https://github.com/Lockyc/linkboy)** — Fast, keyboard-driven macOS reader for link-aggregator feeds on Miniflux — each item's page and its comments, in logged-in web views

**[cooee](https://github.com/Lockyc/cooee)** — macOS menu-bar app that runs Google Meet in its own window and floats the other people's faces in an always-on-top window you snap to where you look.

**[darkfield](https://github.com/Lockyc/darkfield)** — macOS presenting app — only the windows you choose, on a clean canvas over your wallpaper, shared to a call or shown on a projector

## Tools

**[plate](https://github.com/Lockyc/plate)** — Go CLI that makes or inspects visual artefacts for print and web pipelines: cutout, inpaint, infill, upscale, colour grade, HTML→PNG/PDF render, markdown→PDF, press-ready PDF, diff, font embed, QR, demo-clip render — pinned engines, measured quality

**[docgraph](https://github.com/Lockyc/docgraph)** — Pre-push gate for agent-facing repo docs — content/metadata graph islands, broken links, frontmatter, untracked markdown, leak scan — plus diff-scoped drift checks (footgun, covers, Stop-hook doc-drift) and read-only doc-graph views

**[compositor](https://github.com/Lockyc/compositor)** — A Rust static-site generator for Markdown doc repos — a from-scratch MkDocs replacement (reusable render engine + CLI)

**[mycelium](https://github.com/Lockyc/mycelium)** — A cross-repo ecosystem map for agents. Each repo carries a small mycelium.toml describing what it is and what it provides; mycelium merges them into one graph an agent reads to discover the repos, services and capabilities around it.

**[cred](https://github.com/Lockyc/cred)** — Move a credential from your fingers to a file, without it touching argv, history, or an agent transcript.

## Building blocks

Shared guts behind the apps above.

**[shell-core](https://github.com/Lockyc/shell-core)** — The shared Tauri app-shell + release tooling for warden, curator, lector, and flotilla

**[chrome-core](https://github.com/Lockyc/chrome-core)** — The shared sidebar UI for the warden, curator, lector, and flotilla apps — the grouped tab rows, resize-drag and density styling, written once as framework-free CSS + vanilla JS the apps embed at build time.

**[config-core](https://github.com/Lockyc/config-core)** — The shared config primitives behind warden, curator, lector and flotilla — house-formats each app's TOML config, edits windows, groups and tabs while preserving your comments, provides the leaf-free model types, resolves the config path, parses accent colours, discovers project roots, and writes a starter config on request.

**[libghostty-build](https://github.com/Lockyc/libghostty-build)** — CI that builds Ghostty's embedding library from a pinned, unmodified upstream commit and publishes it as a release asset — build tooling, no library source of its own

## Dormant

Still published, no longer the focus.

**[agentmux](https://github.com/Lockyc/agentmux)** — A configurable tmux launcher for agent sessions. Define your AI agents — or any CLI — in TOML; each opens in its own colour-coded tmux window and prefix-m cycles between them. Runs in any terminal.

**[lector](https://github.com/Lockyc/lector)** — Curated rendered docs - a macOS console of grouped tabs, each a local Markdown repo rendered live with hot-reload and simple editing.

<!-- fleet.sh profile: end -->
