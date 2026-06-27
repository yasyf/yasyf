<!-- gh-profile:meta {"intensity": "fancy", "last_refresh": "2026-06-27T10:26:12Z", "min_contributions": 750, "min_stars_badge": 30, "shipped_window_months": 6, "skill_version": "0.2.0"} -->

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
- `2026-06-27` Pushed to [yasyf/homebrew-tap](https://github.com/yasyf/homebrew-tap) — split release-pypi into a build-only reusable + caller-side OIDC publish, with notarization retry
- `2026-06-27` Pushed to [yasyf/reposync](https://github.com/yasyf/reposync) — adopted synckit's shared TUI (keeping only the Repos screen) and its typed RPC contract
- `2026-06-27` Pushed to [yasyf/cookiesync](https://github.com/yasyf/cookiesync) — added a Browsers + shared Hosts TUI on synckit v0.4.0 and a profile picker showing names/emails
- `2026-06-27` Pushed to [yasyf/synckit](https://github.com/yasyf/synckit) — extracted a shared TUI shell + Hosts tab and a typed RPC service contract (syncservice)
- `2026-06-27` Pushed to [yasyf/cc-skills](https://github.com/yasyf/cc-skills) — collapsed repo-bootstrap's PyPI template onto a release-pypi.yml@pypi-v1 caller with opt-in maturin
- `2026-06-27` Pushed to [yasyf/cc-pushback](https://github.com/yasyf/cc-pushback) — migrated to spawnllm 0.5's run/call/extract API with a structured Response, and tuned the judge prompt to v5
- `2026-06-27` Was active in [yasyf/cc-pushback](https://github.com/yasyf/cc-pushback)
- `2026-06-27` Pushed to [yasyf/cc-squash](https://github.com/yasyf/cc-squash) — wired the proxy to reversibly squash tool output and calibrate the live cache-economics engine
- `2026-06-27` Pushed to [yasyf/yclaw](https://github.com/yasyf/yclaw) — added unattended `just redeploy` + a `just onboard` TUI and hardened the metal daemon boot for reboot self-heal
- `2026-06-27` Pushed to [yasyf/cc-pool](https://github.com/yasyf/cc-pool) — cut over to the shared fusekit-holder over RPC, going pure-Go with no in-process holder
- `2026-06-27` Pushed to [yasyf/cc-notes](https://github.com/yasyf/cc-notes) — added --checkout/--apply to edit docs and notes as files, plus auto-sync/reconcile hooks
- `2026-06-27` Was active in [yasyf/cc-notes](https://github.com/yasyf/cc-notes)

**9,668 contributions in the last year**
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
- `2026-06-27` [cookiesync v0.6.1](https://github.com/yasyf/cookiesync/releases/tag/v0.6.1) — profile picker shows names/emails, with registered hosts sorted first
- `2026-06-27` [cc-pushback v0.7.2](https://github.com/yasyf/cc-pushback/releases/tag/v0.7.2) — adopted the shared release-pypi.yml@pypi-v1 workflow with in-repo OIDC publish
- `2026-06-26` [slop-cop v0.1.24](https://github.com/yasyf/slop-cop/releases/tag/v0.1.24) — collapsed CI onto the unified release-go.yml@v1 with codesign and auto-tag
- `2026-06-25` [captain-hook v4.2.0](https://github.com/yasyf/captain-hook/releases/tag/v4.2.0) — added SessionStore.once/unseen for keyed session dedup and a commit= diff source
- `2026-06-25` [spawnllm v0.5.2](https://github.com/yasyf/spawnllm/releases/tag/v0.5.2) — seeded an isolated CLAUDE_CONFIG_DIR per run
- `2026-06-24` [cc-pool v0.34.1](https://github.com/yasyf/cc-pool/releases/tag/v0.34.1) — re-blinded the overlay onto fusekit's concrete backends and consumed its RetirePolicy for holder skew-replace
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
Go          ███████████░░░░░░░░░   25%
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
