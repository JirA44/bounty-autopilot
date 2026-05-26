# Bounty Worker Queue

Last built: 2026-05-26 08:23 UTC

Purpose: turn scouting results into a concrete work queue for an agent. Up to 10 candidates are kept so one stale opportunity does not block the whole system. Higher-value, lower-risk items are prioritized first. Do not submit a PR unless the bug is reproduced or the requested change is clearly verified.

## Queue Item 1: BGL PR bounty hunt

- Issue: https://github.com/BitgesellOfficial/bitgesell/issues/32
- Repository: https://github.com/BitgesellOfficial/bitgesell
- Amount hint: $100
- Score: 3
- Work priority: 13.0
- Match reason: mentions bounty/reward, has visible amount, busy thread

### Worker Instructions

1. Open the issue and confirm the bounty is still active.
2. Read the repository contribution rules.
3. Clone or fork the repository only if the issue is still open and not already solved.
4. Reproduce the bug or identify the smallest requested change.
5. Add or update tests when practical.
6. Submit a focused PR with a short explanation and link it to the bounty issue.
7. Stop immediately if the issue is vague, already fixed, requires private credentials, or asks for spam/security-abuse behavior.
