# GitHub Bounty Candidate Triage

Last run: 2026-05-28 07:46 UTC

Kept candidates: 6

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

## 4. [BUG BOUNTY] [Medium] [Ante/MEGroup] Invalid JoinGroup transactions bypass fees via free-gas rule

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/openmetaearth/me-hub/issues/208
- Reason: no clear open paid bounty signal >= $10 found

## 5. [BUG BOUNTY] [High] [WNFT] Leading-zero token IDs bypass class total_supply

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/openmetaearth/me-hub/issues/209
- Reason: no clear open paid bounty signal >= $10 found

## 6. [BUG BOUNTY] [Low] [Gravity] BSC USDT/USDC deposits can round down to zero vouchers

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/openmetaearth/me-hub/issues/203
- Reason: no clear open paid bounty signal >= $10 found

## 7. [BUG BOUNTY] [Low] [MEGroup] Nil groupInfo in MsgCreateGroup triggers ValidateBasic panic

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/openmetaearth/me-hub/issues/200
- Reason: no clear open paid bounty signal >= $10 found

## 8. [BUG BOUNTY] [High] [DelayedAck] Failed OnRecv packets remain pending and are replayed on finalization

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/openmetaearth/me-hub/issues/197
- Reason: no clear open paid bounty signal >= $10 found

## 9. [BUG BOUNTY] [High] [BridgingFee] Bridge fee pool is blocklisted so rollapp receive fees are silently waived

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/openmetaearth/me-hub/issues/196
- Reason: no clear open paid bounty signal >= $10 found

## 10. [BUG BOUNTY] [High] [Gravity] Relayer bond power limit uses percent denominator instead of PowerBase

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/openmetaearth/me-hub/issues/186
- Reason: no clear open paid bounty signal >= $10 found

## 11. [BUG BOUNTY] [Medium] [Gravity] Expired outgoing batch can block creation of fresh batches

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/openmetaearth/me-hub/issues/184
- Reason: no clear open paid bounty signal >= $10 found

## 12. [BUG BOUNTY] [High] [RollApp/Fraud] Fraud handling over-reverts pending states and packets before the fraud height

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/openmetaearth/me-hub/issues/183
- Reason: no clear open paid bounty signal >= $10 found

## 13. [BUG BOUNTY] [Medium] [Sequencer] Pending ReplaceProposer allows old proposer to unbond before replacement height

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/openmetaearth/me-hub/issues/174
- Reason: no clear open paid bounty signal >= $10 found

## 14. [BUG BOUNTY] [Medium] [TRON] Address validation accepts non-TRON Base58Check addresses

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/openmetaearth/me-hub/issues/173
- Reason: no clear open paid bounty signal >= $10 found

## 15. [BUG BOUNTY] [Medium] [ante] CheckFunds Skips Fee Validation for Fee Payer in Multi-Sender Transactions — Gas Griefing via Guaranteed-Fail Txs

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/openmetaearth/me-hub/issues/169
- Reason: no clear open paid bounty signal >= $10 found

## 16. [BUG BOUNTY] [High] [wdistri] AllocateBlockReward Int64 Overflow — Silent Reward Corruption for Large Treasury Balances

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/openmetaearth/me-hub/issues/165
- Reason: no clear open paid bounty signal >= $10 found

## 17. [BUG BOUNTY] [Critical] [wgov] Governance Tally Uses Hardcoded Voting Power (1 per Validator) — Stake-Weighted Voting Completely Broken

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/openmetaearth/me-hub/issues/164
- Reason: no clear open paid bounty signal >= $10 found

## 18. [BUG BOUNTY] [High] [wstaking/kyc] TransferKycRegion Double-Counts Delegation on Target Validator -- Accounting Drift Blocks Future Delegations

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/openmetaearth/me-hub/issues/103
- Reason: no clear open paid bounty signal >= $10 found

## 19. [BUG BOUNTY] [Medium] [Gravity] Historical RelayerSetUpdateClaim blocked after relayer unbonds

- Decision: drop
- Score: 79 -> 9
- Issue: https://github.com/openmetaearth/me-hub/issues/212
- Reason: no clear open paid bounty signal >= $10 found

## 20. Size to close is not well formatted, sometimes

- Decision: keep
- Score: 71 -> 36
- Issue: https://github.com/capofficial/client/issues/11
- Reason: competition already visible in comments; still allowed in aggressive mode

## 21. More thorough benchmarks [$200]

- Decision: keep
- Score: 71 -> 36
- Issue: https://github.com/QuantumSavory/QuantumSavory.jl/issues/131
- Reason: competition already visible in comments; still allowed in aggressive mode

## 22. Add `GET /api/bounties/:id/events` paginated history endpoint

- Decision: drop
- Score: 64 -> -41
- Issue: https://github.com/ritik4ever/stellar-bounty-board/issues/249
- Reason: no clear open paid bounty signal >= $10 found
- Reason: competition already visible in comments; still allowed in aggressive mode

## 23. Add `autocannon` load test script for the bounty board backend

- Decision: drop
- Score: 64 -> -6
- Issue: https://github.com/ritik4ever/stellar-bounty-board/issues/385
- Reason: no clear open paid bounty signal >= $10 found

## 24. Publish Docker images to GHCR on merge to main

- Decision: drop
- Score: 64 -> -6
- Issue: https://github.com/ritik4ever/stellar-bounty-board/issues/320
- Reason: no clear open paid bounty signal >= $10 found

## 25. [BOUNTY: 5 RTC] wRTC Bridge vs Cross-Chain DEX Architecture Comparison

- Decision: drop
- Score: 61 -> -9
- Issue: https://github.com/Scottcjn/rustchain-bounties/issues/12443
- Reason: no clear open paid bounty signal >= $10 found

## 26. [BOUNTY: 5 RTC] Proof of Antiquity vs Proof of Storage (Filecoin/Chia/Arweave)

- Decision: drop
- Score: 61 -> -9
- Issue: https://github.com/Scottcjn/rustchain-bounties/issues/12444
- Reason: no clear open paid bounty signal >= $10 found

## 27. Rust Component Definition Support $500

- Decision: keep
- Score: 61 -> 26
- Issue: https://github.com/Spectral-Finance/lux/issues/103
- Reason: competition already visible in comments; still allowed in aggressive mode

## 28. [BOUNTY: 5 RTC] RustChain vs Helium / DePIN Networks Comparison

- Decision: drop
- Score: 61 -> -9
- Issue: https://github.com/Scottcjn/rustchain-bounties/issues/12442
- Reason: no clear open paid bounty signal >= $10 found

## 29. [200 MRG] Fix logout bug

- Decision: drop
- Score: 56 -> -49
- Issue: https://github.com/mergeos-bounties/mergeos/issues/20
- Reason: no clear open paid bounty signal >= $10 found
- Reason: competition already visible in comments; still allowed in aggressive mode

## 30. Introducing Haveno2Dart: A Native Dart/Flutter Port of haveno-ts with Tor SOCKS5 Support

- Decision: drop
- Score: 47 -> -23
- Issue: https://github.com/haveno-dex/haveno-ts/issues/436
- Reason: no clear open paid bounty signal >= $10 found

## 31. 🌐 Invitation: Deploy your NanoSwarm agents on Nautilus — A2A hosting platform with economic infrastructure

- Decision: drop
- Score: 47 -> -53
- Issue: https://github.com/Mahopanda/NanoSwarm/issues/1
- Reason: false positive claim/cost/market/manual-access issue, not an open coding bounty

## 32. Bugfix Rewards Program Submission

- Decision: drop
- Score: 46 -> -24
- Issue: https://github.com/FreeCAD/FPA/issues/470
- Reason: no clear open paid bounty signal >= $10 found

## 33. [FEAT] No leaderboard for bounty claimants

- Decision: drop
- Score: 46 -> -59
- Issue: https://github.com/Scottcjn/rustchain-bounties/issues/3092
- Reason: no clear open paid bounty signal >= $10 found
- Reason: competition already visible in comments; still allowed in aggressive mode

## 34. Clarify scope and acceptance criteria for Dart port bounty

- Decision: drop
- Score: 43 -> -27
- Issue: https://github.com/haveno-dex/haveno-ts/issues/435
- Reason: no clear open paid bounty signal >= $10 found

## 35. Android app crashes when camera is open for >10 minutes

- Decision: drop
- Score: 41 -> -64
- Issue: https://github.com/mrousavy/vision-camera-resize-plugin/issues/73
- Reason: no clear open paid bounty signal >= $10 found
- Reason: competition already visible in comments; still allowed in aggressive mode

## 36. [Feature] Add Integrity Verification (Hash of Executable/Script)

- Decision: keep
- Score: 40 -> 5
- Issue: https://github.com/javelin-anticheat/py-workedtask/issues/4
- Reason: competition already visible in comments; still allowed in aggressive mode

## 37. task: Comm Guide: Parking Lots vs Downtown Density

- Decision: drop
- Score: 39 -> -31
- Issue: https://github.com/all-aboard-ohio/communication-guides/issues/8
- Reason: no clear open paid bounty signal >= $10 found

## 38. task: Comm Guide - How to Create Compelling Case Studies

- Decision: drop
- Score: 39 -> -31
- Issue: https://github.com/all-aboard-ohio/communication-guides/issues/7
- Reason: no clear open paid bounty signal >= $10 found

## 39. [EASY BOUNTY: 2 RTC] Leave an Honest Review of BoTTube on ToolPilot.ai

- Decision: drop
- Score: 36 -> -34
- Issue: https://github.com/Scottcjn/rustchain-bounties/issues/2155
- Reason: no clear open paid bounty signal >= $10 found

## 40. Whitespace is allowed within Header names, should be an Invalid header

- Decision: keep
- Score: 36 -> 1
- Issue: https://github.com/urllib3/urllib3/issues/1362
- Reason: competition already visible in comments; still allowed in aggressive mode

## 41. Implement a fully functional Admin Panel

- Decision: keep
- Score: 36 -> 1
- Issue: https://github.com/SecureBananaLabs/bug-bounty/issues/29
- Reason: competition already visible in comments; still allowed in aggressive mode

## 42. Feature Request: Copy rule(s) to Private Workspace

- Decision: keep
- Score: 30 -> -5
- Issue: https://github.com/requestly/requestly/issues/3825
- Reason: competition already visible in comments; still allowed in aggressive mode

## 43. Implement trace thickness as a parameter

- Decision: keep
- Score: 26 -> -9
- Issue: https://github.com/tscircuit/tscircuit-autorouter/issues/66
- Reason: competition already visible in comments; still allowed in aggressive mode

## 44. Claim MRG Tokens for Bug Bounty Reports - Comment New Bugs Here Before Opening a PR

- Decision: drop
- Score: 21 -> -84
- Issue: https://github.com/mergeos-bounties/mergeos/issues/1
- Reason: no clear open paid bounty signal >= $10 found
- Reason: competition already visible in comments; still allowed in aggressive mode

## 45. AI-Powered Research Assistant Suite

- Decision: drop
- Score: 11 -> -94
- Issue: https://github.com/SCIBASE-AI/SCIBASE.AI/issues/16
- Reason: no clear open paid bounty signal >= $10 found
- Reason: competition already visible in comments; still allowed in aggressive mode

## 46. Add a README badge and contribution guide to agent-browser

- Decision: drop
- Score: 11 -> -94
- Issue: https://github.com/dextonai/agent-browser/issues/1
- Reason: no clear open paid bounty signal >= $10 found
- Reason: competition already visible in comments; still allowed in aggressive mode

## 47. Support / add `proxy-server` input mode to fuzz / run checks on live traffic

- Decision: drop
- Score: 8 -> -62
- Issue: https://github.com/projectdiscovery/nuclei/issues/4953
- Reason: no clear open paid bounty signal >= $10 found

## 48. Typos and small errors in "The Collections Framework" tutorials ( https://dev.java/learn/api/collections-framework/ )

- Decision: drop
- Score: 6 -> -99
- Issue: https://github.com/java/devjava-content/issues/206
- Reason: no clear open paid bounty signal >= $10 found
- Reason: competition already visible in comments; still allowed in aggressive mode
