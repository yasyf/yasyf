<!-- gh-profile:meta {"intensity": "fancy", "last_refresh": "2026-06-19T19:11:34Z", "min_contributions": 750, "min_stars_badge": 30, "shipped_window_months": 6, "skill_version": "0.2.0"} -->

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
- Converging those pieces into one session-activity platform — typed events and a decision ledger in cc-transcript, with captain-hook as its hook runtime — and building [cc-orchestrate](https://github.com/yasyf/cc-orchestrate) into a pure-Go CLI that runs fleets of agents across pluggable backends like cmux, superset, and tmux
- Running [cc-sentiment](https://github.com/yasyf/cc-sentiment), an open experiment in whether developer sentiment with Claude Code tracks the model, the tooling, or just the time of day
- Engineer & CEO at [Aneta](https://aneta.company)

<details>
<summary>Recent activity</summary>

<!-- gh-profile:start:activity -->
- `2026-06-19` Pushed to [yasyf/homebrew-tap](https://github.com/yasyf/homebrew-tap)
- `2026-06-19` Was active in [yasyf/cc-pool](https://github.com/yasyf/cc-pool)
- `2026-06-19` Pushed to [yasyf/cc-pool](https://github.com/yasyf/cc-pool) — signed and notarized the CCPoolStatus widget app and fell back to a symlink when the mount holder crash-loops
- `2026-06-19` Pushed to [yasyf/captain-hook](https://github.com/yasyf/captain-hook) — added a builtin Go pack — test-gate plus gofumpt/golangci-lint guards — and hardened the loader past unloadable hooks
- `2026-06-19` Pushed to [yasyf/cc-merge](https://github.com/yasyf/cc-merge) — stood up the new merge-queue repo: CLI skeleton, goreleaser release, and a cc-notes reconcile workflow
- `2026-06-19` Pushed to [yasyf/cc-skills](https://github.com/yasyf/cc-skills) — gave the repo-bootstrap skill a full Go layer — cobra, golangci-lint, goreleaser→Homebrew — with Developer ID signing
- `2026-06-19` Pushed to [yasyf/cc-notes](https://github.com/yasyf/cc-notes) — exposed a public in-process Go API, added `note expire` to flag stale notes, and signed the darwin binaries
- `2026-06-19` Created something new in [yasyf/cc-merge](https://github.com/yasyf/cc-merge)
- `2026-06-19` Pushed to [yasyf/cc-review](https://github.com/yasyf/cc-review) — cut a goreleaser→Homebrew release with an embedded SPA, and wrote review corrections into the shared decision ledger
- `2026-06-19` Pushed to [yasyf/reposync](https://github.com/yasyf/reposync) — rebuilt the TUI as a filterable recency-sorted master-detail and synced repos over per-host RPC sockets via watchman
- `2026-06-19` Pushed to [yasyf/cc-orchestrate](https://github.com/yasyf/cc-orchestrate) — built the repo→workstream→sprint→agent model with worktree isolation and in-process cc-notes wiring
- `2026-06-19` Pushed to [yasyf/slop-cop](https://github.com/yasyf/slop-cop) — added `--lines` to report only violations within a touched range, built for agents linting their own edits

**8,914 contributions in the last year**
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
- `2026-06-19` [cc-pool v0.31.5](https://github.com/yasyf/cc-pool/releases/tag/v0.31.5) — signed, notarized, and stapled the CCPoolStatus widget app
- `2026-06-19` [cc-orchestrate v0.2.3](https://github.com/yasyf/cc-orchestrate/releases/tag/v0.2.3) — documented the in-process cc-notes integration, gated on repo entities
- `2026-06-19` [slop-cop v0.1.19](https://github.com/yasyf/slop-cop/releases/tag/v0.1.19) — signed the darwin binaries with codesign+notarytool instead of quill
- `2026-06-19` [cc-notes v0.7.5](https://github.com/yasyf/cc-notes/releases/tag/v0.7.5) — moved the pack test script into tests/ so capt-hook skips it
- `2026-06-19` [cc-review v0.18.3](https://github.com/yasyf/cc-review/releases/tag/v0.18.3)
- `2026-06-19` [captain-hook v3.10.1](https://github.com/yasyf/captain-hook/releases/tag/v3.10.1) — skipped test files and warn-continued past unloadable hook files in the loader
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
Python      ████████████████████   54%
Go          ███████░░░░░░░░░░░░░   20%
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
