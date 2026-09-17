<!-- gh-profile:meta {"intensity": "fancy", "last_refresh": "2026-09-17T21:37:16Z", "min_contributions": 750, "min_stars_badge": 30, "shipped_window_months": 6, "skill_version": "0.2.0"} -->

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

- Building the missing toolbelt for Claude Code: [captain-hook](https://github.com/yasyf/captain-hook) for declarative hooks, [cc-pool](https://github.com/yasyf/cc-pool) for account pooling, [cc-review](https://github.com/yasyf/cc-review) for reviewing Claude's diffs in a PR-style web UI, [cc-transcript](https://github.com/yasyf/cc-transcript) for typed transcripts, and [slop-cop](https://github.com/yasyf/slop-cop) to catch AI-flavored prose — and now to rewrite it, with a `plainify` pass that puts prose into plain English under word and vocabulary constraints
- Turning design docs into something you can interrogate: the `design-doc` skill in [cc-skills](https://github.com/yasyf/cc-skills) went v0.12.0 to v0.16.0 in three days — a summary deck and Mermaid overview diagrams, term hover and a plain-language twin beside every section, then an Ask bar over the whole document whose follow-ups stay grounded in the doc, whose cites preview the evidence they lean on, and whose every doc now makes exactly one argument. A doc is now something you can talk back to as well: reader comments arrive as margin threads anchored to the quote they mark, queue through an append-only outbox, and land as pull requests that merge themselves. That machinery has since become shared substrate: v0.17.0 builds design-doc's template, scripts, and component schemas from canonical partials, and the new `incident-retro` skill rides the same partials — one canonical `retro.json` beside committed evidence snapshots (Datadog notebooks, Slack threads, images) rendering as an interactive retro with Markdown and PDF editions, TTD/TTE/TTM/TTR tiles derived from timestamps alone, and a Google Docs importer that records every guess it made rather than smoothing the narrative. design-doc now drafts its prose with Astra and falls back to Claude, and a new `long-running` skill carries the context discipline the multi-lane orchestration needs — a lane that now writes its own state down, with [cc-notes](https://github.com/yasyf/cc-notes) capturing user replies as durable answers it can recall, and an open-PR ledger over cc-notes plus a landing desk above it still in flight
- Converging those pieces into one session-activity platform — typed events, a decision ledger, and now a `corpus` command in cc-transcript, so one sweep answers a hundred questions instead of one, with captain-hook as its hook runtime. Both sides now read a relay envelope as agent-injected, so a relay stops opening a turn in cc-transcript and stops counting as an authored prompt in captain-hook, whose dispatch judges lane tool events against the lane transcript rather than the parent's task, scales its budget to live sessions, reads its version from Info.plist rather than exec'ing capt-hookd, and digests settings down to the enablement keys — so a busy machine stops blocking hooks, no hook pays two execve for a string, and settings churn stops costing every root a 3.3s spawn. That runtime has since gone after its own per-event cost: less overhead per event in the Python worker, workers stopped concurrently at restart and shutdown, a Python reply discarded once its caller has abandoned the id, and cc-transcript 14.16.1 underneath so a deep condition stops reparsing sidechains. The 12.30.8 through 12.30.11 line has since made a root deleted underneath a running hookd survivable: the worker leaves the removed directory before the runtime's init getcwd, cleans the temp dir it spawned in, and reads its plugin roster from the nearest surviving ancestor — with [binrun](https://github.com/yasyf/binrun) taking that same getcwd fix, and cc-transcript answering a deep predicate from held inputs rather than held lifts — and building [cc-orchestrate](https://github.com/yasyf/cc-orchestrate) into a pure-Go CLI that runs fleets of agents across pluggable backends like cmux, superset, tmux, and zellij, each with an AgentProber liveness check for long-lived, keep-alive sessions — with [cc-vigil](https://github.com/yasyf/cc-vigil), a transcript-oracle sleep inhibitor, keeping the Mac awake only while those agents are truly working. The 12.31 through 12.37 line has since taken the scheduler out of the hook runtime altogether: hookd runs hooks as one plain `capt-hookd` command, the worker runs async hooks in-process and reads the plugin roster from files, and an event's hooks run concurrently — alongside a new `MessageDisplay` event, a `plain_english` pack that rewrites assistant replies into plain English before being folded into `general`, a gate that blocks prose questions skipping AskUserQuestion, the hook client resolved through binrun's `copy_exec`, and daemonkit v0.31.1 underneath so an aborted install stops wedging upgrades — while cc-transcript keeps pace: `ActivityLift` lifts a session incrementally, and deep lifts evict least-recently-used so a second lead stops reparsing every event
- Running the whole cc-* fleet on shared substrate: [daemonkit](https://github.com/yasyf/daemonkit) for daemon lifecycle — one macOS-only Serve/Client/Control surface, one schema generating the frame codec for both Go and Swift behind a drift gate, and no byte reaching a peer whose code identity hasn't been judged. captain-hook, cc-pool, cc-notes, cc-interact, fusekit, cookiesync, synckit, cc-orchestrate, cc-present, cc-review, cc-runtime, and cc-squash have all moved onto it, each stating a deadline budget at every choke point; v0.22 took the socket path out of a spawned child's argv entirely — the child inherits its session on fd 3 — and v0.23 has since moved every daemon's private state under `~/.daemonkit/a/<label>`, with HelperPaths no longer deriving the socket at all. With v0.23 in, the fleet has deleted what it made obsolete: daemonkit retired `RemoveUnmarked` and its `ErrMarked` sentinel, the deprecated launchd `SessionType` API, the legacy bbolt sweep, the pre-rename metadata migration, and the markerless-plist fallback, and synckit dropped its pre-v0.21 LaunchAgent sweep — while every agent plist now renders a Homebrew-first PATH. v0.24 has since let a `version.file` read the host's version without a spawn and taught gc to prune the tool store, with [binrun](https://github.com/yasyf/binrun) repinned onto it the same day — and v0.25 has put a clock on an idle session, so a peer that neither sends another frame nor closes its socket gives its lane slot back instead of holding it until the daemon restarts, with a full lane now carrying its own error: a consumer can tell transient saturation from a daemon that was never installed, where captain-hook had been reporting the first as the second and sending operators to reinstall a healthy host — and v0.26 through v0.28 have taught a signed app to name a formula as its upgrade hint and to require a minimum version, and a python-tool install to refresh uv's index, with [binrun](https://github.com/yasyf/binrun) repinned onto each one the day it landed — and v0.28.1 and v0.29.0 have since gone after the lifecycle's own edges: a demanded session gets proved inside the children tail's own deadline, a kill keeps one settlement grace instead of compounding them, and an abort that restored the incumbent now says so rather than reporting a bare failure — and v0.30 through v0.31.1 have moved the install itself: attesting once before quiesce, compiling Python bytecode at install, exec'ing a signed app's entrypoint straight from the artifact cache, and restaging a candidate slot the request isn't landing, so an aborted install stops wedging the next upgrade — with [binrun](https://github.com/yasyf/binrun) repinned onto v0.31.0 for `copy_exec`
- Cutting that substrate through to releases: [cc-review](https://github.com/yasyf/cc-review) has cut 0.36.0 — daemonkit v0.23.0 underneath, cc-interact v0.33.0's subprocess-free Root above it, and a daemon that chains turn starts when no review is open — while [cc-runtime](https://github.com/yasyf/cc-runtime) cut 0.18.0 onto the same surface, cc-orchestrate runs its pty hosts as Serve products under one Daemon, and [binrun](https://github.com/yasyf/binrun) gates every release on a tag resolving to one exact commit on main
- Teaching [cc-context](https://github.com/yasyf/cc-context) to ship the way I actually branch: `ccx vcs stack` drives a Graphite stack that spans one working copy per branch — restacking one spread across working copies instead of refusing it, pinning every child to its own copy and `gt track` to its branch, and running a repo's hooks only where CI never will. Those paths have since moved off the gt CLI: the stack is read from Graphite's own database, the downstack submits over Graphite's API, and a refusal carries what Graphite actually said — with `ccx vcs status` reading the merge queue through gt to reconstruct the snapshot no GitHub field carries, catching a branch reparented out from under its PR, submitting one whose work is already committed instead of refusing it, and no longer telling a `--no-commit` ship to re-run the command that just failed. Restack has since moved onto `git replay`, so a branch another worktree holds can no longer stop the stack, a merged decline from gt gets read rather than dropped, and the submit anchors on the remote trunk so it drops the branches Graphite already holds. v0.57.0 has since taught the submit to open one pull request per Graphite call, the way gt does, to ship a path-scoped change whose paths are already committed, and to report a failed `--amend` rather than pushing the un-amended commit — and v0.58.0 has taken the last of gt out of the ship itself, committing and restacking the graphite lane without it, resolving a non-stub git, and overlapping what the ship used to do serially — and v0.58.1 and v0.58.2 have taught `ccx vcs` to read a queue landing from the trunk rather than the closing account
- Running [cc-sentiment](https://github.com/yasyf/cc-sentiment), an open experiment in whether developer sentiment with Claude Code tracks the model, the tooling, or just the time of day
- Self-hosting [yclaw](https://github.com/yasyf/yclaw), an always-on, reproducible Apple Silicon home server for the Nous hermes-agent — gVisor-sandboxed and tailnet-only, so the agent never touches your credentials
- Engineer & CEO at [Aneta](https://aneta.company)

<details>
<summary>Recent activity</summary>

<!-- gh-profile:start:activity -->
- `2026-09-17` Was active in [yasyf/cc-context](https://github.com/yasyf/cc-context)
- `2026-09-17` Pushed to [yasyf/cc-context](https://github.com/yasyf/cc-context)
- `2026-09-17` Worked on a pull request in [yasyf/cc-context](https://github.com/yasyf/cc-context)
- `2026-09-17` Pushed to [yasyf/cc-skills](https://github.com/yasyf/cc-skills) — pinned binrun v0.7.0 for signed-app copy_exec in the guides
- `2026-09-17` Pushed to [yasyf/homebrew-tap](https://github.com/yasyf/homebrew-tap) — bumped the cc-skills, captain-hook, and cc-notes formulae
- `2026-09-17` Worked on a pull request in [yasyf/captain-hook](https://github.com/yasyf/captain-hook) — blocked prose questions that skip AskUserQuestion
- `2026-09-17` Was active in [yasyf/cc-patch](https://github.com/yasyf/cc-patch)
- `2026-09-17` Created something new in [yasyf/captain-hook](https://github.com/yasyf/captain-hook)
- `2026-09-17` Pushed to [yasyf/captain-hook](https://github.com/yasyf/captain-hook) — took daemonkit v0.31.1 so an aborted install stops wedging upgrades
- `2026-09-17` Pushed to [yasyf/spawnllm](https://github.com/yasyf/spawnllm)
- `2026-09-17` Worked on a pull request in [yasyf/spawnllm](https://github.com/yasyf/spawnllm)
- `2026-09-17` Worked on a pull request in [yasyf/cc-skills](https://github.com/yasyf/cc-skills) — gated codex's agent-plane spawns and matched the launcher's runner lookup

**26,754 contributions in the last year**
<!-- gh-profile:end:activity -->

</details>

## 🚀 Start here

<!-- gh-profile:start:featured -->
- **[gpt-do](https://github.com/yasyf/gpt-do)** ⭐ 211 — GPT-powered bash commands. `Python`
- **[summ](https://github.com/yasyf/summ)** ⭐ 152 — GPT-based Conversation Summarizer `Python`
- **[compress-gpt](https://github.com/yasyf/compress-gpt)** ⭐ 217 — Self-extracting GPT prompts for ~70% token savings `Python`
- **[anthropic-computer-use-modal](https://github.com/yasyf/anthropic-computer-use-modal)** ⭐ 50 — Anthropic Computer Use with Modal Sandboxes `Python`
- **[shamer](https://github.com/yasyf/shamer)** ⭐ 37 — Code Coverage Gamified `Python`
<!-- gh-profile:end:featured -->

## 🧰 More things I built

**Claude Code, continued**

- [cc-skills](https://github.com/yasyf/cc-skills) — the plugin marketplace where the whole toolbelt ships
- [cc-guides](https://github.com/yasyf/cc-guides) — src→artifact doc rendering with embedded canonical fragments, keeping every repo's CLAUDE.md and AGENTS.md in sync
- [cc-notes](https://github.com/yasyf/cc-notes) — a notes-and-tasks layer agents can actually use, now with a derived knowledge graph over everything they've recorded
- [cc-runtime](https://github.com/yasyf/cc-runtime) — a runtime that hands Claude Code its harness-injected tools, AskUserQuestion and friends
- [cc-interact](https://github.com/yasyf/cc-interact) — the human-in-the-loop agent/daemon/web framework, pulled out of cc-review
- [cc-present](https://github.com/yasyf/cc-present) — ad-hoc live web artifacts for a session: approval boards and choices whose every click streams back to the agent
- [cc-factory](https://github.com/yasyf/cc-factory) — a software factory where orchestrated agents plan, build, review, and ship
- [cc-steer](https://github.com/yasyf/cc-steer) — learns how you steer Claude from past sessions, then does the steering for you
- [cc-pane](https://github.com/yasyf/cc-pane) — one pane of glass over Claude Code and the whole cc-* toolbelt
- [cc-sudo](https://github.com/yasyf/cc-sudo) — sudo for Claude Code: one Touch ID tap per privileged command
- [cc-patch](https://github.com/yasyf/cc-patch) — fast mode for Claude Code's delegated agents, re-applied automatically on every spawn, now with local packs and replace sites

**Taming long sessions**

- [cc-merge](https://github.com/yasyf/cc-merge) — a merge queue for the git worktrees where finished Claude outputs land
- [cc-context](https://github.com/yasyf/cc-context) — ccx, token-bounded codebase context for agents; takes `cat` away from your agent
- [cc-squash](https://github.com/yasyf/cc-squash) — augmented auto-compaction for marathon Claude Code sessions
- [cc-vigil](https://github.com/yasyf/cc-vigil) — a transcript-oracle sleep inhibitor that keeps your Mac awake only while Claude agents are truly working

**Claude Code, off the clock**

- [getaway](https://github.com/yasyf/getaway) — plan award trips from Claude Code: sweeps seats.aero across 28 mileage programs and composes whole journeys, flights out and home plus hotel award nights via rooms.aero
- [dailies](https://github.com/yasyf/dailies) — stop being your own cron job

**Systems & libraries**

- [authkit](https://github.com/yasyf/authkit) — a signed macOS helper for Touch ID consent and Secure Enclave attestation, replacing the old cookiesync keyhelper
- [fusekit](https://github.com/yasyf/fusekit) — detached FUSE-T mount-holder and mount-lifecycle primitives for Go, now under cc-pool and cc-notes, with a process ledger that tells a real reboot from a slewed clock
- [daemonkit](https://github.com/yasyf/daemonkit) — the durable daemon-lifecycle runtime the cc-* control planes now ride: detached spawns, codesign trust, and drain-on-upgrade
- [binrun](https://github.com/yasyf/binrun) — fetch, verify, and exec the exact artifact a descriptor pins: release binaries, Python tools, signed apps — the shim the cc-* tools now ship behind
- [semisweet](https://github.com/yasyf/semisweet) — an async, in-memory semantic cache with pluggable backends
- [experiment-at-home](https://github.com/yasyf/experiment-at-home) — the plumbing every local AI experiment rebuilds, built once: modal, mlx-lm, and tinker backends behind one registry
- [spawnllm](https://github.com/yasyf/spawnllm) — call an LLM from any subshell: Claude, Codex, a local MLX model, or Apple's on-device Foundation Models
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
- `2026-09-17` [captain-hook v12.40.0](https://github.com/yasyf/captain-hook/releases/tag/v12.40.0)
- `2026-09-17` [spawnllm v0.13.4](https://github.com/yasyf/spawnllm/releases/tag/v0.13.4)
- `2026-09-17` [cc-notes v0.55.0](https://github.com/yasyf/cc-notes/releases/tag/v0.55.0)
- `2026-09-17` [cc-skills v1.13.0](https://github.com/yasyf/cc-skills/releases/tag/v1.13.0)
- `2026-09-15` [cc-context v0.58.2](https://github.com/yasyf/cc-context/releases/tag/v0.58.2) — read a queue landing from the trunk, not the closing account
- `2026-09-15` [slop-cop v0.1.71](https://github.com/yasyf/slop-cop/releases/tag/v0.1.71)
- `2026-08-30` [cc-pool v0.69.0](https://github.com/yasyf/cc-pool/releases/tag/v0.69.0) — added `ccp package reset` to retire a wedged deployment
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
- [Less prompts, more guardrails](https://yasyf.com/writing/less-prompts-more-guardrails/)
- [Improving Claude Computer Use](https://yasyf.com/writing/improving-claude-computer-use/)
- [On Securing Model Supply Chains](https://yasyf.com/writing/on-llm-supply-chain-attacks/)
- [python 🤝 `defer`](https://yasyf.com/writing/bringing-gos-defer-to-python/)
- [Haystack + Pinecone Hybrid Vectors](https://yasyf.com/writing/hybrid-vectors-are-cool/)
<!-- BLOG-POST-LIST:END -->

---

<p align="center"><em>Automate the boring parts, then automate the automation.</em></p>

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/yasyf/yasyf/output/github-snake-dark.svg">
  <img src="https://raw.githubusercontent.com/yasyf/yasyf/output/github-snake.svg" alt="Contribution graph eaten by a snake">
</picture>
