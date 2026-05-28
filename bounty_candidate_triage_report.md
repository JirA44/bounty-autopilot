# GitHub Bounty Candidate Triage

Last run: 2026-05-28 11:27 UTC

Kept candidates: 1

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

## 4. Several adapters ship task-template/instruction.md as bare `{problem_statement}` (no task wrapper), causing conversation-style agents to short-circuit

- Decision: drop
- Score: 110 -> 40
- Issue: https://github.com/harbor-framework/harbor/issues/1742
- Reason: no clear open paid bounty signal >= $10 found

## 5. 🎯 Bounty Alert: 13 New Opportunityies found

- Decision: keep
- Score: 104 -> 104
- Issue: https://github.com/dev-kp-eloper/BountyScout/issues/37

## 6. Payment intent accepts non-positive amounts

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/SecureBananaLabs/bug-bounty/issues/1177
- Reason: no clear open paid bounty signal >= $10 found

## 7. [BUG BOUNTY] [High] [eIBC/Fraud] Fulfilled receive orders are not compensated when fraud reverts the packet

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/openmetaearth/me-hub/issues/244
- Reason: no clear open paid bounty signal >= $10 found

## 8. Frontend feature: add mini reward trend cards for overview and profile surfaces

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/theblockcade/stellarcade/issues/829
- Reason: no clear open paid bounty signal >= $10 found

## 9. Contract quest-turnins: add turn-in queue summary and reward-gap accessor

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/theblockcade/stellarcade/issues/817
- Reason: no clear open paid bounty signal >= $10 found

## 10. 📈 گزارش تحلیل فارکس - 2026-05-28

- Decision: drop
- Score: 85 -> -15
- Issue: https://github.com/alicsx/my-news-feed/issues/2845
- Reason: false positive claim/cost/market/manual-access issue, not an open coding bounty

## 11. nus

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/SyedZimraanAli/ZIMI/issues/2
- Reason: no clear open paid bounty signal >= $10 found

## 12. [BUG BOUNTY] [High] [Wasm] EncodeMeMsg Accepts Unvalidated MultiSend Messages From Wasm Contracts

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/openmetaearth/me-hub/issues/246
- Reason: no clear open paid bounty signal >= $10 found

## 13. [BUG BOUNTY] [Critical] [Upgrade] v2.0.13 and v2.0.14 Upgrade Handlers Override fromVM Silently Skipping All Module Migrations

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/openmetaearth/me-hub/issues/245
- Reason: no clear open paid bounty signal >= $10 found

## 14. Arc 3: commit_runtime — filter/leak fixes + 100 verified envs + promote to stable

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/huggingface/Repo2RLEnv/issues/46
- Reason: no clear open paid bounty signal >= $10 found

## 15. [BUG BOUNTY] [Medium] [x/kyc] SetProtocol silently discards Regions field — Get/Set asymmetry enables stale region data

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/openmetaearth/me-hub/issues/243
- Reason: no clear open paid bounty signal >= $10 found

## 16. [BUG BOUNTY] [Medium] [Gravity/grpc_query] ClaimsByEventNonce query has no nil check or nonce validation — unauthenticated store-wide iteration

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/openmetaearth/me-hub/issues/242
- Reason: no clear open paid bounty signal >= $10 found

## 17. [BUG BOUNTY] [High] [Gravity/grpc_query_router] BridgeChainList and LastObservedRelayer hardcode BSC module — multi-chain bridge returns wrong data for all non-BSC chains

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/openmetaearth/me-hub/issues/240
- Reason: no clear open paid bounty signal >= $10 found

## 18. [BUG BOUNTY] [Medium] [x/kyc] GetAllRegions returns corrupted slice with zero-value phantom regions due to make+append bug

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/openmetaearth/me-hub/issues/239
- Reason: no clear open paid bounty signal >= $10 found

## 19. [BUG BOUNTY] [Medium] [Gravity/grpc_query] RelayerSetRequest query panics on nil request — no nil guard before field access

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/openmetaearth/me-hub/issues/238
- Reason: no clear open paid bounty signal >= $10 found

## 20. [BUG BOUNTY] [Medium] [WNFT/grpc_query] NftFilter silently swallows bech32 parse errors for owner address

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/openmetaearth/me-hub/issues/236
- Reason: no clear open paid bounty signal >= $10 found

## 21. [BUG BOUNTY] [Medium] [VFC Hooks] AfterDenomMetadataUpdate is a no-op causing stale VFBC decimals after governance updates

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/openmetaearth/me-hub/issues/234
- Reason: no clear open paid bounty signal >= $10 found

## 22. [BUG BOUNTY] [High] [WNFT/NewClass] Missing ClassId reservation allows front-running kyc SBT class creation

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/openmetaearth/me-hub/issues/233
- Reason: no clear open paid bounty signal >= $10 found

## 23. Economy連携: Vault APIによる勝利報酬システム

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/0x48lab/easy_ctf/issues/26
- Reason: no clear open paid bounty signal >= $10 found

## 24. [BUG BOUNTY] [High] [DAO] MsgUpdateDao Allows Empty DAO Addresses — Permanently Bricks DAO Governance

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/openmetaearth/me-hub/issues/232
- Reason: no clear open paid bounty signal >= $10 found

## 25. [BUG BOUNTY] [Critical] [wgov] v1 Governance MsgServer Registered on QueryServer — MsgSubmitProposal/MsgVote/MsgDeposit Broken via v1 API

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/openmetaearth/me-hub/issues/231
- Reason: no clear open paid bounty signal >= $10 found

## 26. [BUG BOUNTY] [Critical] [wgov] MeTallyResult Query for Active Proposals Permanently Deletes Non-Validator Votes via State-Mutating Read

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/openmetaearth/me-hub/issues/230
- Reason: no clear open paid bounty signal >= $10 found

## 27. [BUG BOUNTY] [Medium] [x/sequencer] SequencersByRollapp gRPC Queries Missing Pagination — Query Node DoS

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/openmetaearth/me-hub/issues/229
- Reason: no clear open paid bounty signal >= $10 found

## 28. [BUG BOUNTY] [High] [x/sequencer] Pending Replace Proposer Not Cleaned Up When Old Sequencer Is Invalid — Permanent DoS

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/openmetaearth/me-hub/issues/228
- Reason: no clear open paid bounty signal >= $10 found

## 29. [BUG BOUNTY] [Critical] [x/sequencer] ReplaceProposer Missing Self-Replacement Validation Causes Permanent Rollapp DoS

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/openmetaearth/me-hub/issues/227
- Reason: no clear open paid bounty signal >= $10 found

## 30. feat(web/logs): add mood log detail view page — full entry with edit and delete actions

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/Echo-Mirror-Butler/Echo-Mirror-Butler-/issues/363
- Reason: no clear open paid bounty signal >= $10 found

## 31. [BUG BOUNTY] [High] [WStaking/IBC] IbcTransferFromRegionTreasure Hardcodes Receiver to Sender — Treasury Funds Sent to Itself on Remote Chain, Irrecoverable

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/openmetaearth/me-hub/issues/220
- Reason: no clear open paid bounty signal >= $10 found

## 32. [BUG BOUNTY] [High] [WStaking] SendToModule Has No Module Name Allowlist — GlobalDao Can Drain Funds to Any Module Account

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/openmetaearth/me-hub/issues/219
- Reason: no clear open paid bounty signal >= $10 found

## 33. [BUG BOUNTY] [Critical] [WStaking/Genesis] InitGenesis Silently Drops UnbondingStakes, Regions, FixedDeposits, and FixedDepositCount — Permanent State Loss on Chain Upgrade

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/openmetaearth/me-hub/issues/218
- Reason: no clear open paid bounty signal >= $10 found

## 34. [Rewards] Rework PowerUp into Heal, RapidFire, and SpeedBoost drops

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/SurpassJY1/GameProgramming/issues/32
- Reason: no clear open paid bounty signal >= $10 found

## 35. Wire qig-warp reverse-tape expectation into live decisions, not passive telemetry

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/GaryOcean428/poloniex-trading-platform/issues/1003
- Reason: no clear open paid bounty signal >= $10 found

## 36. Wire qig-warp reverse-tape expectation into live decisions, not passive telemetry

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/GaryOcean428/poloniex-trading-platform/issues/1002
- Reason: no clear open paid bounty signal >= $10 found

## 37. [Wintergrasp] Getting invited and removed repeatedly (Team assignment bug?)

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/chromiecraft/chromiecraft/issues/9591
- Reason: no clear open paid bounty signal >= $10 found

## 38. [BUG BOUNTY] [Medium] [Ante/MEGroup] Invalid JoinGroup transactions bypass fees via free-gas rule

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/openmetaearth/me-hub/issues/208
- Reason: no clear open paid bounty signal >= $10 found

## 39. [BUG BOUNTY] [Medium] [eIBC] DemandOrdersByStatus panics on invalid denom filter

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/openmetaearth/me-hub/issues/213
- Reason: no clear open paid bounty signal >= $10 found

## 40. Design phase under-describes decisions: prompt/template needs rework for both human + downstream clarity

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/dfrysinger/qrspi-plus/issues/206
- Reason: no clear open paid bounty signal >= $10 found

## 41. obsi: LittleJS port — v1 playable prototype

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/adamico/aijam3/issues/1
- Reason: no clear open paid bounty signal >= $10 found

## 42. [BUG BOUNTY] [High] [DelayedAck] Failed OnRecv packets remain pending and are replayed on finalization

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/openmetaearth/me-hub/issues/197
- Reason: no clear open paid bounty signal >= $10 found

## 43. [BUG BOUNTY] [High] [BridgingFee] Bridge fee pool is blocklisted so rollapp receive fees are silently waived

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/openmetaearth/me-hub/issues/196
- Reason: no clear open paid bounty signal >= $10 found

## 44. [BUG BOUNTY] [High] [RollApp] Frozen EIP155 recovery can be hijacked by any creator

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/openmetaearth/me-hub/issues/194
- Reason: no clear open paid bounty signal >= $10 found

## 45. [BUG BOUNTY] [Medium] [KYC/WStaking] Duplicate invite reward payouts via KYC level cycling

- Decision: drop
- Score: 85 -> -15
- Issue: https://github.com/openmetaearth/me-hub/issues/193
- Reason: issue explicitly indicates no paid bounty or free-only payment status

## 46. Bug: Zod validation errors return 500 Internal Server Error instead of 400 Bad Request

- Decision: drop
- Score: 79 -> -26
- Issue: https://github.com/SecureBananaLabs/bug-bounty/issues/1141
- Reason: no clear open paid bounty signal >= $10 found
- Reason: competition already visible in comments; still allowed in aggressive mode

## 47. OAuth callback accepts unsupported provider names

- Decision: drop
- Score: 79 -> -26
- Issue: https://github.com/SecureBananaLabs/bug-bounty/issues/1133
- Reason: no clear open paid bounty signal >= $10 found
- Reason: competition already visible in comments; still allowed in aggressive mode

## 48. Payment route accepts invalid amounts

- Decision: drop
- Score: 79 -> -26
- Issue: https://github.com/SecureBananaLabs/bug-bounty/issues/1121
- Reason: no clear open paid bounty signal >= $10 found
- Reason: competition already visible in comments; still allowed in aggressive mode

## 49. Refresh qs to patched 6.15.2 for dependency audit

- Decision: drop
- Score: 79 -> -26
- Issue: https://github.com/SecureBananaLabs/bug-bounty/issues/1113
- Reason: no clear open paid bounty signal >= $10 found
- Reason: competition already visible in comments; still allowed in aggressive mode

## 50. JSON body parser errors are reported as internal server errors

- Decision: drop
- Score: 79 -> -26
- Issue: https://github.com/SecureBananaLabs/bug-bounty/issues/1111
- Reason: no clear open paid bounty signal >= $10 found
- Reason: competition already visible in comments; still allowed in aggressive mode

## 51. OAuth callback should reject missing authorization code

- Decision: drop
- Score: 79 -> -26
- Issue: https://github.com/SecureBananaLabs/bug-bounty/issues/1109
- Reason: no clear open paid bounty signal >= $10 found
- Reason: competition already visible in comments; still allowed in aggressive mode

## 52. List services expose mutable in-memory store arrays

- Decision: drop
- Score: 79 -> -26
- Issue: https://github.com/SecureBananaLabs/bug-bounty/issues/1107
- Reason: no clear open paid bounty signal >= $10 found
- Reason: competition already visible in comments; still allowed in aggressive mode

## 53. feat(web): build mood log creation and edit form page

- Decision: drop
- Score: 79 -> 9
- Issue: https://github.com/Echo-Mirror-Butler/Echo-Mirror-Butler-/issues/346
- Reason: no clear open paid bounty signal >= $10 found

## 54. Admin metrics endpoint is exposed without admin role authorization

- Decision: drop
- Score: 79 -> -26
- Issue: https://github.com/SecureBananaLabs/bug-bounty/issues/1102
- Reason: no clear open paid bounty signal >= $10 found
- Reason: competition already visible in comments; still allowed in aggressive mode

## 55. Gamification Ledger Desync & Race Condition Loophole in useAwardXP

- Decision: drop
- Score: 79 -> 9
- Issue: https://github.com/durdana3105/peer-learning/issues/185
- Reason: no clear open paid bounty signal >= $10 found

## 56. Pause Menu — Escape to pause, resume/quit overlay

- Decision: drop
- Score: 75 -> 5
- Issue: https://github.com/cse110-sp24-group24/sp26-cse110-typing-game/issues/50
- Reason: no clear open paid bounty signal >= $10 found

## 57. Questions on backbone choice and future directions (RL + reasoning) of the LocateAnything model

- Decision: drop
- Score: 75 -> 5
- Issue: https://github.com/NVlabs/Eagle/issues/53
- Reason: no clear open paid bounty signal >= $10 found

## 58. Turret ranges are too short (including but not limited to Wintergrasp)

- Decision: drop
- Score: 75 -> 5
- Issue: https://github.com/chromiecraft/chromiecraft/issues/9592
- Reason: no clear open paid bounty signal >= $10 found

## 59. [Quest] - The Missing Diplomat [10/11] sometimes cannot be picked up

- Decision: drop
- Score: 75 -> 5
- Issue: https://github.com/azerothcore/azerothcore-wotlk/issues/26005
- Reason: no clear open paid bounty signal >= $10 found
