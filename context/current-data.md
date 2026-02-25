# Current Data

This file holds metrics, data points, and current state information relevant to your role and strategy. It provides Claude with concrete context for analysis and decision-making.

## How This Connects

- `business-info.md` provides organizational context
- `personal-info.md` defines what you're responsible for
- `strategy.md` outlines what you're optimizing toward
- This file gives Claude the numbers behind the narrative

## Key Metrics

| Metric | Current Value | Target | Notes |
|--------|--------------|--------|-------|
| Beta testers | 17 | Expand in Q1 | Closed beta, invite-only |
| Core modules | 5 | — | Root Planner, Calendar, Mealflow, Village, Tasks |
| App pages | 13 | — | MVP complete |
| API routes | 22+ | — | v1 endpoints active |
| Database tables | 15 | — | Supabase with RLS |
| Subscription tiers | 3 | — | Free / Plus / Premium Plus |

### Revenue Targets

| Milestone | Target |
|-----------|--------|
| Month 6 | $15K MRR |
| Month 12 | $50K MRR |

### Pricing

| Tier | Monthly Price |
|------|--------------|
| Free | $0 |
| Plus | $12.99 |
| Premium Plus | $24.99 |

## Current State

- **MVP is complete.** All core modules are functional and deployed.
- **Closed beta is active.** 17 testers have been invited with auto-activation working (auto-grants Plus for 3 months + 20% lifetime discount).
- **Payments are live.** Stripe integration with webhook handling is operational.
- **Auth is solid.** Supabase auth with RLS policies on all tables.
- **Village Network is live** with fuzzy geolocation (3-mile randomization) for privacy.
- **Task management** was recently added with Kanban-style boards.
- **Recent work:** Password visibility toggles, date handling fixes (local time vs UTC), forum post improvements, post likes feature.

## Data Sources

- **Supabase Dashboard** — User signups, beta tester status, database metrics
- **Stripe Dashboard** — Subscription status, payment events, revenue
- **Beta tester feedback** — Direct feedback from the 17-person cohort
- **Application logs** — Supabase logs for debugging and monitoring

## Automation Note

This file works as a static snapshot, but can be enhanced with scripts that pull live data. Consider adding a script to `scripts/` that queries Supabase for current beta tester count, active subscriptions, and engagement metrics.

---

*Update regularly — stale data limits Claude's usefulness as an analytical partner.*
