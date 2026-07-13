<!-- gh-profile:meta {"intensity": "fancy", "last_refresh": "2026-07-13T12:28:23Z", "min_contributions": 750, "min_stars_badge": 30, "shipped_window_months": 6, "skill_version": "0.2.0"} -->

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.webp">
  <img src="assets/banner-light.webp" alt="Yasyf Mohamedali — Engineer & CEO @ Aneta. Currently building the missing toolbelt for Claude Code." width="100%">
</picture>

<p align="center">
  <a href="https://www.yasyf.com"><img src="https://img.shields.io/badge/Website-yasyf.com-1f6feb?style=for-the-badge" alt="Website"></a>
  <a href="https://linkedin.com/in/yasyf"><img src="https://img.shields.io/badge/LinkedIn-yasyf-0a66c2?style=for-the-badge" alt="LinkedIn"></a>
  <a href="https://x.com/yasyf"><img src="https://img.shields.io/badge/X-%40yasyf-000000?style=for-the-badge" alt="X"></a>
</p>

## 🔭 Now

- Building the missing toolbelt for Claude Code: [captain-hook](https://github.com/yasyf/captain-hook) for declarative hooks, [cc-pool](https://github.com/yasyf/cc-pool) for account pooling, [cc-review](https://github.com/yasyf/cc-review) for reviewing Claude's diffs in a PR-style web UI, [cc-transcript](https://github.com/yasyf/cc-transcript) for typed transcripts, and [slop-cop](https://github.com/yasyf/slop-cop) to catch AI-flavored prose
- Converging those pieces into one session-activity platform — typed events and a decision ledger in cc-transcript, with captain-hook as its hook runtime — and building [cc-orchestrate](https://github.com/yasyf/cc-orchestrate) into a pure-Go CLI that runs fleets of agents across pluggable backends like cmux, superset, tmux, and zellij, each with an AgentProber liveness check for long-lived, keep-alive sessions — with [cc-vigil](https://github.com/yasyf/cc-vigil), a transcript-oracle sleep inhibitor, keeping the Mac awake only while those agents are truly working
- Running [cc-sentiment](https://github.com/yasyf/cc-sentiment), an open experiment in whether developer sentiment with Claude Code tracks the model, the tooling, or just the time of day
- Self-hosting [yclaw](https://github.com/yasyf/yclaw), an always-on, reproducible Apple Silicon home server for the Nous hermes-agent — gVisor-sandboxed and tailnet-only, so the agent never touches your credentials
- Engineer & CEO at [Aneta](https://aneta.company)

<details>
<summary>Recent activity</summary>

<!-- gh-profile:start:activity -->
- `2026-07-13` Pushed to [yasyf/homebrew-tap](https://github.com/yasyf/homebrew-tap) — bumped casks for synckitd v0.9.0, ccx v0.14.0, cc-present v0.8.1, cc-notes v0.28.0, and cc-pool v0.52.1
- `2026-07-13` Pushed to [yasyf/captain-hook](https://github.com/yasyf/captain-hook) — hardened the daemon for v9.9.0 — registry TOCTOU fixes, peer-uid/run-dir trust checks, in-flight request preservation
- `2026-07-13` Pushed to [yasyf/synckit](https://github.com/yasyf/synckit) — added a self-healing recursive fsnotify watch backend with supervised, backoff-restarted watches
- `2026-07-13` Pushed to [yasyf/getaway](https://github.com/yasyf/getaway) — rewrote getaway as a v2 uv CLI — a doctrine-driven planning engine over data registries — and cut 1.0.0
- `2026-07-13` Was active in [yasyf/yclaw](https://github.com/yasyf/yclaw)
- `2026-07-13` Pushed to [yasyf/experiment-at-home](https://github.com/yasyf/experiment-at-home) — new experiment-at-home toolkit — closed Phase A security & correctness findings and drafted the Phase B API spec
- `2026-07-13` Pushed to [yasyf/yclaw](https://github.com/yasyf/yclaw) — built the hermes disk image with systemd-repart (KVM-less CI) and swapped the MLX daemon to rapid-mlx 0.10.9
- `2026-07-13` Created something new in [yasyf/experiment-at-home](https://github.com/yasyf/experiment-at-home)
- `2026-07-13` Created something new in [yasyf/yclaw](https://github.com/yasyf/yclaw)
- `2026-07-13` Pushed to [yasyf/cc-present](https://github.com/yasyf/cc-present) — built focus mode — a one-decision-at-a-time card deck with swipe-to-decide, at parity across web and iOS
- `2026-07-13` Pushed to [yasyf/cc-skills](https://github.com/yasyf/cc-skills) — routed bounded work to gpt-5.6-sol via the codex skill; quieted codex exec behind a non-improvisable scratchpad log
- `2026-07-13` Pushed to [yasyf/cc-context](https://github.com/yasyf/cc-context) — v0.14.0 — git-show flag-injection & SSRF fixes, a read-only ccx auto-approver, and tilth grep zero-match re-verification

**12,030 contributions in the last year**
<!-- gh-profile:end:activity -->

</details>

## 🚀 Start here

<!-- gh-profile:start:featured -->
- **[gpt-do](https://github.com/yasyf/gpt-do)** ⭐ 211 — GPT-powered bash commands. `Python`
- **[summ](https://github.com/yasyf/summ)** ⭐ 152 — GPT-based Conversation Summarizer `Python`
- **[compress-gpt](https://github.com/yasyf/compress-gpt)** ⭐ 217 — Self-extracting GPT prompts for ~70% token savings `Python`
- **[anthropic-computer-use-modal](https://github.com/yasyf/anthropic-computer-use-modal)** ⭐ 49 — Anthropic Computer Use with Modal Sandboxes `Python`
- **[shamer](https://github.com/yasyf/shamer)** ⭐ 37 — Code Coverage Gamified `Python`
<!-- gh-profile:end:featured -->

## 🧰 More things I built

**Claude Code, continued**

- [cc-skills](https://github.com/yasyf/cc-skills) — the plugin marketplace where the whole toolbelt ships
- [cc-guides](https://github.com/yasyf/cc-guides) — src→artifact doc rendering with embedded canonical fragments, keeping every repo's CLAUDE.md and AGENTS.md in sync
- [cc-notes](https://github.com/yasyf/cc-notes) — a notes-and-tasks layer agents can actually use
- [cc-runtime](https://github.com/yasyf/cc-runtime) — a runtime that hands Claude Code its harness-injected tools, AskUserQuestion and friends
- [cc-interact](https://github.com/yasyf/cc-interact) — the human-in-the-loop agent/daemon/web framework, pulled out of cc-review
- [cc-present](https://github.com/yasyf/cc-present) — ad-hoc live web artifacts for a session: approval boards and choices whose every click streams back to the agent
- [cc-factory](https://github.com/yasyf/cc-factory) — a software factory where orchestrated agents plan, build, review, and ship
- [cc-steer](https://github.com/yasyf/cc-steer) — learns how you steer Claude from past sessions, then does the steering for you
- [cc-pane](https://github.com/yasyf/cc-pane) — one pane of glass over Claude Code and the whole cc-* toolbelt

**Taming long sessions**

- [cc-merge](https://github.com/yasyf/cc-merge) — a merge queue for the git worktrees where finished Claude outputs land
- [cc-context](https://github.com/yasyf/cc-context) — ccx, a token-bounded codebase-context facade over semble + tilth
- [cc-squash](https://github.com/yasyf/cc-squash) — augmented auto-compaction for marathon Claude Code sessions
- [cc-vigil](https://github.com/yasyf/cc-vigil) — a transcript-oracle sleep inhibitor that keeps your Mac awake only while Claude agents are truly working

**Systems & libraries**

- [fusekit](https://github.com/yasyf/fusekit) — detached FUSE-T mount-holder and mount-lifecycle primitives for Go, now under cc-pool and cc-notes
- [semisweet](https://github.com/yasyf/semisweet) — an async, in-memory semantic cache with pluggable backends
- [spawnllm](https://github.com/yasyf/spawnllm) — call an LLM from any subshell: Claude, Codex, or a local MLX model
- [synckit](https://github.com/yasyf/synckit) — the shared substrate cross-host sync tools build on: host mesh, a convergent registry, unix-socket RPC, and synckitd, the daemon reposync and cookiesync now ride

**Python, with fewer footguns**

- [python-defer](https://github.com/yasyf/python-defer) — Go-style `defer` in Python, no decorators required
- [python-secret-type](https://github.com/yasyf/python-secret-type) — a rune-style `secret` type so credentials can't leak by accident
- [docker-dsl](https://github.com/yasyf/docker-dsl) — write multi-stage Dockerfiles as Python context managers
- [bcferries](https://github.com/yasyf/bcferries) — the Python client for BC Ferries schedules; proudly Canadian 🇨🇦

**Earlier eras**

- [safemodels](https://github.com/yasyf/safemodels) — cryptographic provenance proofs for model weights, before that was cool
- [vc](https://github.com/yasyf/vc) — the voting platform Dorm Room Fund used to pick its investments
- [hifromtheotherside](https://github.com/yasyf/hifromtheotherside) — fighting the echo chamber, one cross-aisle match at a time
- [controlio](https://github.com/yasyf/controlio) — control your computer over SMS, 2014 edition

## 📦 Recently shipped

<!-- gh-profile:start:shipped -->
- `2026-07-13` [spawnllm v0.6.0](https://github.com/yasyf/spawnllm/releases/tag/v0.6.0) — file-backed claude stdout capture that fixes the 64KiB pipe truncation, plus retried-away attempt transparency
- `2026-07-13` [captain-hook v9.9.0](https://github.com/yasyf/captain-hook/releases/tag/v9.9.0) — deny-wins dispatch precedence plus the attach-only pack contract — pack lint, versioned plugin, async-decision guard
- `2026-07-13` [cc-pool v0.52.1](https://github.com/yasyf/cc-pool/releases/tag/v0.52.1) — fixed a lease-agent fd-3 crash by single-sourcing --ready-fd parsing; hid File Provider overlay domains from Finder
- `2026-07-12` [slop-cop v0.1.41](https://github.com/yasyf/slop-cop/releases/tag/v0.1.41) — packs.toml — added the missing steering pack to match the go flavor
- `2026-07-12` [cc-guides v0.1.21](https://github.com/yasyf/cc-guides/releases/tag/v0.1.21) — kind dirs at pack root only, case-folded README reservation, and import-name validation
- `2026-06-16` [cc-interact v0.1.0](https://github.com/yasyf/cc-interact/releases/tag/v0.1.0) — initial release — the domain-agnostic agent ⟷ daemon ⟷ web framework extracted from cc-review
<!-- gh-profile:end:shipped -->

## 🛠 Toolbox

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,go,ruby,c,js,swift,php,html,docker,git,bash,githubactions" alt="Python, Go, Ruby, C, JavaScript, Swift, PHP, HTML, Docker, Git, Bash, GitHub Actions">
</p>

<details>
<summary>Language breakdown</summary>

<!-- gh-profile:start:languages -->
```text
Python      ████████████████████   46%
Go          █████████████░░░░░░░   29%
Ruby        █████░░░░░░░░░░░░░░░   12%
Rust        ██░░░░░░░░░░░░░░░░░░    4%
Swift       ██░░░░░░░░░░░░░░░░░░    4%
JavaScript  █░░░░░░░░░░░░░░░░░░░    2%
TypeScript  █░░░░░░░░░░░░░░░░░░░    2%
```
<!-- gh-profile:end:languages -->

</details>

## ✍️ Writing

Latest from [Yasyf's Random Musings](https://musings.yasyf.com):

<!-- BLOG-POST-LIST:START -->
- [Improving Claude Computer Use](https://yasyf.com/writing/improving-claude-computer-use/)
- [On Securing Model Supply Chains](https://yasyf.com/writing/on-llm-supply-chain-attacks/)
- [python 🤝 `defer`](https://yasyf.com/writing/bringing-gos-defer-to-python/)
- [Haystack + Pinecone Hybrid Vectors](https://yasyf.com/writing/hybrid-vectors-are-cool/)
- [CompressGPT: Decrease Token Usage by ~70%](https://yasyf.com/writing/compressgpt-decrease-token-usage-by-70/)
<!-- BLOG-POST-LIST:END -->

---

<p align="center"><em>Automate the boring parts, then automate the automation.</em></p>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/yasyf/yasyf/output/github-snake-dark.svg">
  <img src="https://raw.githubusercontent.com/yasyf/yasyf/output/github-snake.svg" alt="Contribution graph eaten by a snake">
</picture>
