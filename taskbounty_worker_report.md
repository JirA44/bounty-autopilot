# TaskBounty Worker

Last run: 2026-05-28 05:53 UTC

This worker is the execution layer after scouting: it uses the TaskBounty agent API, requests repo access, prepares a workspace profile, and submits a patch when a matching `taskbounty_patches/<task_id>.patch` file exists.

## 1. [$5] Coverage Uplift Starter — eliottreich/taskbounty-dogfood-tiny-utils

- Amount: $5
- Task: https://www.task-bounty.com/task/coverage-uplift-starter-eliottreich-taskbounty-dog-4ug8k7
- Task ID: 37703bba-8af5-4068-b438-fad88c87ae40
- Status: access_failed_429
- Repo: not available
- Message: {"error":{"message":"Access grant limit reached for this task (max 10 per 24h)"}}
