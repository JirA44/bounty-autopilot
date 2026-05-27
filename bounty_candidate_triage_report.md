# GitHub Bounty Candidate Triage

Last run: 2026-05-27 18:36 UTC

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

## 4. Hardening: fix cost tracking, broken test import, and depth-config audit items

- Decision: drop
- Score: 110 -> 40
- Issue: https://github.com/harishkanna-019/revgent-v3/issues/11
- Reason: no clear open paid bounty signal >= $10 found

## 5. Looker tables missing data

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/solema247/Mutual-Aid-Portal/issues/59
- Reason: no clear open paid bounty signal >= $10 found

## 6. P2: dispatch_tick silently swallows push_leads per-lead errors when email lookup misses

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/DanLika/LeadDataScraper/issues/367
- Reason: no clear open paid bounty signal >= $10 found

## 7. [infra] Staging deploy takes ~21 min end-to-end; cut to under 10 on test/docs-only PRs

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/brownm09/lifting-logbook/issues/358
- Reason: no clear open paid bounty signal >= $10 found

## 8. Verify 2026-05-27 deploys: trialing-sub recon, Pendiente subs-only, late-payment-on-cancelled-sub, Enviar por email

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/joseamtalavera/beworking-orchestration/issues/228
- Reason: no clear open paid bounty signal >= $10 found

## 9. SQL deadlocks in EntityRepository bulk methods — default Serializable isolation in TransactionScope

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/nopSolutions/nopCommerce/issues/8212
- Reason: no clear open paid bounty signal >= $10 found

## 10. Decompose 16 oversize Python source files to clear the file-size allowlist

- Decision: drop
- Score: 85 -> -15
- Issue: https://github.com/jwbron/egg/issues/2817
- Reason: false positive claim/cost/market/manual-access issue, not an open coding bounty

## 11. Plan phase: architect owns slice composition; risk_analyst becomes dual-role reviewer; reviewer_plan NACKs oversized slices

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/jwbron/egg/issues/2809
- Reason: no clear open paid bounty signal >= $10 found

## 12. PEND-83 — Hierarchical pages: pill display consistency + dedicated child-pages tree on the page view

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/jfolcini/agaric/issues/89
- Reason: no clear open paid bounty signal >= $10 found

## 13. [E14.5] e2e: Stripe webhook events (B7–B14)

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/sniffins-mcmuggins/murals/issues/111
- Reason: no clear open paid bounty signal >= $10 found

## 14. [BUG-106] wiki read truncates large documents silently — large-document review is broken for all connector users

- Decision: drop
- Score: 79 -> -21
- Issue: https://github.com/Jonnyton/Workflow/issues/1087
- Reason: issue explicitly indicates no paid bounty or free-only payment status

## 15. [WIKI-DESIGN] Souled-universe consolidation program — finish the substrate's half-built universe/soul/permission surfaces into one finite domain-neutral architecture

- Decision: drop
- Score: 71 -> -29
- Issue: https://github.com/Jonnyton/Workflow/issues/1090
- Reason: false positive claim/cost/market/manual-access issue, not an open coding bounty

## 16. bug: scheduled runs ignore per-agent execution_timeout_seconds (canary S-03 + E-01 surfaced)

- Decision: drop
- Score: 70 -> 0
- Issue: https://github.com/Abilityai/trinity/issues/913
- Reason: no clear open paid bounty signal >= $10 found

## 17. Invoice cannot be marked as paid - Failed to mark bill as paid

- Decision: drop
- Score: 69 -> -1
- Issue: https://github.com/otherworld-dev/Budget/issues/222
- Reason: no clear open paid bounty signal >= $10 found

## 18. 扩充赏金组织列表：当前 21 个组织中仅 2 个有活跃赏金

- Decision: drop
- Score: 68 -> -32
- Issue: https://github.com/FuZoe/PD-Hunter/issues/18
- Reason: false positive claim/cost/market/manual-access issue, not an open coding bounty

## 19. Microgrant Proposal: Field verified OpenStreetMap data

- Decision: drop
- Score: 63 -> -37
- Issue: https://github.com/osmfoundation/ewg_bidding/issues/24
- Reason: false positive claim/cost/market/manual-access issue, not an open coding bounty

## 20. Low Handing Fruit Automation

- Decision: keep
- Score: 61 -> 26
- Issue: https://github.com/SecureBananaLabs/bug-bounty/issues/743
- Reason: competition already visible in comments; still allowed in aggressive mode

## 21. qa-review: double-review in single turn regression — idempotency guard (mika#695) not preventing duplicate pr review posts

- Decision: drop
- Score: 60 -> -10
- Issue: https://github.com/senara-solutions/mika/issues/736
- Reason: no clear open paid bounty signal >= $10 found

## 22. P0: Fix RL simulator objective activation after post-1448 smoke remains territory=2/kills=0

- Decision: drop
- Score: 56 -> -49
- Issue: https://github.com/lanyusea/screeps/issues/1450
- Reason: no clear open paid bounty signal >= $10 found
- Reason: competition already visible in comments; still allowed in aggressive mode

## 23. AGENTMEMORY_SECRET enables api-auth middleware that also rejects internal worker callbacks, silently halting consolidation pipeline (v0.9.20)

- Decision: drop
- Score: 54 -> -16
- Issue: https://github.com/rohitg00/agentmemory/issues/518
- Reason: no clear open paid bounty signal >= $10 found

## 24. Fix helm chart dependencies on Bitnami images

- Decision: drop
- Score: 54 -> -16
- Issue: https://github.com/bcgov/MFIN-Data-Catalogue/issues/680
- Reason: no clear open paid bounty signal >= $10 found

## 25. Bug: UpcomingPayments Shows Fake Data and "Pay Now" Button Does Nothing

- Decision: drop
- Score: 54 -> -16
- Issue: https://github.com/BlockHaven-Labs/esustellar/issues/51
- Reason: no clear open paid bounty signal >= $10 found

## 26. WaterwayMap.org hosting costs

- Decision: drop
- Score: 54 -> -46
- Issue: https://github.com/osmfoundation/ewg_bidding/issues/45
- Reason: false positive claim/cost/market/manual-access issue, not an open coding bounty

## 27. Microgrant Proposal: OSMAutoDrone

- Decision: drop
- Score: 54 -> -46
- Issue: https://github.com/osmfoundation/ewg_bidding/issues/39
- Reason: issue explicitly indicates no paid bounty or free-only payment status

## 28. MICROGRANT PROPOSAL:OSM-BASED DASHBOARD FOR CLIMATE CHANGE MONITORING IN AFRICA

- Decision: drop
- Score: 54 -> -16
- Issue: https://github.com/osmfoundation/ewg_bidding/issues/22
- Reason: no clear open paid bounty signal >= $10 found

## 29. Microgrant Proposal: Enhancing Drone Tasking Manager for Multi-Drone Support and Operational Refinements

- Decision: drop
- Score: 54 -> -46
- Issue: https://github.com/osmfoundation/ewg_bidding/issues/28
- Reason: false positive claim/cost/market/manual-access issue, not an open coding bounty

## 30. MicroGrant Proposal : OSMSG

- Decision: drop
- Score: 54 -> -16
- Issue: https://github.com/osmfoundation/ewg_bidding/issues/30
- Reason: no clear open paid bounty signal >= $10 found

## 31. MIcrogrant Proposal: OSMLocalizer

- Decision: drop
- Score: 54 -> -46
- Issue: https://github.com/osmfoundation/ewg_bidding/issues/29
- Reason: false positive claim/cost/market/manual-access issue, not an open coding bounty

## 32. Microgrant Proposal: OpenStreetMap Before-After Maps Generator

- Decision: drop
- Score: 54 -> -16
- Issue: https://github.com/osmfoundation/ewg_bidding/issues/27
- Reason: no clear open paid bounty signal >= $10 found

## 33. docs: README missing quick-start command for macOS users

- Decision: drop
- Score: 49 -> -21
- Issue: https://github.com/Scottcjn/Rustchain/issues/6414
- Reason: no clear open paid bounty signal >= $10 found

## 34. perf(ci): build.yml optimization plan — parallelism, caching, and redundancy removal

- Decision: drop
- Score: 49 -> -21
- Issue: https://github.com/aws-samples/sample-autonomous-cloud-coding-agents/issues/201
- Reason: no clear open paid bounty signal >= $10 found

## 35. [Discussion] Optimizer-strength fairness in Table 1: SkillOpt uses GPT-5.5 as optimizer while several baselines (GEPA, Trace2Skill, EvoSkill) are self-contained by design

- Decision: drop
- Score: 49 -> -21
- Issue: https://github.com/microsoft/SkillOpt/issues/12
- Reason: no clear open paid bounty signal >= $10 found

## 36. Phase-2 follow-on for Epic #2041: per-runtime fleet-review skill wrappers

- Decision: drop
- Score: 49 -> -21
- Issue: https://github.com/chf3198/megingjord-harness/issues/2285
- Reason: no clear open paid bounty signal >= $10 found

## 37. Phase-2 follow-on for Epic #2041: fleet-red-team workflow operator runbook

- Decision: drop
- Score: 49 -> -21
- Issue: https://github.com/chf3198/megingjord-harness/issues/2284
- Reason: no clear open paid bounty signal >= $10 found

## 38. Microgrant Proposal: Map Review Team

- Decision: drop
- Score: 48 -> -22
- Issue: https://github.com/osmfoundation/ewg_bidding/issues/46
- Reason: no clear open paid bounty signal >= $10 found

## 39. Microgrant Proposal: GeoAI for Maternal Health Risk Mapping in Kenya

- Decision: drop
- Score: 48 -> -22
- Issue: https://github.com/osmfoundation/ewg_bidding/issues/43
- Reason: no clear open paid bounty signal >= $10 found

## 40. Microgrant Proposal: Campus Guide

- Decision: drop
- Score: 48 -> -22
- Issue: https://github.com/osmfoundation/ewg_bidding/issues/23
- Reason: no clear open paid bounty signal >= $10 found

## 41. Draft: MIcrogrant Proposal- OSMLocalizer

- Decision: drop
- Score: 48 -> -52
- Issue: https://github.com/osgeonepal/site/issues/74
- Reason: false positive claim/cost/market/manual-access issue, not an open coding bounty

## 42. [BUG] Desktop app Google Drive connector flow routes to signup page, creates duplicate account under same email and locks paid Max subscriber

- Decision: drop
- Score: 46 -> -24
- Issue: https://github.com/anthropics/claude-code/issues/51002
- Reason: no clear open paid bounty signal >= $10 found

## 43. [Blueprint] Strange scroll bar

- Decision: drop
- Score: 46 -> -119
- Issue: https://github.com/stakwork/sphinx-nav-fiber/issues/2315
- Reason: no clear open paid bounty signal >= $10 found
- Reason: light competition allowed: 4 open competing PR(s)
- Reason: competition already visible in comments; still allowed in aggressive mode
- Competing PR: https://github.com/stakwork/sphinx-nav-fiber/pull/3020
- Competing PR: https://github.com/stakwork/sphinx-nav-fiber/pull/3004
- Competing PR: https://github.com/stakwork/sphinx-nav-fiber/pull/2999
- Competing PR: https://github.com/stakwork/sphinx-nav-fiber/pull/2991

## 44. NuGet package signing for Fleans.Application.Abstractions / Fleans.Worker / Fleans.Plugins.RestCaller

- Decision: drop
- Score: 46 -> -24
- Issue: https://github.com/nightBaker/fleans/issues/458
- Reason: no clear open paid bounty signal >= $10 found

## 45. Insulation as Infrastructure: supporting “Dobra Maisternia” in frontline Kharkiv region

- Decision: drop
- Score: 44 -> -26
- Issue: https://github.com/maxzalevski/community_spaces/issues/7
- Reason: no clear open paid bounty signal >= $10 found

## 46. W3I Network Initiative in Action: Building a Sarafu-Based DAO for Regenerative Coordination in Ukraine

- Decision: drop
- Score: 44 -> -26
- Issue: https://github.com/maxzalevski/grants/issues/2
- Reason: no clear open paid bounty signal >= $10 found

## 47. Radaria three bunk beds in hostel

- Decision: drop
- Score: 44 -> -26
- Issue: https://github.com/maxzalevski/community_spaces/issues/6
- Reason: no clear open paid bounty signal >= $10 found

## 48. Add policies / visa letter page

- Decision: drop
- Score: 44 -> -26
- Issue: https://github.com/open-life-science/open-life-science.github.io/issues/1108
- Reason: no clear open paid bounty signal >= $10 found

## 49. Meeting [2025-06-06]

- Decision: drop
- Score: 44 -> -26
- Issue: https://github.com/osgeonepal/site/issues/73
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
