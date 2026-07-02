<!-- gh-profile:meta {"intensity": "fancy", "last_refresh": "2026-07-02T10:34:57Z", "min_contributions": 750, "min_stars_badge": 30, "shipped_window_months": 6, "skill_version": "0.2.0"} -->

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
- `2026-07-02` Pushed to [yasyf/cc-interact](https://github.com/yasyf/cc-interact) — replaced dispatch hardcoding with a per-op scope policy and narrowed subject resolution to a window's own review
- `2026-07-02` Pushed to [yasyf/homebrew-tap](https://github.com/yasyf/homebrew-tap) — added a shared Swift CLI release pipeline (release-swift.yml, swift-v1) and rolled the synckitd and cc-review casks
- `2026-07-02` Pushed to [yasyf/synckit](https://github.com/yasyf/synckit) — added a busy gate that defers watches, with skipped-busy counts wired through the sync service and daemon
- `2026-07-02` Pushed to [yasyf/cc-review](https://github.com/yasyf/cc-review) — added a review lifecycle: expire idle reviews after 24h, close-without-submitting, and close/list repair commands
- `2026-07-02` Pushed to [yasyf/fusekit](https://github.com/yasyf/fusekit) — built a tart VM harness for kernel-panic repro, added prefix-aware overlay skips and a writable fully-remote tree mode
- `2026-07-02` Triaged issues in [macos-fuse-t/fuse-t](https://github.com/macos-fuse-t/fuse-t)
- `2026-07-02` Pushed to [yasyf/captain-hook](https://github.com/yasyf/captain-hook) — added model-routing guard hooks (general/models pack) with ToolInput and WorkflowScript conditions
- `2026-07-02` Pushed to [yasyf/reposync](https://github.com/yasyf/reposync) — hardened the vcs layer with typed command errors, structural divergence classification, and a shared vcstest fixture
- `2026-07-02` Pushed to [yasyf/yclaw](https://github.com/yasyf/yclaw) — swapped the max-effort rule for a model routing table
- `2026-07-02` Pushed to [yasyf/spawnllm](https://github.com/yasyf/spawnllm) — delegated the build to the shared release-pypi-build.yml@pypi-v1 caller while keeping OIDC publish in-repo
- `2026-07-02` Pushed to [yasyf/semisweet](https://github.com/yasyf/semisweet) — unified CI onto current action majors (Node-24) and swapped the max-effort rule for a model routing table
- `2026-07-02` Pushed to [yasyf/cc-factory](https://github.com/yasyf/cc-factory) — swapped the max-effort rule for a model routing table

**9,809 contributions in the last year**
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
- [cc-factory](https://github.com/yasyf/cc-factory) — a software factory where orchestrated agents plan, build, review, and ship
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
- `2026-07-02` [cc-review v0.19.0](https://github.com/yasyf/cc-review/releases/tag/v0.19.0) — added a review lifecycle: expire idle reviews after 24h, close-without-submitting, and close/list repair commands
- `2026-07-02` [captain-hook v4.4.0](https://github.com/yasyf/captain-hook/releases/tag/v4.4.0) — added model-routing guard hooks (general/models pack) with ToolInput and WorkflowScript conditions
- `2026-07-02` [fusekit v0.25.0](https://github.com/yasyf/fusekit/releases/tag/v0.25.0) — added prefix-aware overlay skipping (SkipPrefixes) and hardened the tart VM panic harness
- `2026-07-02` [slop-cop v0.1.26](https://github.com/yasyf/slop-cop/releases/tag/v0.1.26) — unified GitHub Actions onto current majors (Node-24 baseline)
- `2026-07-02` [cc-pool v0.35.1](https://github.com/yasyf/cc-pool/releases/tag/v0.35.1) — composed the shared homebrew-tap@v1 release tail (codesign, notarize, render-formula) and cleared golangci findings
- `2026-07-02` [spawnllm v0.5.3](https://github.com/yasyf/spawnllm/releases/tag/v0.5.3) — delegated the build to the shared release-pypi-build.yml@pypi-v1 caller while keeping OIDC publish in-repo
- `2026-06-16` [cc-interact v0.1.0](https://github.com/yasyf/cc-interact/releases/tag/v0.1.0) — initial release of the agent⟷daemon⟷web framework extracted from cc-review
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
