# Autopilot Health

Last run: 2026-05-28 01:30 UTC

Overall: `degraded`

The automation can still scout, solve locally through Codex, submit ready patches, and follow up; at least one online capability is degraded.

## Checks

- `ok` GitHub interaction token: Token available for comments, fork, push, and PR submission.
- `degraded` Bounty scout scheduler: bounty_worker_queue.md is stale (100 minutes old); dispatch sent.
- `degraded` GitHub claimer scheduler: github_bounty_claim_report.md is stale (80 minutes old); dispatch sent.
- `degraded` GitHub submitter scheduler: github_bounty_submission_report.md is stale (81 minutes old); dispatch sent.
- `degraded` TaskBounty scout scheduler: taskbounty_report.md is stale (74 minutes old); dispatch sent.
- `degraded` TaskBounty worker scheduler: taskbounty_worker_report.md is stale (86 minutes old); dispatch sent.
- `degraded` Online model solver key: GitHub Actions cannot generate new code patches without a model key. Local Codex automation is configured as the solving fallback.
- `ok` TaskBounty credentials: TaskBounty API and agent id are available.
- `ok` GitHub bounty claimer: Comments tracked: 3
- `ok` GitHub patch solver report: Latest report parsed; local Codex is fallback if online model key is missing.
- `ok` TaskBounty patch solver report: Latest report parsed; local Codex is fallback if online model key is missing.
- `ok` GitHub bounty submitter: PRs tracked: 3
- `ok` TaskBounty worker: Worker report exists.
- `ok` Ready patch files: GitHub patches: 3; TaskBounty patches: 1.
- `ok` Candidate feeds: GitHub candidates: 5; TaskBounty candidates: 1.

## Tracked Comments

- https://github.com/SecureBananaLabs/bug-bounty/issues/979#issuecomment-4559646266
- https://github.com/commaai/opendbc/issues/2017#issuecomment-4559645983
- https://github.com/dev-kp-eloper/BountyScout/issues/33#issuecomment-4559646108

## Tracked PRs

- https://github.com/orchestration-agent/AgentOrchestration/pull/20
- https://github.com/orchestration-agent/AgentOrchestration/pull/98
- https://github.com/orchestration-agent/AgentOrchestration/pull/99
