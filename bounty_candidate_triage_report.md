# GitHub Bounty Candidate Triage

Last run: 2026-05-25 23:49 UTC

Kept candidates: 5

This pass removes unpaid, assigned, closed, market-alert, token-cost, HITL-blocked, or false-positive GitHub bounty issues before worker time is spent. Crowded but still-paid issues are allowed with a score penalty.

## 1. Proton Calendar Integration

- Decision: drop
- Score: 160 -> 55
- Issue: https://github.com/calcom/cal.com/issues/5756
- Reason: no clear open paid bounty signal >= $10 found
- Reason: competition already visible in comments; still allowed in aggressive mode

## 2. Replace panic with error handling in template loader when dialers are missing

- Decision: drop
- Score: 150 -> 15
- Issue: https://github.com/projectdiscovery/nuclei/issues/6674
- Reason: issue is not open
- Reason: competition already visible in comments; still allowed in aggressive mode

## 3. Integrate typos tool into CI

- Decision: drop
- Score: 150 -> 15
- Issue: https://github.com/projectdiscovery/nuclei/issues/6532
- Reason: issue is not open
- Reason: competition already visible in comments; still allowed in aggressive mode

## 4. Bounty 5 — `loss_stale_active` group-wide flag overwritten per-asset (engine `v16.rs:7429`); permissionless drain of `header.insurance` via `WithdrawInsuranceDomain` gate-bypass during loss-stale state

- Decision: drop
- Score: 104 -> 34
- Issue: https://github.com/aeyakovenko/percolator-prog/issues/106
- Reason: no clear open paid bounty signal >= $10 found

## 5. Bounty 5: cross-market state leak — permissionless `pnl_pos_bound_tot` inflation haircuts unrelated users and drains `header.insurance`

- Decision: keep
- Score: 104 -> 104
- Issue: https://github.com/aeyakovenko/percolator-prog/issues/104

## 6. 🎯 Bounty Alert: 11 New Opportunityies found

- Decision: keep
- Score: 100 -> 100
- Issue: https://github.com/dev-kp-eloper/BountyScout/issues/21

## 7. 📈 گزارش تحلیل فارکس - 2026-05-25

- Decision: drop
- Score: 85 -> -15
- Issue: https://github.com/alicsx/my-news-feed/issues/2832
- Reason: false positive claim/cost/market/manual-access issue, not an open coding bounty

## 8. P1: Restore standalone RL experiment-card fallback for latest E1 gate

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/lanyusea/screeps/issues/1438
- Reason: no clear open paid bounty signal >= $10 found

## 9. P1: Configure E1 predefined metric and rollout gates from runtime KPI floors

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/lanyusea/screeps/issues/1437
- Reason: no clear open paid bounty signal >= $10 found

## 10. Implement Stellar Claimable Balances for Record Rewards

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/DogStark/PetChain-MobileApp/issues/386
- Reason: no clear open paid bounty signal >= $10 found

## 11. Component primitives: Button, Input, Card, Text

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/guilherme-andrade/polyglot-ai/issues/29
- Reason: no clear open paid bounty signal >= $10 found

## 12. [RWF] pallet-child-bounties: unassign_curator leaves cumulative fees inflated

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/paritytech/polkadot-sdk/issues/12192
- Reason: no clear open paid bounty signal >= $10 found

## 13. [RWF] pallet-child-bounties: parent curator award records caller as child curator

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/paritytech/polkadot-sdk/issues/12190
- Reason: no clear open paid bounty signal >= $10 found

## 14. Master Implementation Plan

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/hearn1/hex-tactical-roguelite/issues/1
- Reason: no clear open paid bounty signal >= $10 found

## 15. Feature 20 — Content Expansion and Difficulty (M7.2)

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/hearn1/hex-tactical-roguelite/issues/22
- Reason: no clear open paid bounty signal >= $10 found

## 16. Feature 19 — Data Repository (M7.1)

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/hearn1/hex-tactical-roguelite/issues/21
- Reason: no clear open paid bounty signal >= $10 found

## 17. Feature 16 — Renown Calculation (M6.1)

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/hearn1/hex-tactical-roguelite/issues/18
- Reason: no clear open paid bounty signal >= $10 found

## 18. Feature 15 — Recruit / Pet Node (M5.3)

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/hearn1/hex-tactical-roguelite/issues/17
- Reason: no clear open paid bounty signal >= $10 found

## 19. Feature 13 — Shop Node (M5.1)

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/hearn1/hex-tactical-roguelite/issues/15
- Reason: no clear open paid bounty signal >= $10 found

## 20. Feature 12 — Boss and Run End (M4.3)

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/hearn1/hex-tactical-roguelite/issues/14
- Reason: no clear open paid bounty signal >= $10 found

## 21. Feature 11 — Combat Node Integration (M4.2)

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/hearn1/hex-tactical-roguelite/issues/13
- Reason: no clear open paid bounty signal >= $10 found

## 22. Feature 09 — Leveling (M3.2)

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/hearn1/hex-tactical-roguelite/issues/11
- Reason: no clear open paid bounty signal >= $10 found

## 23. Feature 08 — Victory Reward Screen (M3.1)

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/hearn1/hex-tactical-roguelite/issues/10
- Reason: no clear open paid bounty signal >= $10 found

## 24. Feature 07 — Item Equipment (M2.2)

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/hearn1/hex-tactical-roguelite/issues/9
- Reason: no clear open paid bounty signal >= $10 found

## 25. 实验记录：terminal-rl Qwen3-30B-A3B fresh run (118h, 350 rollout, wandb b0il0mq4) — raw_reward -0.07 → +0.19 50-rollout 均值，runner_fail 0.27%，5 次 grad spike 全 clip-grad 兜底（still running）

- Decision: drop
- Score: 79 -> 9
- Issue: https://github.com/HansBug/OpenClaw-RL/issues/14
- Reason: no clear open paid bounty signal >= $10 found

## 26. Fix crash when task title contains emoji

- Decision: drop
- Score: 79 -> 9
- Issue: https://github.com/CodeBountyOrg/taskforge-demo/issues/10
- Reason: no clear open paid bounty signal >= $10 found

## 27. Emoji Reaction Claim - 20 Reactions - 2026-05-25 21:56 UTC

- Decision: drop
- Score: 75 -> 5
- Issue: https://github.com/Scottcjn/rustchain-bounties/issues/12349
- Reason: no clear open paid bounty signal >= $10 found

## 28. PR Review Claim - 10 PRs - 2026-05-25 21:56 UTC

- Decision: drop
- Score: 75 -> 5
- Issue: https://github.com/Scottcjn/rustchain-bounties/issues/12348
- Reason: no clear open paid bounty signal >= $10 found

## 29. [Emoji Reaction] Bounty Claim - 2026-05-25 20:50 UTC

- Decision: drop
- Score: 75 -> -25
- Issue: https://github.com/Scottcjn/rustchain-bounties/issues/12345
- Reason: false positive claim/cost/market/manual-access issue, not an open coding bounty

## 30. License compliance remediation & apology — deonmenezes/mantishack

- Decision: drop
- Score: 69 -> -36
- Issue: https://github.com/vmihalis/hacker-bob/issues/49
- Reason: no clear open paid bounty signal >= $10 found
- Reason: competition already visible in comments; still allowed in aggressive mode

## 31. Froggy

- Decision: drop
- Score: 69 -> -1
- Issue: https://github.com/caustic-kronos/BotsHub/issues/181
- Reason: no clear open paid bounty signal >= $10 found

## 32. Bounty: $50 USD

- Decision: keep
- Score: 61 -> 26
- Issue: https://github.com/fredldotme/ISODriveUT/issues/12
- Reason: competition already visible in comments; still allowed in aggressive mode

## 33. Dependency Dashboard

- Decision: drop
- Score: 60 -> -10
- Issue: https://github.com/kseito/RewardedTodo/issues/102
- Reason: no clear open paid bounty signal >= $10 found

## 34. NPCs Interrupt Training and Following to Sleep

- Decision: drop
- Score: 54 -> -16
- Issue: https://github.com/CleverRaven/Cataclysm-DDA/issues/86915
- Reason: no clear open paid bounty signal >= $10 found

## 35. [Arcade/99v99]THIN BRADY

- Decision: drop
- Score: 49 -> -21
- Issue: https://github.com/OvercastCommunity/CommunityMaps/issues/1341
- Reason: no clear open paid bounty signal >= $10 found

## 36. Golden Set Curation & Test Harness

- Decision: drop
- Score: 49 -> -21
- Issue: https://github.com/OWASP-BLT/BLT-Toasty/issues/44
- Reason: no clear open paid bounty signal >= $10 found

## 37. [Feature] Add Integrity Verification (Hash of Executable/Script)

- Decision: keep
- Score: 46 -> 11
- Issue: https://github.com/javelin-anticheat/py-workedtask/issues/4
- Reason: competition already visible in comments; still allowed in aggressive mode

## 38. Progress bar in middle of bounty board

- Decision: drop
- Score: 43 -> -27
- Issue: https://github.com/FaceInCake/LetThemEatCake/issues/6
- Reason: no clear open paid bounty signal >= $10 found

## 39. Mission Lists blue prints not associated with it

- Decision: drop
- Score: 39 -> -31
- Issue: https://github.com/Osiris-DevWorks/smart-citizen/issues/47
- Reason: no clear open paid bounty signal >= $10 found

## 40. [Bounty] Analyze word-level streaming options

- Decision: drop
- Score: 36 -> -69
- Issue: https://github.com/ivrit-ai/ivrit-py/issues/12
- Reason: no clear open paid bounty signal >= $10 found
- Reason: competition already visible in comments; still allowed in aggressive mode

## 41. When a user returns `return { ... }` from a route instead of `return ctx.json({ ... })`, throw an error telling them to use `ctx.json`

- Decision: drop
- Score: 36 -> -69
- Issue: https://github.com/tscircuit/winterspec/issues/30
- Reason: no clear open paid bounty signal >= $10 found
- Reason: competition already visible in comments; still allowed in aggressive mode

## 42. BGL PR bounty hunt ($10000 overall budget)

- Decision: keep
- Score: 36 -> 1
- Issue: https://github.com/BitgesellOfficial/bitgesell/issues/39
- Reason: competition already visible in comments; still allowed in aggressive mode
