# Canonical Project Portfolio

This document is the portfolio source of truth for the Emergent-origin project cluster and its consolidation status.

| Product family | Canonical repository | Legacy / merge source | Strategic role | Primary economic path |
| --- | --- | --- | --- | --- |
| Musician On-Demand | [MOD](https://github.com/wizelements/MOD) | MusucianOnDemand | Commercial product | Booking/platform transaction revenue |
| C3B Trade | [c3b-trade](https://github.com/wizelements/c3b-trade) | tradealert | Commercial product | Recurring subscription |
| SynWave | [SpeakUp](https://github.com/wizelements/SpeakUp) | blushaired | R&D / licensable IP | SDK, licensing, installations, service |
| KGU Staff Portal | [KGUStaffPortal](https://github.com/wizelements/KGUStaffPortal) | — | Internal/productizable operations tool | Contractor/instructor billing SaaS or service |
| TeeUp ATL | [Teeupatl](https://github.com/wizelements/Teeupatl) | — | Local vertical product | Membership, events, referrals, partnerships |
| MomentumPress | [momentumpress](https://github.com/wizelements/momentumpress) | — | Internal delivery accelerator | Margin improvement and faster client delivery |

## Consolidation policy

1. One product family has one canonical development repository.
2. Legacy repositories remain available for provenance and recovery, but receive no independent feature development.
3. Duplicate code is not copied merely to create activity. Identical implementations are canonicalized by reference; divergent features are ported only when verified and useful.
4. Historical completion reports do not establish current production status.
5. Each canonical repository must state its business objective, current maturity, completion condition, and revenue path.
6. Generated caches, obsolete preview configuration, committed credentials, and stale provider-specific assumptions should be removed as each canonical repository is hardened.
7. Portfolio priority is determined by customer value, revenue potential, reuse, and proof—not repository count.

## Merge decisions

### Musician On-Demand
Core backend, frontend application, dependency, requirements, and backend-test file hashes matched between the duplicate repositories during the October 7, 2026 audit. MOD is therefore the canonical repository; MusucianOnDemand is a legacy snapshot rather than a parallel codebase.

### SynWave
The duplicate repositories share the same backend server, backend tests, and testing-state file. SpeakUp carries the newer frontend dependency baseline and is the canonical repository.

### TradeAlert / C3B Trade
The repositories have diverged. c3b-trade is the canonical product identity, while tradealert contains additional hardening work. Security and subscription improvements must be selectively ported and verified rather than wholesale-merging old trees.

## Portfolio focus

The six families are intentionally not equal in priority.

- **Near-term revenue:** C3B Trade, Musician On-Demand, KGU Staff Portal.
- **Client-delivery leverage:** MomentumPress.
- **Vertical/community opportunity:** TeeUp ATL.
- **Longer-horizon defensible IP:** SynWave.

This structure should reduce duplicate development, clarify ownership, and turn the Emergent experiments into a smaller set of deliberate products and reusable assets.
