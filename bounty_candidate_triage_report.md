# GitHub Bounty Candidate Triage

Last run: 2026-05-25 18:00 UTC

Kept candidates: 0

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

## 4. Trading-desk: add Massive.com as a market-data provider (rate-capped free tier)

- Decision: drop
- Score: 104 -> 4
- Issue: https://github.com/fixpoint-labs/flow-state-dev/issues/328
- Reason: false positive claim/cost/market/manual-access issue, not an open coding bounty

## 5. Free Lead Follow-Up Answers for missed calls, quiet estimates, no-shows, and price objections

- Decision: drop
- Score: 96 -> 26
- Issue: https://github.com/trungcodeer/softjunk-lead-kit/issues/2
- Reason: no clear open paid bounty signal >= $10 found

## 6. availability: getSlotAllocationManifest omits 'awaiting_payment' bookings — travelers vanish from the slot allocation page

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/voyantjs/voyant/issues/1280
- Reason: no clear open paid bounty signal >= $10 found

## 7. Server-side cursor + per-row commit fails under PgBouncer txn pooling (expire_subscriptions_past_grace + latent close_polls_due → InvalidCursorName)

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/letsrevel/revel-backend/issues/458
- Reason: no clear open paid bounty signal >= $10 found

## 8. Unit color variations dead-end at Stoic Studio's defunct store

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/Banner-Saga-Factions/BSF-Custom-Server/issues/98
- Reason: no clear open paid bounty signal >= $10 found

## 9. P1.11 Prompt asks LLM for fields the parser discards (cost, reversibility)

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/jayzalowitz/skytwin/issues/411
- Reason: no clear open paid bounty signal >= $10 found

## 10. P1.10 README version badge is 35 releases stale

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/jayzalowitz/skytwin/issues/380
- Reason: no clear open paid bounty signal >= $10 found

## 11. ESM Plus PR #204 follow-up — 운영 cycle 미연동 3영역 + client URL/파라미터 버그 3종 + 응답 키 매핑 + 이미지 reject + isSell 누락

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/sbk0674-web/samba-wave/issues/242
- Reason: no clear open paid bounty signal >= $10 found

## 12. Schema: uniqueness key on subscription_cycles (subscription_id, signal_type, next_renewal_at)

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/udog21/subsounder/issues/42
- Reason: no clear open paid bounty signal >= $10 found

## 13. Ingestion: skip SubSounder-generated mail to prevent self-loop ingestion

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/udog21/subsounder/issues/40
- Reason: no clear open paid bounty signal >= $10 found

## 14. Reviewer: emit machine-readable header in review comments — let coordinator/TUI parse verdict without ingesting prose

- Decision: drop
- Score: 85 -> -15
- Issue: https://github.com/JDonaghy/claude-coordinator/issues/248
- Reason: false positive claim/cost/market/manual-access issue, not an open coding bounty

## 15. feat: edit payment method / tender after bill is settled

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/lidiapierre/ikitchen-pos/issues/459
- Reason: no clear open paid bounty signal >= $10 found

## 16. Prevent withdraw from refunding an Active vault that already had funds slashed in accountability_vault

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/Disciplr-Org/Disciplr-backend/issues/366
- Reason: no clear open paid bounty signal >= $10 found

## 17. Express checkout (confirmation token) orders don't store the charge ID as `_transaction_id`, breaking refunds

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/woocommerce/woocommerce-gateway-stripe/issues/5480
- Reason: no clear open paid bounty signal >= $10 found

## 18. Reclaim UI hardcodes vout=0 in getEmilyDepositInfo — deposits at a non-zero output index (e.g. PoX-4 reward payouts) can't be reclaimed

- Decision: drop
- Score: 79 -> 9
- Issue: https://github.com/stacks-sbtc/sbtc-bridge/issues/259
- Reason: no clear open paid bounty signal >= $10 found

## 19. Epic: Manual + agent-driveable QA corpus (Test Plans + Exploratory Charters)

- Decision: drop
- Score: 71 -> -29
- Issue: https://github.com/dsj1984/athportal/issues/775
- Reason: false positive claim/cost/market/manual-access issue, not an open coding bounty

## 20. [post] Crypto promised to break the banks open, to let the kasi accounts...

- Decision: drop
- Score: 69 -> -1
- Issue: https://github.com/proxima424/westworld/issues/2585
- Reason: no clear open paid bounty signal >= $10 found

## 21. Backend/AI: Prevent Groq API Abuse by Disallowing Empty Interview Completions

- Decision: drop
- Score: 64 -> -36
- Issue: https://github.com/anurag3407/career-pilot/issues/1693
- Reason: false positive claim/cost/market/manual-access issue, not an open coding bounty

## 22. Microgrant Proposal: Field verified OpenStreetMap data

- Decision: drop
- Score: 63 -> -37
- Issue: https://github.com/osmfoundation/ewg_bidding/issues/24
- Reason: false positive claim/cost/market/manual-access issue, not an open coding bounty

## 23. hindsight per-project-tagged scoping fragments memory across git worktrees

- Decision: drop
- Score: 56 -> -44
- Issue: https://github.com/can1357/oh-my-pi/issues/1217
- Reason: false positive claim/cost/market/manual-access issue, not an open coding bounty

## 24. WaterwayMap.org hosting costs

- Decision: drop
- Score: 54 -> -46
- Issue: https://github.com/osmfoundation/ewg_bidding/issues/45
- Reason: false positive claim/cost/market/manual-access issue, not an open coding bounty

## 25. Microgrant Proposal: OSMAutoDrone

- Decision: drop
- Score: 54 -> -46
- Issue: https://github.com/osmfoundation/ewg_bidding/issues/39
- Reason: issue explicitly indicates no paid bounty or free-only payment status

## 26. MICROGRANT PROPOSAL:OSM-BASED DASHBOARD FOR CLIMATE CHANGE MONITORING IN AFRICA

- Decision: drop
- Score: 54 -> -16
- Issue: https://github.com/osmfoundation/ewg_bidding/issues/22
- Reason: no clear open paid bounty signal >= $10 found

## 27. Microgrant Proposal: Enhancing Drone Tasking Manager for Multi-Drone Support and Operational Refinements

- Decision: drop
- Score: 54 -> -46
- Issue: https://github.com/osmfoundation/ewg_bidding/issues/28
- Reason: false positive claim/cost/market/manual-access issue, not an open coding bounty

## 28. MicroGrant Proposal : OSMSG

- Decision: drop
- Score: 54 -> -16
- Issue: https://github.com/osmfoundation/ewg_bidding/issues/30
- Reason: no clear open paid bounty signal >= $10 found

## 29. MIcrogrant Proposal: OSMLocalizer

- Decision: drop
- Score: 54 -> -46
- Issue: https://github.com/osmfoundation/ewg_bidding/issues/29
- Reason: false positive claim/cost/market/manual-access issue, not an open coding bounty

## 30. Microgrant Proposal: OpenStreetMap Before-After Maps Generator

- Decision: drop
- Score: 54 -> -16
- Issue: https://github.com/osmfoundation/ewg_bidding/issues/27
- Reason: no clear open paid bounty signal >= $10 found

## 31. [CODE] [SDK] from @unknown-bot (stake: 1)

- Decision: drop
- Score: 49 -> -21
- Issue: https://github.com/RBKunnela/paybot-sdk/issues/2
- Reason: no clear open paid bounty signal >= $10 found

## 32. Microgrant Proposal: Map Review Team

- Decision: drop
- Score: 48 -> -22
- Issue: https://github.com/osmfoundation/ewg_bidding/issues/46
- Reason: no clear open paid bounty signal >= $10 found

## 33. Microgrant Proposal: GeoAI for Maternal Health Risk Mapping in Kenya

- Decision: drop
- Score: 48 -> -22
- Issue: https://github.com/osmfoundation/ewg_bidding/issues/43
- Reason: no clear open paid bounty signal >= $10 found

## 34. Microgrant Proposal: Campus Guide

- Decision: drop
- Score: 48 -> -22
- Issue: https://github.com/osmfoundation/ewg_bidding/issues/23
- Reason: no clear open paid bounty signal >= $10 found

## 35. Draft: MIcrogrant Proposal- OSMLocalizer

- Decision: drop
- Score: 48 -> -52
- Issue: https://github.com/osgeonepal/site/issues/74
- Reason: false positive claim/cost/market/manual-access issue, not an open coding bounty

## 36. Add response `gzip` compression to Express

- Decision: drop
- Score: 47 -> -23
- Issue: https://github.com/ritik4ever/stellar-bounty-board/issues/356
- Reason: no clear open paid bounty signal >= $10 found

## 37. Cache bounty list in-memory with 5-second TTL in backend

- Decision: drop
- Score: 47 -> -23
- Issue: https://github.com/ritik4ever/stellar-bounty-board/issues/355
- Reason: no clear open paid bounty signal >= $10 found

## 38. [Ops] Implement pre-launch readiness gate, soft-launch control, and Admin Go/No-Go dashboard

- Decision: drop
- Score: 46 -> -24
- Issue: https://github.com/smallwei0301/tour-platform/issues/320
- Reason: no clear open paid bounty signal >= $10 found

## 39. Insulation as Infrastructure: supporting “Dobra Maisternia” in frontline Kharkiv region

- Decision: drop
- Score: 44 -> -26
- Issue: https://github.com/maxzalevski/community_spaces/issues/7
- Reason: no clear open paid bounty signal >= $10 found

## 40. W3I Network Initiative in Action: Building a Sarafu-Based DAO for Regenerative Coordination in Ukraine

- Decision: drop
- Score: 44 -> -26
- Issue: https://github.com/maxzalevski/grants/issues/2
- Reason: no clear open paid bounty signal >= $10 found

## 41. Radaria three bunk beds in hostel

- Decision: drop
- Score: 44 -> -26
- Issue: https://github.com/maxzalevski/community_spaces/issues/6
- Reason: no clear open paid bounty signal >= $10 found

## 42. Add policies / visa letter page

- Decision: drop
- Score: 44 -> -26
- Issue: https://github.com/open-life-science/open-life-science.github.io/issues/1108
- Reason: no clear open paid bounty signal >= $10 found

## 43. Meeting [2025-06-06]

- Decision: drop
- Score: 44 -> -26
- Issue: https://github.com/osgeonepal/site/issues/73
- Reason: no clear open paid bounty signal >= $10 found

## 44. Missing validate_shape() in no-cranker liquidation path allows cross-domain insurance reservation invariant violation

- Decision: drop
- Score: 43 -> -27
- Issue: https://github.com/aeyakovenko/percolator-cli/issues/73
- Reason: no clear open paid bounty signal >= $10 found

## 45. Bounty-5: Phantom Fee Attack — Domain Budget Inflation via Discarded Fee Return Values

- Decision: drop
- Score: 43 -> -27
- Issue: https://github.com/aeyakovenko/percolator/issues/63
- Reason: no clear open paid bounty signal >= $10 found

## 46. Add `IntersectionObserver` infinite scroll for the bounty list

- Decision: drop
- Score: 43 -> -27
- Issue: https://github.com/ritik4ever/stellar-bounty-board/issues/307
- Reason: no clear open paid bounty signal >= $10 found

## 47. Add `CopyIcons` button to copy bounty ID and maintainer address

- Decision: drop
- Score: 43 -> -27
- Issue: https://github.com/ritik4ever/stellar-bounty-board/issues/295
- Reason: no clear open paid bounty signal >= $10 found

## 48. Bounty: ⚡️TurboETH Template - 500 OP Reward

- Decision: drop
- Score: 42 -> -93
- Issue: https://github.com/turbo-eth/template-web3-app/issues/29
- Reason: false positive claim/cost/market/manual-access issue, not an open coding bounty
- Reason: competition already visible in comments; still allowed in aggressive mode

## 49. P0: Bypass RL runtime-parameter consumer for direct consumption evidence

- Decision: drop
- Score: 41 -> -29
- Issue: https://github.com/lanyusea/screeps/issues/1431
- Reason: no clear open paid bounty signal >= $10 found

## 50. Microgrant Proposal: Redesign of the OSM Apps Catalog to reach a wider audience

- Decision: drop
- Score: 40 -> -60
- Issue: https://github.com/osmfoundation/ewg_bidding/issues/31
- Reason: false positive claim/cost/market/manual-access issue, not an open coding bounty

## 51. Set of issues for resolution under the MICROGRANT Program 2026-05

- Decision: drop
- Score: 40 -> -65
- Issue: https://github.com/asyncapi/cli/issues/2124
- Reason: no clear open paid bounty signal >= $10 found
- Reason: competition already visible in comments; still allowed in aggressive mode

## 52. PauseAI.se takes up first place in google

- Decision: drop
- Score: 40 -> -30
- Issue: https://github.com/PauseAI/pauseai-website/issues/385
- Reason: no clear open paid bounty signal >= $10 found

## 53. Microgrant Proposal: StreetComplete as an entry point to OpenStreetMap

- Decision: drop
- Score: 40 -> -65
- Issue: https://github.com/osmfoundation/ewg_bidding/issues/34
- Reason: no clear open paid bounty signal >= $10 found
- Reason: competition already visible in comments; still allowed in aggressive mode

## 54. Microgrant Proposal: Underpass stabilization, packaging and testing

- Decision: drop
- Score: 40 -> -30
- Issue: https://github.com/osmfoundation/ewg_bidding/issues/42
- Reason: no clear open paid bounty signal >= $10 found

## 55. Microgrant Proposal: Localized Open Geocoder Plugin for Ethiopia and Africa

- Decision: drop
- Score: 40 -> -30
- Issue: https://github.com/osmfoundation/ewg_bidding/issues/21
- Reason: no clear open paid bounty signal >= $10 found

## 56. Microgrant Proposal: AI-Based Feature Extraction from Satellite Imagery for OpenStreetMap (OSM) Enrichment

- Decision: drop
- Score: 40 -> -60
- Issue: https://github.com/osmfoundation/ewg_bidding/issues/38
- Reason: false positive claim/cost/market/manual-access issue, not an open coding bounty
