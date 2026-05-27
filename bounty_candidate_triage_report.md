# GitHub Bounty Candidate Triage

Last run: 2026-05-27 16:10 UTC

Kept candidates: 2

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

## 4. [price-oracle] Whitelisted tokens frozen at an inflated constant → phantom multi-billion TVL (PEPE, wOptiDoge)

- Decision: drop
- Score: 95 -> -5
- Issue: https://github.com/velodrome-finance/indexer/issues/786
- Reason: false positive claim/cost/market/manual-access issue, not an open coding bounty

## 5. Quiet-lead $5 PayPal order board

- Decision: drop
- Score: 94 -> 24
- Issue: https://github.com/trungcodeer/quiet-lead-follow-up/issues/1
- Reason: no clear open paid bounty signal >= $10 found

## 6. [BUG BOUNTY] [High] [Cross-Module] Irrecoverable Deadlock: Unbonded Region + Fixed Deposits + Ante Handler Creates Permanent Fund Lock With No Recovery Path

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/openmetaearth/me-hub/issues/104
- Reason: no clear open paid bounty signal >= $10 found

## 7. [BUG BOUNTY] [Medium] [wstaking] SendInviteReward Does Not Call SetInviterReward -- Duplicate Reward Payments Possible If Called Multiple Times

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/openmetaearth/me-hub/issues/95
- Reason: no clear open paid bounty signal >= $10 found

## 8. [BUG BOUNTY] [Medium] [wstaking] transferDeposit Blocks All KYC Region Transfers If Target Region Has ANY Inactive Fixed Deposit Config

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/openmetaearth/me-hub/issues/92
- Reason: no clear open paid bounty signal >= $10 found

## 9. [BUG BOUNTY] [Medium] [wstaking] RemoveMeidNFT Uses Wrong Prefix Key -- Orphaned Region Index Entries Never Cleaned Up

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/openmetaearth/me-hub/issues/88
- Reason: no clear open paid bounty signal >= $10 found

## 10. [BUG BOUNTY] [Medium] [megroup/ante] Free Gas MsgJoinGroup Enables Zero-Cost Treasury Drain via Sybil KYC Accounts

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/openmetaearth/me-hub/issues/87
- Reason: no clear open paid bounty signal >= $10 found

## 11. [BUG BOUNTY] [Medium] [wdistri] AllocateBlockReward Int64 Overflow -- Silent Reward Corruption for Large Fee Collector Balances

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/openmetaearth/me-hub/issues/86
- Reason: no clear open paid bounty signal >= $10 found

## 12. [BUG BOUNTY] [High] [wstaking] Interest Paid Before Accounting Check -- DelegateInterest Ledger Permanently Diverges from Treasury Balance

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/openmetaearth/me-hub/issues/82
- Reason: no clear open paid bounty signal >= $10 found

## 13. [BUG BOUNTY] [Critical] [wstaking] Interest Rate Manipulation via Delegate/Undelegate StartHeight Reset -- Accumulated Rewards Theft or Loss

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/openmetaearth/me-hub/issues/78
- Reason: no clear open paid bounty signal >= $10 found

## 14. [runtime]: bind prover-chosen nonce to SP1 BEEFY proofs for uncle dedup

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/polytope-labs/hyperbridge/issues/923
- Reason: no clear open paid bounty signal >= $10 found

## 15. [T10] Final Testing and Debugging

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/agntdev/habittrackerbot/issues/10
- Reason: no clear open paid bounty signal >= $10 found

## 16. Stripe / 微信支付 webhook 接入

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/CadanHu/data-analyse-system/issues/14
- Reason: no clear open paid bounty signal >= $10 found

## 17. Build invoice payment reminder sender

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/Stellar-split/split-app/issues/125
- Reason: no clear open paid bounty signal >= $10 found

## 18. Implement VotePanel Component — Real Voting Logic

- Decision: drop
- Score: 79 -> 9
- Issue: https://github.com/StellarGrant/StellarGrant-fe/issues/337
- Reason: no clear open paid bounty signal >= $10 found

## 19. design: harness-as-policy learning architecture — Phase 3+ roadmap post-#673

- Decision: drop
- Score: 79 -> -26
- Issue: https://github.com/Jinn-Network/mono/issues/689
- Reason: no clear open paid bounty signal >= $10 found
- Reason: competition already visible in comments; still allowed in aggressive mode

## 20. [P1] Reputation rewards are no-ops

- Decision: drop
- Score: 79 -> 9
- Issue: https://github.com/phash/voidSector/issues/528
- Reason: no clear open paid bounty signal >= $10 found

## 21. Phishing-gate auto-cancelling legitimate bookings — paid Teams plan, 5 support tickets/emails unanswered

- Decision: drop
- Score: 79 -> 9
- Issue: https://github.com/calcom/cal.diy/issues/29469
- Reason: no clear open paid bounty signal >= $10 found

## 22. Bug Report: API rate limiting returns 500 instead of 429

- Decision: drop
- Score: 73 -> 3
- Issue: https://github.com/chrizbo/agentics-beyond-code/issues/166
- Reason: no clear open paid bounty signal >= $10 found

## 23. consensus: cascading clock-skew enables liveness degradation and chain-time drift under current block-timestamp validation

- Decision: drop
- Score: 64 -> -6
- Issue: https://github.com/harmony-one/harmony/issues/5047
- Reason: no clear open paid bounty signal >= $10 found

## 24. T-014 · Test helper `setup_paid_order` is not reused consistently

- Decision: drop
- Score: 64 -> -6
- Issue: https://github.com/devEunicee/pulsar-contracts/issues/44
- Reason: no clear open paid bounty signal >= $10 found

## 25. Low Handing Fruit Automation

- Decision: keep
- Score: 61 -> -124
- Issue: https://github.com/SecureBananaLabs/bug-bounty/issues/743
- Reason: light competition allowed: 10 open competing PR(s)
- Reason: competition already visible in comments; still allowed in aggressive mode
- Competing PR: https://github.com/SecureBananaLabs/bug-bounty/pull/747
- Competing PR: https://github.com/SecureBananaLabs/bug-bounty/pull/765
- Competing PR: https://github.com/SecureBananaLabs/bug-bounty/pull/781
- Competing PR: https://github.com/SecureBananaLabs/bug-bounty/pull/788
- Competing PR: https://github.com/SecureBananaLabs/bug-bounty/pull/810

## 26. PMSS source audit: find attempt-without-verify logging patterns (state-change commands that log intent but not kernel-level outcome)

- Decision: drop
- Score: 56 -> -14
- Issue: https://github.com/MagnaCapax/PMSS/issues/595
- Reason: no clear open paid bounty signal >= $10 found

## 27. [3000 MRG] Implement public and logged-in notifications

- Decision: drop
- Score: 56 -> -74
- Issue: https://github.com/mergeos-bounties/mergeos/issues/19
- Reason: no clear open paid bounty signal >= $10 found
- Reason: light competition allowed: 4 open competing PR(s)
- Competing PR: https://github.com/mergeos-bounties/mergeos/pull/66
- Competing PR: https://github.com/mergeos-bounties/mergeos/pull/50
- Competing PR: https://github.com/mergeos-bounties/mergeos/pull/72
- Competing PR: https://github.com/mergeos-bounties/mergeos/pull/39

## 28. [3000 MRG] Improve create-project flow for new projects and existing bug fixes

- Decision: drop
- Score: 56 -> -184
- Issue: https://github.com/mergeos-bounties/mergeos/issues/12
- Reason: no clear open paid bounty signal >= $10 found
- Reason: light competition allowed: 9 open competing PR(s)
- Reason: competition already visible in comments; still allowed in aggressive mode
- Competing PR: https://github.com/mergeos-bounties/mergeos/pull/65
- Competing PR: https://github.com/mergeos-bounties/mergeos/pull/72
- Competing PR: https://github.com/mergeos-bounties/mergeos/pull/57
- Competing PR: https://github.com/mergeos-bounties/mergeos/pull/33
- Competing PR: https://github.com/mergeos-bounties/mergeos/pull/24

## 29. Bug: manage_hub contract — staking.rs calculate_pending_rewards uses integer division causing reward loss

- Decision: drop
- Score: 54 -> -16
- Issue: https://github.com/Hub-Assist/Hub-Assist/issues/215
- Reason: no clear open paid bounty signal >= $10 found

## 30. meta: create project roadmap (v2.0 vision)

- Decision: drop
- Score: 54 -> -16
- Issue: https://github.com/chernistry/RightLayout/issues/48
- Reason: no clear open paid bounty signal >= $10 found

## 31. 信用点购物点击领取信用点点歪了

- Decision: drop
- Score: 49 -> -21
- Issue: https://github.com/MaaEnd/MaaEnd/issues/3207
- Reason: no clear open paid bounty signal >= $10 found

## 32. Project Limit Request: ingestr

- Decision: drop
- Score: 49 -> -21
- Issue: https://github.com/pypi/support/issues/10798
- Reason: no clear open paid bounty signal >= $10 found

## 33. json in mcp server args textarea

- Decision: keep
- Score: 46 -> -19
- Issue: https://github.com/archestra-ai/archestra/issues/3859
- Reason: light competition allowed: 2 open competing PR(s)
- Reason: competition already visible in comments; still allowed in aggressive mode
- Competing PR: https://github.com/archestra-ai/archestra/pull/5082
- Competing PR: https://github.com/archestra-ai/archestra/pull/4591

## 34. [BUG] Desktop app Google Drive connector flow routes to signup page, creates duplicate account under same email and locks paid Max subscriber

- Decision: drop
- Score: 46 -> -24
- Issue: https://github.com/anthropics/claude-code/issues/51002
- Reason: no clear open paid bounty signal >= $10 found

## 35. move scalability jobs to private pull-through cache and re-enable private clusters

- Decision: drop
- Score: 40 -> -30
- Issue: https://github.com/kubernetes/test-infra/issues/34701
- Reason: no clear open paid bounty signal >= $10 found

## 36. Account recovery request

- Decision: drop
- Score: 39 -> -31
- Issue: https://github.com/pypi/support/issues/10799
- Reason: no clear open paid bounty signal >= $10 found

## 37. Account recovery request

- Decision: drop
- Score: 39 -> -31
- Issue: https://github.com/pypi/support/issues/10797
- Reason: no clear open paid bounty signal >= $10 found

## 38. [Achievement] Documenter - Improve Docs in 3+ Repos - 3 RTC

- Decision: drop
- Score: 36 -> -69
- Issue: https://github.com/Scottcjn/rustchain-bounties/issues/521
- Reason: no clear open paid bounty signal >= $10 found
- Reason: competition already visible in comments; still allowed in aggressive mode

## 39. Validate reward generation behavior

- Decision: keep
- Score: 36 -> 1
- Issue: https://github.com/devpool-directory/devpool-directory/issues/5887
- Reason: competition already visible in comments; still allowed in aggressive mode

## 40. When a user returns `return { ... }` from a route instead of `return ctx.json({ ... })`, throw an error telling them to use `ctx.json`

- Decision: drop
- Score: 36 -> -69
- Issue: https://github.com/tscircuit/winterspec/issues/30
- Reason: no clear open paid bounty signal >= $10 found
- Reason: competition already visible in comments; still allowed in aggressive mode

## 41. Fix extra trace lines in post-processing step

- Decision: keep
- Score: 36 -> 1
- Issue: https://github.com/tscircuit/schematic-trace-solver/issues/78
- Reason: competition already visible in comments; still allowed in aggressive mode

## 42. Stellar payment-link / invoice flow

- Decision: drop
- Score: 34 -> -36
- Issue: https://github.com/wraith-protocol/demo/issues/7
- Reason: no clear open paid bounty signal >= $10 found

## 43. [Achievement] Explorer - PRs to 3+ Repos - 3 RTC

- Decision: drop
- Score: 26 -> -79
- Issue: https://github.com/Scottcjn/rustchain-bounties/issues/519
- Reason: no clear open paid bounty signal >= $10 found
- Reason: competition already visible in comments; still allowed in aggressive mode

## 44. Fix failing CI checks for React Native, Rust, and Soroban pipelines

- Decision: drop
- Score: 26 -> -44
- Issue: https://github.com/Fracverse/zaps/issues/229
- Reason: no clear open paid bounty signal >= $10 found

## 45. Re-enable cargo test in CI (stellar-xdr arbitrary version mismatch)

- Decision: drop
- Score: 24 -> -81
- Issue: https://github.com/Miracle656/veil/issues/100
- Reason: no clear open paid bounty signal >= $10 found
- Reason: competition already visible in comments; still allowed in aggressive mode

## 46. Claim MRG Tokens for Bug Bounty Reports - Comment New Bugs Here Before Opening a PR

- Decision: drop
- Score: 21 -> -84
- Issue: https://github.com/mergeos-bounties/mergeos/issues/1
- Reason: no clear open paid bounty signal >= $10 found
- Reason: competition already visible in comments; still allowed in aggressive mode

## 47. Mint Authorization Framework & Multi-Signature Approval

- Decision: drop
- Score: 16 -> -54
- Issue: https://github.com/kellymusk/Aframp-backend/issues/213
- Reason: no clear open paid bounty signal >= $10 found

## 48. Database Sharding & Read Replica Strategy

- Decision: drop
- Score: 16 -> -54
- Issue: https://github.com/kellymusk/Aframp-backend/issues/398
- Reason: no clear open paid bounty signal >= $10 found

## 49. Production-trial postmortem: M-001 (trial #1 of 3 per F-2-155)

- Decision: drop
- Score: 16 -> -89
- Issue: https://github.com/Nish-Project/Nish/issues/68
- Reason: no clear open paid bounty signal >= $10 found
- Reason: competition already visible in comments; still allowed in aggressive mode

## 50. Write Getting Started Guide

- Decision: drop
- Score: 16 -> -54
- Issue: https://github.com/Soroban-Cookbook/Soroban-Cookbook-/issues/180
- Reason: no clear open paid bounty signal >= $10 found

## 51. Create Quick Reference Guide

- Decision: drop
- Score: 16 -> -54
- Issue: https://github.com/Soroban-Cookbook/Soroban-Cookbook-/issues/190
- Reason: no clear open paid bounty signal >= $10 found

## 52. [BUG] Cannot purchase API credits - card approved by bank (3DS passed) but Stripe declines

- Decision: drop
- Score: 16 -> -54
- Issue: https://github.com/anthropics/claude-code/issues/45361
- Reason: no clear open paid bounty signal >= $10 found

## 53. [Feature] Global Pro Unlock for users with personal API keys

- Decision: drop
- Score: 16 -> -54
- Issue: https://github.com/SATYAM-PRATIBHAN/arcmindAI/issues/154
- Reason: no clear open paid bounty signal >= $10 found
