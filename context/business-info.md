# Business Info

This file provides background on the organization or business you operate within. It sets the stage for understanding your role (personal-info.md) and strategic priorities (strategy.md).

## How This Connects

- This file establishes organizational context
- `personal-info.md` defines your role within this org
- `strategy.md` captures the goals you're driving toward
- `current-data.md` tracks progress and informs decisions

## Organization Overview

Kinroot is a personal household OS for parents carrying the mental load. It's a single-user command center — one parent logs in and manages everything about their household from one place. This is NOT a family app, NOT a co-parenting tool, and NOT a multi-user platform. Think of it as a productivity tool purpose-built for the unique chaos of single parenthood.

The core insight: single parents don't need another app that assumes two adults are coordinating. They need a tool that respects the reality of doing it all alone and makes that easier.

## Product

Kinroot is a Next.js 15 SaaS application with 5 core modules:

- **Root Planner** — Household dashboard and task management hub
- **Calendar** — Family schedule management with event tracking
- **Mealflow** — Meal planning and grocery organization
- **Village Network** — Local community for single parents (privacy-first, with 3-mile fuzzy geolocation)
- **Task Management** — Kanban-style task boards for household organization

### Subscription Tiers

| Tier | Price | Key Features |
|------|-------|--------------|
| Free | $0/mo | 1 child limit, core features |
| Plus | $12.99/mo | Unlimited children, full access |
| Premium Plus | $24.99/mo | Everything in Plus + AI-powered features |

## Key Context

- **Stage:** Closed beta with 17 invited testers. MVP is complete.
- **Scale:** 13 pages, 22+ API routes, 15 database tables
- **Tech stack:** Next.js 15, React 19, Supabase (auth + DB), Stripe (payments), Tailwind CSS v4, shadcn/ui
- **Beta mechanics:** Auto-activation on signup — marks `is_beta_tester = true`, grants 3-month free Plus, sets 20% lifetime discount for post-beta
- **Privacy stance:** Privacy-first design. Village Network uses fuzzy geolocation (3-mile randomization) so exact locations are never exposed.
- **Differentiation:** Single-parent focus (not generic family tools), privacy-first community, all-in-one household OS (not just one feature)
- **Kids are data, not users.** Children are managed like calendar events — the parent enters and manages their info. Kids never log in.

---

*Keep this high-level — enough to orient Claude, not a comprehensive company wiki.*
