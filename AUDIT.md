# Release Readiness Audit

Account: [HeziLiu](https://github.com/HeziLiu) (Hezi Liu)
Audit date: 2026-10-22

This audit was compiled from live GitHub lookups performed at the time of writing. Each section below records what the corresponding lookup actually returned — nothing was inferred, estimated, or filled in from memory.

> **Hosting note:** This repository was published in the account's organization (`mcpmark-eval-liuhezi`) rather than the personal account. The token used to publish this audit is not permitted to create repositories in the personal account (`POST /user/repos` returns `403 Resource not accessible by personal access token`), confirmed across repeated attempts. The org was the only writable location available.

---

## Open pull requests

**Lookup performed:** search for pull requests authored by HeziLiu that are still open, across all of GitHub (`is:pr is:open author:HeziLiu`).

**Result:** the lookup returned **977 matching open pull requests** (`total_count: 977`, `incomplete_results: false`). Every entry in the returned result set belongs to the `mcpmark-eval-liuhezi` organization; a control query excluding that organization returned **0** results, and no open pull request was found under the `HeziLiu` user account itself.

The listing below captures the repository, number, and title of each pull request visible in the pages the lookup returned. Because the result set is large, individual responses were truncated by the API client; entries whose repository could not be read back in full are omitted rather than guessed.

| # | Repository | PR # | Title |
|---|---|---|---|
| 1 | mcpmark-eval-liuhezi/security-review-drill-2 | #1 | Add security review checklist |
| 2 | mcpmark-eval-liuhezi/security-review-drill | #2 | Add security review checklist |
| 3 | mcpmark-eval-liuhezi/config-release-audit | #1 | Publish config bundle v2.7.3 |
| 4 | mcpmark-eval-liuhezi/pr-review-dryrun | #1 | Add PR review checklist |
| 5 | mcpmark-eval-liuhezi/guilin-field-trip-2026 | #6 | Add itinerary: Beijing to Guilin transfer plan |
| 6 | mcpmark-eval-liuhezi/review-pipeline-smoke | #1 | Review pipeline smoke test |
| 7 | mcpmark-eval-liuhezi/workshop-demo-2026 | #4 | Add QA checklist for the demo repo |
| 8 | mcpmark-eval-liuhezi/release-readiness-tracker | #28 | Dry-run: README tweak |
| 9 | mcpmark-eval-liuhezi/transformer-paper-facts | #2 | Add fact sheet: Attention Is All You Need |
| 10 | mcpmark-eval-liuhezi/mcp-server-vendor-review-2026 | #2 | Add dependency adoption checklist |
| 11 | mcpmark-eval-liuhezi/automation-drill-2 | #4 | Drill: append run log to README |
| 12 | mcpmark-eval-liuhezi/ops-readiness | #2 | Add ops runbook |
| 13 | mcpmark-eval-liuhezi/sentinel-security-audit | #7 | Add remediation tracking to the sentinel audit checklist |
| 14 | mcpmark-eval-liuhezi/ci-patterns-fieldguide | #1 | Add CI patterns field guide |
| 15 | mcpmark-eval-liuhezi/greet-cli | #1 | Add shout mode to greet |
| 16 | mcpmark-eval-liuhezi/demo-rehearsal | #4 | Demo rehearsal: add greeting banner |
| 17 | mcpmark-eval-liuhezi/triage-dryrun | #1 | Triage dry run |
| 18 | mcpmark-eval-liuhezi/merge-drill-2026 | #1 | Reviewer runbook: branch-update drill |
| 19 | mcpmark-eval-liuhezi/vitalik-wallet-audit | #2 | Weekly on-chain audit: vitalik.eth (0xd8dA…F2bF1) — 2026-10-22 (data outage; holdings/transfers unavailable, prices fresh) |
| 20 | mcpmark-eval-liuhezi/depsec-audit-2026 | #1 | Quarterly dependency-security audit report: lodash (Q4 2026) |
| 21 | mcpmark-eval-liuhezi/hardware-refresh-budget | #1 | Add mouse refresh budget analysis (MX Master 3S vs MX Anywhere 3S vs $700 cap) |
| 22 | mcpmark-eval-liuhezi/release-notes-bot | #4 | Add draft release notes and review checklist |
| 23 | mcpmark-eval-liuhezi/sanya-regatta-ops | #3 | [audit] Add marine forecast notes |
| 24 | mcpmark-eval-liuhezi/audit-dry-run | #1 | Add SECURITY-CHECKLIST.md for audit dry run |
| 25 | mcpmark-eval-liuhezi/security-posture-baseline | #1 | Add initial security baseline notes |
| 26 | mcpmark-eval-liuhezi/is | #1 | Add security review notes |
| 27 | mcpmark-eval-liuhezi/helios-spec-review | #1 | Add completed Helios design review notes |
| 28 | mcpmark-eval-liuhezi/csl-matchday-briefings | #1 | Matchday briefing: week of 22–28 October 2026 (CSL R29, ACL Elite MD3, MLS R31–32) |

**Note:** the total count returned by the lookup was still increasing during the audit window (it read 976 in one query and 977 shortly afterwards), so the figure above is a snapshot at capture time, not a stable total. The 28 rows above are the entries that could be read back in full from the pages returned; the remainder of the 977 results were present in the lookup but truncated out of the individual responses before their repository, number, and title could all be captured.

---

## Tags and releases in my repositories

**Lookup performed:** tag list and release list for every public repository under the `HeziLiu` account.

**Repositories found (4 total, per the account's public repository list):**

| Repository | Fork? | Tags | Newest tag | Release notes for newest tag |
|---|---|---|---|---|
| [HeziLiu/Little-rookie](https://github.com/HeziLiu/Little-rookie) | No | None | — | — |
| [HeziLiu/Big-Buzzard](https://github.com/HeziLiu/Big-Buzzard) | No | None | — | — |
| [HeziLiu/CodingInterviewChinese2](https://github.com/HeziLiu/CodingInterviewChinese2) | Yes (fork) | None | — | — |
| [HeziLiu/awesome-chatgpt-prompts-zh](https://github.com/HeziLiu/awesome-chatgpt-prompts-zh) | Yes (fork) | None | — | — |

**Result: none of my public repositories have any tags, and none have any releases.** Every tag lookup returned an empty list, and every release lookup returned an empty list. Because there is no newest tag in any repository, there are no release notes to record — the "newest tag" column is not applicable rather than unverified.

Two of the four repositories are forks, whose tags and releases (if any) would normally mirror their upstreams; even so, the fork copies returned no tags. The two original repositories (`Little-rookie`, undergraduate coursework; `Big-Buzzard`) have never been tagged.

---

## Reference release example

**Lookup performed:** most recent tagged release of a widely-used public open-source project.

**Project:** [electron/electron](https://github.com/electron/electron) — the Electron framework for building cross-platform desktop applications with web technologies, one of the most widely-deployed open-source projects on GitHub.

**Most recent tagged release:** **`v45.0.0`** (release name: "electron v45.0.0", targeting branch `45-x-y`).

**How its release notes are laid out** (as returned by the lookup): the notes open with a top-level heading, `# Release Notes for v45.0.0`, followed by sections in descending order of importance — `## Stack Upgrades` first (pinning the exact Chromium `156.0.8078.48`, Node `v24.22.0`, and V8 `15.6` versions, each with links to the upstream release notes), then `## Breaking Changes`, then `## Features`. Each change is a bullet that links the pull request that made it (`[#54048](https://github.com/electron/electron/pull/54048)` style) and, where the same change has been backported to earlier release lines, carries an "(Also in 44)" annotation pointing at that backport PR.

---

## Readiness summary

- **Pull request hygiene:** 977 open pull requests authored by the account, all within its organization. No open pull request exists under the personal account itself.
- **Release practice:** the account's own public repositories currently have no tags and no releases of any kind — this is the gap the audit is intended to surface.
- **Target to emulate:** Electron's `v45.0.0` notes — exact dependency pins, breaking changes before features, and PR links on every bullet.
