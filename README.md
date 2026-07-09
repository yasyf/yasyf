<!-- gh-profile:meta {"intensity": "fancy", "last_refresh": "2026-07-09T12:25:28Z", "min_contributions": 750, "min_stars_badge": 30, "shipped_window_months": 6, "skill_version": "0.2.0"} -->

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
- `2026-07-09` Pushed to [yasyf/cc-transcript](https://github.com/yasyf/cc-transcript) — shipped cc-transcript 10 — a delivery-aware session-activity oracle with a regenerated swift-bridge Swift package
- `2026-07-09` Pushed to [yasyf/cc-skills](https://github.com/yasyf/cc-skills) — built the cc-guides v3 content split — shared fragments, a fleet roster, and fan-out CI (v0.39.1)
- `2026-07-09` Pushed to [yasyf/homebrew-tap](https://github.com/yasyf/homebrew-tap) — bumped casks for cc-pool v0.50.1, cc-notes v0.22.0, ccx v0.8.1, and fusekit-holder v0.36.0
- `2026-07-09` Pushed to [yasyf/cc-pool](https://github.com/yasyf/cc-pool) — survived TCC app-group consent across upgrades via a stable-path daemon re-exec, plus ledger observability in doctor
- `2026-07-09` Pushed to [yasyf/captain-hook](https://github.com/yasyf/captain-hook) — routed delegated codex runs to the codex:codex-wrapper agent and added a teammate tight-digest nudge on SubagentStart
- `2026-07-09` Pushed to [yasyf/cc-guides](https://github.com/yasyf/cc-guides) — stood up cc-guides — src→artifact doc rendering with embedded canonical fragments and fan-out fleet CI
- `2026-07-09` Pushed to [yasyf/cc-notes](https://github.com/yasyf/cc-notes) — landed one flag vocabulary across every entity and survived concurrent git ref writes in gitobj (v0.22.0)
- `2026-07-09` Pushed to [yasyf/fusekit](https://github.com/yasyf/fusekit) — added ReexecStable — self-exec onto a stable path so path-keyed TCC grants survive upgrades
- `2026-07-08` Worked on a pull request in [posit-dev/great-docs](https://github.com/posit-dev/great-docs)
- `2026-07-08` Pushed to [yasyf/cc-context](https://github.com/yasyf/cc-context) — live-verified the ccx web tier wire shapes and auto-rewrote blocked commands to ccx equivalents (v0.8.1)
- `2026-07-08` Pushed to [yasyf/yclaw](https://github.com/yasyf/yclaw) — shipped yclaw onboard — seven auto-advancing gates with piped guest bring-up and Google Workspace OAuth connect
- `2026-07-08` Pushed to [yasyf/cc-vigil](https://github.com/yasyf/cc-vigil) — notarized the Developer ID release and shipped a Homebrew cask, with the oracle aging out stale sessions (v0.1.1)

**11,228 contributions in the last year**
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
- `2026-07-09` [cc-pool v0.50.1](https://github.com/yasyf/cc-pool/releases/tag/v0.50.1) — daemon FP healing under the claim — one-snapshot status and a doctor that explains a parked-but-never-faulted domain
- `2026-07-09` [cc-transcript v10.0.0](https://github.com/yasyf/cc-transcript/releases/tag/v10.0.0) — the delivery-aware session-activity oracle, with a swift-bridge CCTranscript Swift package
- `2026-07-08` [cc-context v0.8.1](https://github.com/yasyf/cc-context/releases/tag/v0.8.1) — live-verified the web tier wire shapes — jina warnings and a browserbase content envelope
- `2026-07-08` [captain-hook v8.14.0](https://github.com/yasyf/captain-hook/releases/tag/v8.14.0) — routed delegated codex runs to the codex:codex-wrapper agent, retiring the sonnet wrapper shape
- `2026-07-08` [slop-cop v0.1.35](https://github.com/yasyf/slop-cop/releases/tag/v0.1.35) — migrated generated files to cc-guides rendering
- `2026-07-05` [spawnllm v0.5.5](https://github.com/yasyf/spawnllm/releases/tag/v0.5.5) — passed codex --skip-git-repo-check so verdicts run in untrusted cwds
<!-- gh-profile:end:shipped -->

## 🛠 Toolbox

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,go,ruby,c,js,swift,php,html,docker,git,bash,githubactions" alt="Python, Go, Ruby, C, JavaScript, Swift, PHP, HTML, Docker, Git, Bash, GitHub Actions">
</p>

<details>
<summary>Language breakdown</summary>

<!-- gh-profile:start:languages -->
```text
Python      ████████████████████   42%
Go          ███████████████░░░░░   31%
Ruby        ████████░░░░░░░░░░░░   17%
Rust        ██░░░░░░░░░░░░░░░░░░    4%
JavaScript  █░░░░░░░░░░░░░░░░░░░    2%
Swift       █░░░░░░░░░░░░░░░░░░░    2%
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
