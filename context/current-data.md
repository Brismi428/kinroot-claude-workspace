# Current Data

This file holds metrics, data points, and current state information relevant to your role and strategy. It provides Claude with concrete context for analysis and decision-making.

## How This Connects

- `business-info.md` provides organizational context
- `personal-info.md` defines what you're responsible for
- `strategy.md` outlines what you're optimizing toward
- This file gives Claude the numbers behind the narrative

## Key Metrics

<!-- REPLACE with your actual metrics -->

**Example:**

| Metric | Current Value | Target | Notes |
|--------|--------------|--------|-------|
| MQLs (Q1 to date) | 38 | 120 | On pace for ~76, need to accelerate |
| Website traffic (monthly) | 12,400 | 18,000 | Up 8% MoM, blog is primary driver |
| Cost per lead | $125 | $106 | Google Ads CPL is $180, LinkedIn is $95 |
| Blog posts published (Q1) | 9 | 36 | Slightly behind 3/week cadence |
| YouTube subscribers | 2,100 | 3,000 | Growing ~150/month |
| Email list size | 4,800 | 6,000 | Open rate 34%, click rate 4.2% |
| Acme Docs trial signups | 12 | 50 | Campaign hasn't launched yet |

## Current State

<!-- REPLACE with qualitative status updates -->

**Example:**
- The webinar series is in production — first one scheduled for Feb 18. Speaker confirmed, landing page draft complete.
- Google Ads performance has degraded since January. Investigating whether it's a bidding issue or creative fatigue.
- Content team is at capacity. The 3/week blog cadence is achievable but leaves no room for one-off requests.
- The Docs cross-sell campaign is blocked on getting customer email segments from the product team. Follow up scheduled for Feb 10.

## Data Sources

<!-- REPLACE with where your data comes from -->

**Example:**
- Google Analytics (website traffic, conversion rates)
- HubSpot (MQLs, email metrics, pipeline)
- Google Ads + LinkedIn Ads dashboards (paid metrics)
- YouTube Studio (subscriber and video analytics)
- Internal spreadsheet for monthly P&L and budget tracking

## Automation Note

This file works as a static snapshot, but can be enhanced with scripts that pull live data. Once comfortable with the workspace, consider adding a script to `scripts/` that refreshes this file from your data sources (dashboards, APIs, spreadsheets, etc.).

---

*Update regularly — stale data limits Claude's usefulness as an analytical partner. Delete the examples above and replace with your own content.*