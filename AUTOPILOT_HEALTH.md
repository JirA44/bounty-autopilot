# Autopilot Health

Last run: 2026-05-27 06:39 UTC

Overall: `active`

The automation has active work in flight, claim comments, or ready submission paths.

## Checks

- `ok` GitHub interaction token: Token available for comments, fork, push, and PR submission.
- `degraded` Bounty scout scheduler: bounty_worker_queue.md is stale (108 minutes old); dispatch sent.
- `degraded` GitHub claimer scheduler: github_bounty_claim_report.md is stale (231 minutes old); dispatch sent.
- `ok` GitHub submitter scheduler: github_bounty_submission_report.md is fresh (1 minutes old).
- `ok` TaskBounty scout scheduler: taskbounty_report.md is fresh (12 minutes old).
- `ok` TaskBounty worker scheduler: taskbounty_worker_report.md is fresh (12 minutes old).
- `degraded` Online model solver key: GitHub Actions cannot generate new code patches without a model key. Local Codex automation is configured as the solving fallback.
- `ok` TaskBounty credentials: TaskBounty API and agent id are available.
- `active` GitHub bounty claimer: Comments tracked: 1
- `ok` GitHub patch solver report: Latest report parsed; local Codex is fallback if online model key is missing.
- `ok` TaskBounty patch solver report: Latest report parsed; local Codex is fallback if online model key is missing.
- `ok` GitHub bounty submitter: PRs tracked: 3
- `ok` TaskBounty worker: Worker report exists.
- `ok` Ready patch files: GitHub patches: 3; TaskBounty patches: 1.
- `ok` Candidate feeds: GitHub candidates: 2; TaskBounty candidates: 4.

## Tracked Comments

- https://github.com/algora-io/algora/issues/303#issuecomment-4550793176

## Tracked PRs

- https://github.com/orchestration-agent/AgentOrchestration/pull/20
- https://github.com/orchestration-agent/AgentOrchestration/pull/98
- https://github.com/orchestration-agent/AgentOrchestration/pull/99
