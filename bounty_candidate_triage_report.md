# GitHub Bounty Candidate Triage

Last run: 2026-05-28 16:48 UTC

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

## 4. Potential paid-work-before-settlement issue in x402 tool routes

- Decision: drop
- Score: 110 -> 40
- Issue: https://github.com/mokwathedeveloper/Agent-Paywall-Router/issues/1
- Reason: no clear open paid bounty signal >= $10 found

## 5. perf(ingest): parallelize per-listing scrape+score within a page using a thread pool

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/glitchwerks/job-matcher/issues/560
- Reason: no clear open paid bounty signal >= $10 found

## 6. [Chapter 5] 결제 취소(환불) 기능 구현

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/gone09-sketch/sparta-payment-system/issues/21
- Reason: no clear open paid bounty signal >= $10 found

## 7. Potential settlement-ordering issue: AI service executes before payment settlement

- Decision: drop
- Score: 85 -> -15
- Issue: https://github.com/basileus-labs/x402-api-gateway/issues/1
- Reason: false positive claim/cost/market/manual-access issue, not an open coding bounty

## 8. auto-recap: prompt passed via argv (E2BIG) — 72 silent spawn failures from large README

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/Kohei-Wada/knowledge-gardener/issues/19
- Reason: no clear open paid bounty signal >= $10 found

## 9. 🎯 Bounty Alert: 8 New Opportunityies found

- Decision: drop
- Score: 85 -> -15
- Issue: https://github.com/dev-kp-eloper/BountyScout/issues/38
- Reason: false positive claim/cost/market/manual-access issue, not an open coding bounty

## 10. Non-numeric input at main menu / ticket prompts crashes program

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/bushidocodes/west-point-train-station/issues/22
- Reason: no clear open paid bounty signal >= $10 found

## 11. Claude Code dependency contract + automated regression tests

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/coalesce-labs/catalyst/issues/1165
- Reason: no clear open paid bounty signal >= $10 found

## 12. RadzenTabs component's SelectTab method is not exception-safe

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/radzenhq/radzen-blazor/issues/2558
- Reason: no clear open paid bounty signal >= $10 found

## 13. [BUG] DashScope Rerank: spring.ai.dashscope.rerank.options.model 配置不生效，始终使用默认 gte-rerank

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/alibaba/spring-ai-alibaba/issues/4663
- Reason: no clear open paid bounty signal >= $10 found

## 14. Potential paid asset access issue: asset data routes bypass payment enforcement

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/0xAlchemist1411/x402-agent/issues/2
- Reason: no clear open paid bounty signal >= $10 found

## 15. [BUG BOUNTY] [Medium] [Gas/WBank] DAO fee receivers bypass blocked module-account protection

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/openmetaearth/me-hub/issues/298
- Reason: no clear open paid bounty signal >= $10 found

## 16. Memoize re-render scope in the workspace Ink runtime

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/gfargo/coco/issues/1079
- Reason: no clear open paid bounty signal >= $10 found

## 17. [BUG BOUNTY] [Medium] [Wmint/WStaking] Staking rewards continue accruing after the wmint supply cap stops minting

- Decision: drop
- Score: 85 -> -15
- Issue: https://github.com/openmetaearth/me-hub/issues/292
- Reason: false positive claim/cost/market/manual-access issue, not an open coding bounty

## 18. Potential settlement gating issue: paid MCP callback runs before settlement

- Decision: drop
- Score: 85 -> -15
- Issue: https://github.com/microchipgnu/MCPay/issues/43
- Reason: false positive claim/cost/market/manual-access issue, not an open coding bounty

## 19. Image upload endpoint accepts arbitrary file types with no MIME validation, forwarding them to paid AI vision APIs

- Decision: drop
- Score: 85 -> 15
- Issue: https://github.com/ln-tc999/ai-trading/issues/7
- Reason: no clear open paid bounty signal >= $10 found

## 20. Fully-paid invoice (Balance Rs 0.00) still displays 'Unpaid' status

- Decision: drop
- Score: 85 -> -15
- Issue: https://github.com/tachyoniclabs/autoerp-support/issues/3
- Reason: issue explicitly indicates no paid bounty or free-only payment status

## 21. [ Bounty $3k ] [ Research ] Collect and compare AI-generated AGI architecture proposals

- Decision: keep
- Score: 81 -> 46
- Issue: https://github.com/aLexzzz430/Cognitive-OS/issues/5
- Reason: competition already visible in comments; still allowed in aggressive mode

## 22. openai-codex subscription backend returns HTTP 200 with response.output=None, causing Slack/cron failures

- Decision: drop
- Score: 79 -> -26
- Issue: https://github.com/NousResearch/hermes-agent/issues/33976
- Reason: no clear open paid bounty signal >= $10 found
- Reason: competition already visible in comments; still allowed in aggressive mode

## 23. [Bug] Timeout extensions verify miner-controlled fulfilled amount instead of canonical payout, so underpaid txs can delay slashing

- Decision: drop
- Score: 79 -> 9
- Issue: https://github.com/entrius/allways/issues/403
- Reason: no clear open paid bounty signal >= $10 found

## 24. [BUG]

- Decision: drop
- Score: 79 -> 9
- Issue: https://github.com/anthropics/claude-code/issues/63115
- Reason: no clear open paid bounty signal >= $10 found

## 25. [Bug](nereids) distributionPrune doesn't slice nereidsPrunedTabletIds per partition

- Decision: drop
- Score: 79 -> -26
- Issue: https://github.com/apache/doris/issues/63854
- Reason: no clear open paid bounty signal >= $10 found
- Reason: competition already visible in comments; still allowed in aggressive mode

## 26. perf: Inefficient O(N log N) global sort in content recommender

- Decision: drop
- Score: 79 -> 9
- Issue: https://github.com/leonagoel/hybrid-recommender/issues/643
- Reason: no clear open paid bounty signal >= $10 found

## 27. Add React app action to record an offline team fee payment

- Decision: drop
- Score: 79 -> -56
- Issue: https://github.com/pauljsnider/allplays/issues/1513
- Reason: issue explicitly indicates no paid bounty or free-only payment status
- Reason: competition already visible in comments; still allowed in aggressive mode

## 28. Potential challenge-binding issue: nonce lookup can authorize a different current tool

- Decision: drop
- Score: 75 -> 5
- Issue: https://github.com/QuinnYates/tomopay-gateway/issues/3
- Reason: no clear open paid bounty signal >= $10 found

## 29. Potential settlement-ordering issue: delegate agent executes before settlement

- Decision: drop
- Score: 75 -> 5
- Issue: https://github.com/Trustdev-eth/a2a-x402/issues/1
- Reason: no clear open paid bounty signal >= $10 found

## 30. Potential settlement gating issue: paid tool callback runs before settlement

- Decision: drop
- Score: 75 -> -25
- Issue: https://github.com/cloudflare/agents/issues/1603
- Reason: false positive claim/cost/market/manual-access issue, not an open coding bounty

## 31. Potential paid-cookie scope issue: auth_token is not bound to route or payment context

- Decision: drop
- Score: 75 -> 5
- Issue: https://github.com/cloudflare/mpp-proxy/issues/24
- Reason: no clear open paid bounty signal >= $10 found

## 32. Potential payment-session binding issue: recent receiver transfer is accepted for a reference

- Decision: drop
- Score: 75 -> 5
- Issue: https://github.com/homebrewroboticsclub/Ros-X402-Node/issues/5
- Reason: no clear open paid bounty signal >= $10 found

## 33. Start me up! Week 1

- Decision: drop
- Score: 70 -> 0
- Issue: https://github.com/malon7782/gsoc-blog-2026/issues/5
- Reason: no clear open paid bounty signal >= $10 found

## 34. ci: add nix-community/cache-nix-action for store-path caching across cold runs

- Decision: drop
- Score: 69 -> -1
- Issue: https://github.com/dannyfaris/nix-config/issues/61
- Reason: no clear open paid bounty signal >= $10 found

## 35. [Hiring] Full-Stack Developer — React Native + NestJS — Paid $3-7K

- Decision: drop
- Score: 65 -> -5
- Issue: https://github.com/hrahatyesayan-stack/vetpet/issues/1
- Reason: no clear open paid bounty signal >= $10 found

## 36. LICENSE funding model — UI/forms are incomplete despite schema being ready

- Decision: drop
- Score: 64 -> -6
- Issue: https://github.com/Practitionist/familiarise_web/issues/756
- Reason: no clear open paid bounty signal >= $10 found

## 37. Phishing-gate auto-cancelling legitimate bookings — paid Teams plan, 5 support tickets/emails unanswered

- Decision: drop
- Score: 64 -> -6
- Issue: https://github.com/calcom/cal.diy/issues/29469
- Reason: no clear open paid bounty signal >= $10 found

## 38. Docs site live at curio-core-docs.pages.dev (first cut, will improve)

- Decision: drop
- Score: 64 -> -6
- Issue: https://github.com/Reiers/curio-core/issues/66
- Reason: no clear open paid bounty signal >= $10 found

## 39. Add indicators like MA, RSI, MACD, etc.

- Decision: keep
- Score: 61 -> 26
- Issue: https://github.com/capofficial/client/issues/16
- Reason: competition already visible in comments; still allowed in aggressive mode

## 40. bug: Nitrate activation code reuse cannot be distinguished from invalid codes (misleading error)

- Decision: drop
- Score: 60 -> -10
- Issue: https://github.com/penpot/penpot/issues/9624
- Reason: no clear open paid bounty signal >= $10 found

## 41. When a customer has a credit it is tagged as non paid in customer account

- Decision: drop
- Score: 54 -> -16
- Issue: https://github.com/openfoodfoundation/openfoodnetwork/issues/14197
- Reason: no clear open paid bounty signal >= $10 found

## 42. feat(submissions): add guided source-backed submission wizard

- Decision: drop
- Score: 54 -> -16
- Issue: https://github.com/JSONbored/awesome-claude/issues/444
- Reason: no clear open paid bounty signal >= $10 found

## 43. PEP 541 Request: adminA / admina transfer with owner consent

- Decision: drop
- Score: 49 -> -21
- Issue: https://github.com/pypi/support/issues/10814
- Reason: no clear open paid bounty signal >= $10 found

## 44. Agent runs fall back to openrouter despite model.provider=custom in config.yaml

- Decision: drop
- Score: 46 -> -24
- Issue: https://github.com/NousResearch/hermes-agent/issues/12146
- Reason: no clear open paid bounty signal >= $10 found

## 45. Improve test coverage for cmd/fleet/serve.go

- Decision: drop
- Score: 46 -> -59
- Issue: https://github.com/fleetdm/fleet/issues/33370
- Reason: no clear open paid bounty signal >= $10 found
- Reason: competition already visible in comments; still allowed in aggressive mode

## 46. NuGet package signing for Fleans.Application.Abstractions / Fleans.Worker / Fleans.Plugins.RestCaller

- Decision: drop
- Score: 46 -> -24
- Issue: https://github.com/nightBaker/fleans/issues/458
- Reason: no clear open paid bounty signal >= $10 found

## 47. Add BountyClient + ContractClient + wire-format types after chain v0.4.0 lands

- Decision: drop
- Score: 43 -> -27
- Issue: https://github.com/ligate-io/ligate-js/issues/46
- Reason: no clear open paid bounty signal >= $10 found

## 48. I purchased additional Codex credits but still can't use it.

- Decision: drop
- Score: 41 -> -29
- Issue: https://github.com/openai/codex/issues/19830
- Reason: no clear open paid bounty signal >= $10 found

## 49. Widget Looses Thumbnail - I want Paid Support ( Please )

- Decision: drop
- Score: 40 -> -30
- Issue: https://github.com/seazon/FeedMe/issues/137
- Reason: no clear open paid bounty signal >= $10 found

## 50. [Backend] Implement loyalty program backend

- Decision: drop
- Score: 39 -> -31
- Issue: https://github.com/Lex-Studios/Stellar-Spend/issues/501
- Reason: no clear open paid bounty signal >= $10 found

## 51. Add bounty + contract surfaces after chain v0.4.0 lands

- Decision: drop
- Score: 39 -> -31
- Issue: https://github.com/ligate-io/ligate-api/issues/77
- Reason: no clear open paid bounty signal >= $10 found

## 52. Account recovery request

- Decision: drop
- Score: 39 -> -31
- Issue: https://github.com/pypi/support/issues/10813
- Reason: no clear open paid bounty signal >= $10 found

## 53. Account recovery request

- Decision: drop
- Score: 39 -> -31
- Issue: https://github.com/pypi/support/issues/10811
- Reason: no clear open paid bounty signal >= $10 found

## 54. Account recovery request

- Decision: drop
- Score: 39 -> -31
- Issue: https://github.com/pypi/support/issues/10810
- Reason: no clear open paid bounty signal >= $10 found

## 55. [Cross-platform Collaboration] Nautilus: Agent Economic Infrastructure + Partnership Proposal

- Decision: drop
- Score: 35 -> -35
- Issue: https://github.com/wanxingai/LightAgent/issues/41
- Reason: no clear open paid bounty signal >= $10 found

## 56. GeneralFailure("Authentication throttled. Wait a minute and try again.")

- Decision: drop
- Score: 35 -> -35
- Issue: https://github.com/himmelblau-idm/himmelblau/issues/1414
- Reason: no clear open paid bounty signal >= $10 found
