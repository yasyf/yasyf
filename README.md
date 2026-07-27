<!-- gh-profile:meta {"intensity": "fancy", "last_refresh": "2026-07-27T10:26:27Z", "min_contributions": 750, "min_stars_badge": 30, "shipped_window_months": 6, "skill_version": "0.2.0"} -->

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
- Hard-cutting the whole cc-* fleet onto shared substrate: [daemonkit](https://github.com/yasyf/daemonkit) for daemon lifecycle — stable launchd program paths, verifier self-probes, drain-on-upgrade — and [binrun](https://github.com/yasyf/binrun) for distribution, with every release gated on a tag resolving to one exact commit on main
- Running [cc-sentiment](https://github.com/yasyf/cc-sentiment), an open experiment in whether developer sentiment with Claude Code tracks the model, the tooling, or just the time of day
- Self-hosting [yclaw](https://github.com/yasyf/yclaw), an always-on, reproducible Apple Silicon home server for the Nous hermes-agent — gVisor-sandboxed and tailnet-only, so the agent never touches your credentials
- Engineer & CEO at [Aneta](https://aneta.company)

<details>
<summary>Recent activity</summary>

<!-- gh-profile:start:activity -->
- `2026-07-27` Was active in [yasyf/spawnllm](https://github.com/yasyf/spawnllm)
- `2026-07-27` Pushed to [yasyf/spawnllm](https://github.com/yasyf/spawnllm) — required trusted signed release tags
- `2026-07-27` Pushed to [yasyf/fusekit](https://github.com/yasyf/fusekit)
- `2026-07-27` Pushed to [yasyf/cc-context](https://github.com/yasyf/cc-context)
- `2026-07-27` Pushed to [yasyf/homebrew-tap](https://github.com/yasyf/homebrew-tap) — bumped the tap formulae for cc-notes, cookiesync, and cc-orchestrate
- `2026-07-27` Pushed to [yasyf/cc-pool](https://github.com/yasyf/cc-pool) — polled for the deferred durable untrack and matched the widget's FuseKit pin to v1.15.3
- `2026-07-27` Pushed to [yasyf/cc-notes](https://github.com/yasyf/cc-notes) — reworked the v0.48.0 JSON surface: summaries on listings and acks, zero values omitted
- `2026-07-27` Pushed to [yasyf/cc-skills](https://github.com/yasyf/cc-skills) — kept the codex lane lock out of the GC's hands and made ship run prek hooks once per commit
- `2026-07-27` Pushed to [yasyf/cookiesync](https://github.com/yasyf/cookiesync) — hardened source tag verification and allowed packaged FuseKit helpers
- `2026-07-27` Pushed to [yasyf/cc-patch](https://github.com/yasyf/cc-patch)
- `2026-07-27` Pushed to [yasyf/reposync](https://github.com/yasyf/reposync)
- `2026-07-27` Starred [vercel-labs/scriptc](https://github.com/vercel-labs/scriptc)

**16,845 contributions in the last year**
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
- [cc-sudo](https://github.com/yasyf/cc-sudo) — sudo for Claude Code: one Touch ID tap per privileged command
- [cc-patch](https://github.com/yasyf/cc-patch) — fast mode for Claude Code's delegated agents, re-applied automatically on every spawn

**Taming long sessions**

- [cc-merge](https://github.com/yasyf/cc-merge) — a merge queue for the git worktrees where finished Claude outputs land
- [cc-context](https://github.com/yasyf/cc-context) — ccx, a token-bounded codebase-context facade over semble + tilth
- [cc-squash](https://github.com/yasyf/cc-squash) — augmented auto-compaction for marathon Claude Code sessions
- [cc-vigil](https://github.com/yasyf/cc-vigil) — a transcript-oracle sleep inhibitor that keeps your Mac awake only while Claude agents are truly working

**Claude Code, off the clock**

- [getaway](https://github.com/yasyf/getaway) — plan award trips from Claude Code: sweeps seats.aero across 28 mileage programs and composes whole journeys, flights out and home plus hotel award nights via rooms.aero
- [dailies](https://github.com/yasyf/dailies) — stop being your own cron job

**Systems & libraries**

- [authkit](https://github.com/yasyf/authkit) — a signed macOS helper for Touch ID consent and Secure Enclave attestation, replacing the old cookiesync keyhelper
- [fusekit](https://github.com/yasyf/fusekit) — detached FUSE-T mount-holder and mount-lifecycle primitives for Go, now under cc-pool and cc-notes
- [daemonkit](https://github.com/yasyf/daemonkit) — the durable daemon-lifecycle runtime the cc-* control planes now ride: detached spawns, codesign trust, and drain-on-upgrade
- [binrun](https://github.com/yasyf/binrun) — fetch, verify, and exec the exact artifact a descriptor pins: release binaries, Python tools, signed apps — the shim the cc-* tools now ship behind
- [semisweet](https://github.com/yasyf/semisweet) — an async, in-memory semantic cache with pluggable backends
- [experiment-at-home](https://github.com/yasyf/experiment-at-home) — the plumbing every local AI experiment rebuilds, built once: modal, mlx-lm, and tinker backends behind one registry
- [spawnllm](https://github.com/yasyf/spawnllm) — call an LLM from any subshell: Claude, Codex, or a local MLX model
- [pocket-llm](https://github.com/yasyf/pocket-llm) — on-device LLM sessions for any browser: Chrome's Prompt API, WebLLM, or wllama, picked by feature detection, smallest model first

**Cross-host sync**

- [synckit](https://github.com/yasyf/synckit) — the shared substrate the tools below build on: host mesh, a convergent registry, unix-socket RPC, and synckitd, the daemon they now ride
- [reposync](https://github.com/yasyf/reposync) — your other machine already pulled: git checkouts kept in step across every host you work from
- [cookiesync](https://github.com/yasyf/cookiesync) — your other Mac already did the 2FA: browser sessions moved between your own machines, consent gated behind Touch ID via authkit

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
- `2026-07-27` [spawnllm v0.11.0](https://github.com/yasyf/spawnllm/releases/tag/v0.11.0)
- `2026-07-27` [cc-notes v0.48.2](https://github.com/yasyf/cc-notes/releases/tag/v0.48.2)
- `2026-07-27` [captain-hook v12.20.12](https://github.com/yasyf/captain-hook/releases/tag/v12.20.12)
- `2026-07-26` [cc-context v0.34.0](https://github.com/yasyf/cc-context/releases/tag/v0.34.0)
- `2026-07-26` [cc-skills v1.8.4](https://github.com/yasyf/cc-skills/releases/tag/v1.8.4) — let the binrun shim tell the codex binary its plugin root, and kept the lane lock out of the GC
- `2026-07-26` [cc-pool v0.64.8](https://github.com/yasyf/cc-pool/releases/tag/v0.64.8)
- `2026-07-24` [slop-cop v0.1.58](https://github.com/yasyf/slop-cop/releases/tag/v0.1.58)
- `2026-07-18` [authkit v0.2.0](https://github.com/yasyf/authkit/releases/tag/v0.2.0) — pinned cookiesync trust by its shipped module-path codesign identifier
<!-- gh-profile:end:shipped -->

## 🛠 Toolbox

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,go,ruby,c,js,swift,php,html,docker,git,bash,githubactions" alt="Python, Go, Ruby, C, JavaScript, Swift, PHP, HTML, Docker, Git, Bash, GitHub Actions">
</p>

<details>
<summary>Language breakdown</summary>

<!-- gh-profile:start:languages -->
```text
Go          ████████████████████   35%
Python      ████████████████████   35%
Ruby        ██████░░░░░░░░░░░░░░   10%
Rust        ████░░░░░░░░░░░░░░░░    6%
Swift       ████░░░░░░░░░░░░░░░░    6%
TypeScript  ████░░░░░░░░░░░░░░░░    6%
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
