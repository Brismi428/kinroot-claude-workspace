# Weekly Report

Generate a weekly progress report based on the current workspace context.

## Variables

- focus_area: $ARGUMENTS (optional — specify a particular area to emphasize, e.g., "marketing", "product", "sales")

## Instructions

This is an example domain command. It shows how to structure a reusable task that Claude executes the same way every time. Customize this for your actual role.

### Step 1: Gather Context

Read the following files to understand current state:
- `context/strategy.md` — what are we working toward?
- `context/current-data.md` — what do the numbers say?

### Step 2: Analyze the Week

Based on the strategy and current data, produce a weekly report covering:

1. **Progress against priorities** — For each strategic priority in strategy.md, assess what moved forward this week based on the data available.
2. **Key metrics summary** — Pull the most relevant numbers from current-data.md and note any significant changes, trends, or anomalies.
3. **Wins** — What went well? What's worth celebrating or noting?
4. **Blockers or risks** — What's stalled, at risk, or needs attention?
5. **Next week focus** — Based on everything above, what should the top 3 priorities be for next week?

If a focus_area was specified, weight the report toward that area while still covering the full picture.

### Step 3: Output

Save the report to: `outputs/weekly-report-YYYY-MM-DD.md`

Use today's date in the filename. Write in a clear, direct tone suitable for sharing with a team or manager. Avoid fluff — every sentence should carry information.

### Step 4: Summary

After saving, provide a brief verbal summary of the 3 most important takeaways from the report.