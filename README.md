<!-- gh-profile:meta {"intensity": "fancy", "last_refresh": "2026-06-22T01:37:42Z", "min_contributions": 750, "min_stars_badge": 30, "shipped_window_months": 6, "skill_version": "0.2.0"} -->

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
- Converging those pieces into one session-activity platform — typed events and a decision ledger in cc-transcript, with captain-hook as its hook runtime — and building [cc-orchestrate](https://github.com/yasyf/cc-orchestrate) into a pure-Go CLI that runs fleets of agents across pluggable backends like cmux, superset, and tmux, now with long-lived, keep-alive agent sessions
- Running [cc-sentiment](https://github.com/yasyf/cc-sentiment), an open experiment in whether developer sentiment with Claude Code tracks the model, the tooling, or just the time of day
- Self-hosting [yclaw](https://github.com/yasyf/yclaw), an always-on, reproducible Apple Silicon home server for the Nous hermes-agent — gVisor-sandboxed and tailnet-only, so the agent never touches your credentials
- Engineer & CEO at [Aneta](https://aneta.company)

<details>
<summary>Recent activity</summary>

<!-- gh-profile:start:activity -->
- `2026-06-22` Pushed to [yasyf/captain-hook](https://github.com/yasyf/captain-hook) — added on-demand pack fetching (@latest, daily refresh) and a shared review correction ledger
- `2026-06-22` Pushed to [yasyf/yclaw](https://github.com/yasyf/yclaw) — hardened the hermes-agent home server: a gVisor runtime, a filtering docker socket proxy, and tailnet-only firewalls
- `2026-06-22` Pushed to [yasyf/cc-context](https://github.com/yasyf/cc-context) — built ccx, a compact codebase-context facade over semble + tilth, with lazy engine startup
- `2026-06-21` Pushed to [yasyf/cc-pool](https://github.com/yasyf/cc-pool) — hardened the overlay's fuse→symlink retreat and kept the macOS Network Volumes grant across upgrades
- `2026-06-21` Pushed to [yasyf/fusekit](https://github.com/yasyf/fusekit) — added a generic Supervisor/Policy for detached children and a stable-path mount holder with peer-gated kill
- `2026-06-21` Pushed to [yasyf/cc-squash](https://github.com/yasyf/cc-squash) — scaffolded cc_squash and laid out the compaction research, architecture, and build plan
- `2026-06-21` Pushed to [yasyf/homebrew-tap](https://github.com/yasyf/homebrew-tap) — published the latest cask and formula bumps across the cc-* tools
- `2026-06-21` Pushed to [yasyf/cc-orchestrate](https://github.com/yasyf/cc-orchestrate) — added a /cco plugin and AgentProber liveness across the tmux, zellij, and superset backends
- `2026-06-21` Pushed to [yasyf/cc-notes](https://github.com/yasyf/cc-notes) — added a ccn alias and made the plugin auto-install the binary on first session
- `2026-06-21` Pushed to [yasyf/cc-skills](https://github.com/yasyf/cc-skills) — taught the repo-bootstrap skill to adopt cc-context (ccx) and documented the new plugins
- `2026-06-21` Was active in [yasyf/captain-hook](https://github.com/yasyf/captain-hook)
- `2026-06-21` Created something new in [yasyf/captain-hook](https://github.com/yasyf/captain-hook)

**8,960 contributions in the last year**
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
- `2026-06-22` [captain-hook v3.13.0](https://github.com/yasyf/captain-hook/releases/tag/v3.13.0)
- `2026-06-21` [cc-context v0.1.1](https://github.com/yasyf/cc-context/releases/tag/v0.1.1) — cleared the S1–S7 acceptance-test findings and rewrote the ccx README
- `2026-06-21` [cc-pool v0.31.8](https://github.com/yasyf/cc-pool/releases/tag/v0.31.8) — swept orphaned shared overlay entries into base on the fuse→symlink retreat
- `2026-06-20` [slop-cop v0.1.20](https://github.com/yasyf/slop-cop/releases/tag/v0.1.20) — added golangci-lint v2 lint and vuln jobs and cleared the lint debt
- `2026-06-19` [spawnllm v0.3.1](https://github.com/yasyf/spawnllm/releases/tag/v0.3.1) — threaded cwd and timeout through the call() entrypoint
<!-- gh-profile:end:shipped -->

## 🛠 Toolbox

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,go,ruby,c,js,swift,php,html,docker,git,bash,githubactions" alt="Python, Go, Ruby, C, JavaScript, Swift, PHP, HTML, Docker, Git, Bash, GitHub Actions">
</p>

<details>
<summary>Language breakdown</summary>

<!-- gh-profile:start:languages -->
```text
Python      ████████████████████   53%
Go          ████████░░░░░░░░░░░░   21%
Ruby        █████░░░░░░░░░░░░░░░   13%
C           ██░░░░░░░░░░░░░░░░░░    4%
HTML        █░░░░░░░░░░░░░░░░░░░    2%
JavaScript  █░░░░░░░░░░░░░░░░░░░    2%
Nix         █░░░░░░░░░░░░░░░░░░░    2%
Rust        █░░░░░░░░░░░░░░░░░░░    2%
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
