<!-- gh-profile:meta {"intensity": "fancy", "last_refresh": "2026-06-24T13:21:13Z", "min_contributions": 750, "min_stars_badge": 30, "shipped_window_months": 6, "skill_version": "0.2.0"} -->

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
- Converging those pieces into one session-activity platform — typed events and a decision ledger in cc-transcript, with captain-hook as its hook runtime — and building [cc-orchestrate](https://github.com/yasyf/cc-orchestrate) into a pure-Go CLI that runs fleets of agents across pluggable backends like cmux, superset, tmux, and zellij, each with an AgentProber liveness check for long-lived, keep-alive sessions
- Running [cc-sentiment](https://github.com/yasyf/cc-sentiment), an open experiment in whether developer sentiment with Claude Code tracks the model, the tooling, or just the time of day
- Self-hosting [yclaw](https://github.com/yasyf/yclaw), an always-on, reproducible Apple Silicon home server for the Nous hermes-agent — gVisor-sandboxed and tailnet-only, so the agent never touches your credentials
- Engineer & CEO at [Aneta](https://aneta.company)

<details>
<summary>Recent activity</summary>

<!-- gh-profile:start:activity -->
- `2026-06-24` Pushed to [yasyf/synckit](https://github.com/yasyf/synckit) — scaffolded a generic sync toolkit — unix-socket RPC, a launchd service manager, and an LWW-Element-Set registry
- `2026-06-24` Pushed to [yasyf/spawnllm](https://github.com/yasyf/spawnllm) — redesigned the public API around run/call/extract and isolated each spawned CLI's config per run
- `2026-06-24` Pushed to [yasyf/yclaw](https://github.com/yasyf/yclaw) — hardened the Apple Silicon build — resumable hermes images and first-boot daemon activation on metal
- `2026-06-24` Pushed to [yasyf/semisweet](https://github.com/yasyf/semisweet) — migrated the semantic cache onto the spawnllm 0.5 API and added a precision-first scoring benchmark
- `2026-06-24` Pushed to [yasyf/cc-squash](https://github.com/yasyf/cc-squash) — built the two-socket cold start — Go daemon ↔ Rust proxy — with Layer-2 economics and policy crates
- `2026-06-24` Pushed to [yasyf/cc-pool](https://github.com/yasyf/cc-pool) — re-blinded the overlay onto fusekit's backends and added ccp fuse enable for one-step live-mirror setup
- `2026-06-24` Pushed to [yasyf/cc-notes](https://github.com/yasyf/cc-notes) — added an append-only log primitive, a history command for entity edit trails, and a cc-pool memory mirror
- `2026-06-24` Pushed to [yasyf/cc-sentiment](https://github.com/yasyf/cc-sentiment) — migrated the sentiment client onto spawnllm 0.5 and cc-transcript 7
- `2026-06-24` Pushed to [yasyf/cc-pushback](https://github.com/yasyf/cc-pushback) — tuned the triage judge to v5 to fix golden boundary misses; moved onto spawnllm 0.5 and cc-transcript 7
- `2026-06-24` Pushed to [yasyf/fusekit](https://github.com/yasyf/fusekit) — took ownership of the overlay abstraction across symlink, NFS, and FSKit backends, with version-skew replace
- `2026-06-24` Pushed to [yasyf/captain-hook](https://github.com/yasyf/captain-hook) — shipped 4.0 on spawnllm 0.5 and cc-transcript 7, with a broad test-suite DRY and parametrize pass
- `2026-06-24` Pushed to [yasyf/cc-transcript](https://github.com/yasyf/cc-transcript) — shipped 7.0 with a declarative MiningSpec and a dual-backend Rust signal-mining executor

**9,442 contributions in the last year**
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
- [cc-notes](https://github.com/yasyf/cc-notes) — a notes-and-tasks layer agents can actually use
- [cc-runtime](https://github.com/yasyf/cc-runtime) — a runtime that hands Claude Code its harness-injected tools, AskUserQuestion and friends
- [cc-interact](https://github.com/yasyf/cc-interact) — the human-in-the-loop agent/daemon/web framework, pulled out of cc-review
- [cc-pushback](https://github.com/yasyf/cc-pushback) — learns how you push back on Claude from past feedback, then does it for you
- [cc-pane](https://github.com/yasyf/cc-pane) — one pane of glass over Claude Code and the whole cc-* toolbelt

**Taming long sessions**

- [cc-merge](https://github.com/yasyf/cc-merge) — a merge queue for the git worktrees where finished Claude outputs land
- [cc-context](https://github.com/yasyf/cc-context) — ccx, a token-bounded codebase-context facade over semble + tilth
- [cc-squash](https://github.com/yasyf/cc-squash) — augmented auto-compaction for marathon Claude Code sessions

**Systems & libraries**

- [fusekit](https://github.com/yasyf/fusekit) — detached FUSE-T mount-holder and mount-lifecycle primitives for Go, now under cc-pool and cc-notes
- [semisweet](https://github.com/yasyf/semisweet) — an async, in-memory semantic cache with pluggable backends
- [spawnllm](https://github.com/yasyf/spawnllm) — call an LLM from any subshell: Claude, Codex, or a local MLX model
- [synckit](https://github.com/yasyf/synckit) — the shared substrate cross-host sync tools build on: host mesh, a convergent registry, and unix-socket RPC, extracted from reposync

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
- `2026-06-24` [spawnllm v0.5.1](https://github.com/yasyf/spawnllm/releases/tag/v0.5.1)
- `2026-06-24` [captain-hook v4.0.0](https://github.com/yasyf/captain-hook/releases/tag/v4.0.0) — migrated onto spawnllm 0.5 and cc-transcript 7, with a broad test-suite DRY and parametrize pass
- `2026-06-24` [cc-pool v0.34.1](https://github.com/yasyf/cc-pool/releases/tag/v0.34.1) — re-blinded the overlay onto fusekit's concrete backends and consumed its RetirePolicy for holder skew-replace
- `2026-06-23` [slop-cop v0.1.22](https://github.com/yasyf/slop-cop/releases/tag/v0.1.22) — trimmed the README to one canonical install path
<!-- gh-profile:end:shipped -->

## 🛠 Toolbox

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,go,ruby,c,js,swift,php,html,docker,git,bash,githubactions" alt="Python, Go, Ruby, C, JavaScript, Swift, PHP, HTML, Docker, Git, Bash, GitHub Actions">
</p>

<details>
<summary>Language breakdown</summary>

<!-- gh-profile:start:languages -->
```text
Python      ████████████████████   48%
Go          ██████████░░░░░░░░░░   23%
Ruby        ███████░░░░░░░░░░░░░   17%
Rust        ██░░░░░░░░░░░░░░░░░░    4%
C           █░░░░░░░░░░░░░░░░░░░    2%
JavaScript  █░░░░░░░░░░░░░░░░░░░    2%
Shell       █░░░░░░░░░░░░░░░░░░░    2%
TypeScript  █░░░░░░░░░░░░░░░░░░░    2%
```
<!-- gh-profile:end:languages -->

</details>

## ✍️ Writing

Latest from [Yasyf's Random Musings](https://musings.yasyf.com):

<!-- BLOG-POST-LIST:START -->
- [Improving Claude Computer Use](https://musings.yasyf.com/improving-claude-computer-use/)
- [On Securing Model Supply Chains](https://musings.yasyf.com/on-llm-supply-chain-attacks/)
- [python 🤝 `defer`](https://musings.yasyf.com/bringing-gos-defer-to-python/)
- [Haystack + Pinecone Hybrid Vectors](https://musings.yasyf.com/hybrid-vectors-are-cool/)
- [CompressGPT: Decrease Token Usage by ~70%](https://musings.yasyf.com/compressgpt-decrease-token-usage-by-70/)
<!-- BLOG-POST-LIST:END -->

---

<p align="center"><em>Automate the boring parts, then automate the automation.</em></p>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/yasyf/yasyf/output/github-snake-dark.svg">
  <img src="https://raw.githubusercontent.com/yasyf/yasyf/output/github-snake.svg" alt="Contribution graph eaten by a snake">
</picture>
