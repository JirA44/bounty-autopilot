# GitHub Bounty Candidate Triage

Last run: 2026-05-28 12:56 UTC

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

## 4. 🎯 Bounty Alert: 6 New Opportunityies found

- Decision: keep
- Score: 98 -> 98
- Issue: https://github.com/dev-kp-eloper/BountyScout/issues/33

## 5. [BUG BOUNTY] [High] [Gravity/grpc_query_router] BridgeChainList and LastObservedRelayer hardcode BSC module — multi-chain bridge returns wrong data for all non-BSC chains

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/openmetaearth/me-hub/issues/240
- Reason: no clear open paid bounty signal >= $10 found

## 6. [BUG BOUNTY] [Medium] [WNFT/grpc_query] NftFilter silently swallows bech32 parse errors for owner address

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/openmetaearth/me-hub/issues/236
- Reason: no clear open paid bounty signal >= $10 found

## 7. [BUG BOUNTY] [Critical] [wgov] v1 Governance MsgServer Registered on QueryServer — MsgSubmitProposal/MsgVote/MsgDeposit Broken via v1 API

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/openmetaearth/me-hub/issues/231
- Reason: no clear open paid bounty signal >= $10 found

## 8. [FEATURE] Improve Landing Page Design for Better Medical UI/UX

- Decision: drop
- Score: 71 -> -34
- Issue: https://github.com/RatLoopz/sahidawa-india/issues/793
- Reason: no clear open paid bounty signal >= $10 found
- Reason: competition already visible in comments; still allowed in aggressive mode

## 9. More thorough benchmarks [$200]

- Decision: keep
- Score: 71 -> 36
- Issue: https://github.com/QuantumSavory/QuantumSavory.jl/issues/131
- Reason: competition already visible in comments; still allowed in aggressive mode

## 10. [Bug]: BUG BOUNTY

- Decision: drop
- Score: 65 -> -40
- Issue: https://github.com/openmetaearth/me-hub/issues/108
- Reason: no clear open paid bounty signal >= $10 found
- Reason: competition already visible in comments; still allowed in aggressive mode

## 11. Add Mermaid sequence diagram for the full bounty lifecycle

- Decision: drop
- Score: 64 -> -41
- Issue: https://github.com/ritik4ever/stellar-bounty-board/issues/337
- Reason: no clear open paid bounty signal >= $10 found
- Reason: competition already visible in comments; still allowed in aggressive mode

## 12. [FEATURE] Build Medicine Photo Upload Component using Cloudinary Media API

- Decision: drop
- Score: 64 -> -6
- Issue: https://github.com/RatLoopz/sahidawa-india/issues/424
- Reason: no clear open paid bounty signal >= $10 found

## 13. Add `frontend` Vitest coverage threshold enforcement

- Decision: drop
- Score: 64 -> -41
- Issue: https://github.com/ritik4ever/stellar-bounty-board/issues/380
- Reason: no clear open paid bounty signal >= $10 found
- Reason: competition already visible in comments; still allowed in aggressive mode

## 14. Add `autocannon` load test script for the bounty board backend

- Decision: drop
- Score: 64 -> -6
- Issue: https://github.com/ritik4ever/stellar-bounty-board/issues/385
- Reason: no clear open paid bounty signal >= $10 found

## 15. Publish Docker images to GHCR on merge to main

- Decision: drop
- Score: 64 -> -6
- Issue: https://github.com/ritik4ever/stellar-bounty-board/issues/320
- Reason: no clear open paid bounty signal >= $10 found

## 16. [2000 MRG] Fix dashboard layout after login

- Decision: drop
- Score: 64 -> -41
- Issue: https://github.com/mergeos-bounties/mergeos/issues/16
- Reason: no clear open paid bounty signal >= $10 found
- Reason: competition already visible in comments; still allowed in aggressive mode

## 17. Smart Contract Event Monitoring System $1,500

- Decision: keep
- Score: 61 -> 26
- Issue: https://github.com/Spectral-Finance/lux/issues/75
- Reason: competition already visible in comments; still allowed in aggressive mode

## 18. LLM Provider Abstraction Layer $600

- Decision: keep
- Score: 61 -> 26
- Issue: https://github.com/Spectral-Finance/lux/issues/99
- Reason: competition already visible in comments; still allowed in aggressive mode

## 19. Add `UsdAmount` conversion using live XLM/USD price feed

- Decision: drop
- Score: 58 -> -122
- Issue: https://github.com/ritik4ever/stellar-bounty-board/issues/288
- Reason: false positive claim/cost/market/manual-access issue, not an open coding bounty
- Reason: light competition allowed: 3 open competing PR(s)
- Reason: competition already visible in comments; still allowed in aggressive mode
- Competing PR: https://github.com/ritik4ever/stellar-bounty-board/pull/430
- Competing PR: https://github.com/ritik4ever/stellar-bounty-board/pull/462
- Competing PR: https://github.com/ritik4ever/stellar-bounty-board/pull/398

## 20. Add `multi_token_release` support — allow different tokens per bounty

- Decision: drop
- Score: 58 -> -42
- Issue: https://github.com/ritik4ever/stellar-bounty-board/issues/223
- Reason: no clear open paid bounty signal >= $10 found
- Reason: light competition allowed: 2 open competing PR(s)
- Competing PR: https://github.com/ritik4ever/stellar-bounty-board/pull/461
- Competing PR: https://github.com/ritik4ever/stellar-bounty-board/pull/409

## 21. Add `usePolling` hook for live bounty status updates

- Decision: drop
- Score: 58 -> -77
- Issue: https://github.com/ritik4ever/stellar-bounty-board/issues/374
- Reason: no clear open paid bounty signal >= $10 found
- Reason: light competition allowed: 2 open competing PR(s)
- Reason: competition already visible in comments; still allowed in aggressive mode
- Competing PR: https://github.com/ritik4ever/stellar-bounty-board/pull/460
- Competing PR: https://github.com/ritik4ever/stellar-bounty-board/pull/390

## 22. [500 MRG] Test and fix login/logout modal responsive behavior

- Decision: drop
- Score: 56 -> -49
- Issue: https://github.com/mergeos-bounties/mergeos/issues/13
- Reason: no clear open paid bounty signal >= $10 found
- Reason: competition already visible in comments; still allowed in aggressive mode

## 23. Implement the Request Revisions flow on the submission approval panel

- Decision: drop
- Score: 56 -> -49
- Issue: https://github.com/boundlessfi/bounties/issues/202
- Reason: no clear open paid bounty signal >= $10 found
- Reason: competition already visible in comments; still allowed in aggressive mode

## 24. test : add unit tests for auto_close_service.py utility

- Decision: drop
- Score: 56 -> -154
- Issue: https://github.com/ritesh-1918/HELPDESK.AI/issues/279
- Reason: no clear open paid bounty signal >= $10 found
- Reason: light competition allowed: 7 open competing PR(s)
- Reason: competition already visible in comments; still allowed in aggressive mode
- Competing PR: https://github.com/ritesh-1918/HELPDESK.AI/pull/416
- Competing PR: https://github.com/ritesh-1918/HELPDESK.AI/pull/372
- Competing PR: https://github.com/ritesh-1918/HELPDESK.AI/pull/422
- Competing PR: https://github.com/ritesh-1918/HELPDESK.AI/pull/408
- Competing PR: https://github.com/ritesh-1918/HELPDESK.AI/pull/415

## 25. Implement the maintainer dashboard actions for Multi-Winner Milestone bounties

- Decision: drop
- Score: 56 -> -49
- Issue: https://github.com/boundlessfi/bounties/issues/205
- Reason: no clear open paid bounty signal >= $10 found
- Reason: competition already visible in comments; still allowed in aggressive mode

## 26. Implement the Decline applicant flow on the application review dashboard

- Decision: drop
- Score: 56 -> -49
- Issue: https://github.com/boundlessfi/bounties/issues/208
- Reason: no clear open paid bounty signal >= $10 found
- Reason: competition already visible in comments; still allowed in aggressive mode

## 27. [FEATURE] <Brief description>Implementing Dynamic Hero Section

- Decision: drop
- Score: 56 -> -14
- Issue: https://github.com/RatLoopz/sahidawa-india/issues/519
- Reason: no clear open paid bounty signal >= $10 found

## 28. [1500 MRG] AI project evaluation for price suggestion

- Decision: drop
- Score: 56 -> -49
- Issue: https://github.com/mergeos-bounties/mergeos/issues/3
- Reason: no clear open paid bounty signal >= $10 found
- Reason: competition already visible in comments; still allowed in aggressive mode

## 29. Add `dark mode` toggle with localStorage persistence

- Decision: drop
- Score: 56 -> -14
- Issue: https://github.com/ritik4ever/stellar-bounty-board/issues/298
- Reason: no clear open paid bounty signal >= $10 found

## 30. [2000 MRG] Fix project view after login from dashboard

- Decision: drop
- Score: 56 -> -14
- Issue: https://github.com/mergeos-bounties/mergeos/issues/17
- Reason: no clear open paid bounty signal >= $10 found

## 31. [200 MRG] Fix logout bug

- Decision: drop
- Score: 56 -> -49
- Issue: https://github.com/mergeos-bounties/mergeos/issues/20
- Reason: no clear open paid bounty signal >= $10 found
- Reason: competition already visible in comments; still allowed in aggressive mode

## 32. [FEATURE] Medicine Batch Number Traceability with Manufacturer Details & Contact

- Decision: drop
- Score: 54 -> -46
- Issue: https://github.com/RatLoopz/sahidawa-india/issues/308
- Reason: false positive claim/cost/market/manual-access issue, not an open coding bounty

## 33. feat: create temperature-alert skill template

- Decision: drop
- Score: 54 -> -51
- Issue: https://github.com/Clawland-AI/clawland-skills/issues/1
- Reason: no clear open paid bounty signal >= $10 found
- Reason: competition already visible in comments; still allowed in aggressive mode

## 34. [1500 MRG] Live project creation updates on dashboard and homepage via WebSocket

- Decision: drop
- Score: 50 -> -55
- Issue: https://github.com/mergeos-bounties/mergeos/issues/21
- Reason: no clear open paid bounty signal >= $10 found
- Reason: competition already visible in comments; still allowed in aggressive mode

## 35. [3000 MRG] Implement public and logged-in notifications

- Decision: drop
- Score: 50 -> -20
- Issue: https://github.com/mergeos-bounties/mergeos/issues/19
- Reason: no clear open paid bounty signal >= $10 found

## 36. Add Sorting Hat MCP server with Patronus-based tool authorization and Quidditch-style streaming UI

- Decision: keep
- Score: 50 -> 15
- Issue: https://github.com/archestra-ai/archestra/issues/4998
- Reason: competition already visible in comments; still allowed in aggressive mode

## 37. [WIKI-DESIGN] Souled-universe consolidation program — finish the substrate's half-built universe/soul/permission surfaces into one finite domain-neutral architecture

- Decision: drop
- Score: 50 -> -50
- Issue: https://github.com/Jonnyton/Workflow/issues/1090
- Reason: false positive claim/cost/market/manual-access issue, not an open coding bounty

## 38. Add Responsive Scroll-to-Top Utility for Improved Page Navigation Experience

- Decision: drop
- Score: 48 -> -22
- Issue: https://github.com/RatLoopz/sahidawa-india/issues/363
- Reason: no clear open paid bounty signal >= $10 found

## 39. bounties

- Decision: drop
- Score: 47 -> -23
- Issue: https://github.com/PatMyron/.github/issues/1
- Reason: no clear open paid bounty signal >= $10 found

## 40. Introducing Haveno2Dart: A Native Dart/Flutter Port of haveno-ts with Tor SOCKS5 Support

- Decision: drop
- Score: 47 -> -23
- Issue: https://github.com/haveno-dex/haveno-ts/issues/436
- Reason: no clear open paid bounty signal >= $10 found

## 41. Feature: Notification Center

- Decision: drop
- Score: 46 -> -59
- Issue: https://github.com/boundlessfi/bounties/issues/182
- Reason: no clear open paid bounty signal >= $10 found
- Reason: competition already visible in comments; still allowed in aggressive mode

## 42. Clarify scope and acceptance criteria for Dart port bounty

- Decision: drop
- Score: 43 -> -27
- Issue: https://github.com/haveno-dex/haveno-ts/issues/435
- Reason: no clear open paid bounty signal >= $10 found

## 43. [WIKI-PATCH] Add plan-level approvals, scoped trust sessions, and batch receipts for fast online Branch authoring

- Decision: drop
- Score: 40 -> -95
- Issue: https://github.com/Jonnyton/Workflow/issues/961
- Reason: issue explicitly indicates no paid bounty or free-only payment status
- Reason: competition already visible in comments; still allowed in aggressive mode

## 44. [Backend-express] Feature: Real Nearby Pharmacy Search using Supabase + PostGIS

- Decision: drop
- Score: 40 -> -30
- Issue: https://github.com/RatLoopz/sahidawa-india/issues/171
- Reason: no clear open paid bounty signal >= $10 found

## 45. Add internationalization (i18n) support

- Decision: drop
- Score: 40 -> -65
- Issue: https://github.com/sorosave-protocol/frontend/issues/16
- Reason: no clear open paid bounty signal >= $10 found
- Reason: competition already visible in comments; still allowed in aggressive mode

## 46. [Blueprint] Strange scroll bar

- Decision: drop
- Score: 40 -> -65
- Issue: https://github.com/stakwork/sphinx-nav-fiber/issues/2315
- Reason: no clear open paid bounty signal >= $10 found
- Reason: competition already visible in comments; still allowed in aggressive mode

## 47. Create wallet benchmarks

- Decision: drop
- Score: 38 -> -67
- Issue: https://github.com/tari-project/wallet-benchmarks/issues/1
- Reason: no clear open paid bounty signal >= $10 found
- Reason: competition already visible in comments; still allowed in aggressive mode

## 48. 🚀 WebGPU Backend Implementation for LLGI ($2000 Bounty)

- Decision: keep
- Score: 36 -> 1
- Issue: https://github.com/effekseer/EffekseerForWebGL/issues/113
- Reason: competition already visible in comments; still allowed in aggressive mode

## 49. Timeline - Create new Tracks and Clips

- Decision: drop
- Score: 36 -> -69
- Issue: https://github.com/jbilcke-hf/clapper/issues/10
- Reason: no clear open paid bounty signal >= $10 found
- Reason: competition already visible in comments; still allowed in aggressive mode

## 50. Add `GET /api/open-issues` caching and GitHub API rate-limit handling

- Decision: drop
- Score: 34 -> -71
- Issue: https://github.com/ritik4ever/stellar-bounty-board/issues/365
- Reason: no clear open paid bounty signal >= $10 found
- Reason: competition already visible in comments; still allowed in aggressive mode

## 51. [BOUNTY: 2 RTC each] Upvote Elyan Labs Skills on ClawHub (5 skills)

- Decision: drop
- Score: 30 -> -40
- Issue: https://github.com/Scottcjn/rustchain-bounties/issues/2571
- Reason: no clear open paid bounty signal >= $10 found

## 52. [Bounty] Block Explorer Bug Hunt - 2 RTC

- Decision: drop
- Score: 30 -> -40
- Issue: https://github.com/Scottcjn/rustchain-bounties/issues/517
- Reason: no clear open paid bounty signal >= $10 found

## 53. [BOUNTY: 15 RTC] BoTTube — Video Page Customization

- Decision: keep
- Score: 20 -> -15
- Issue: https://github.com/Scottcjn/rustchain-bounties/issues/2156
- Reason: competition already visible in comments; still allowed in aggressive mode
