# Research

Conduct focused research on a topic and produce a structured briefing document.

## Variables

- topic: $ARGUMENTS (required — the subject to research, e.g., "competitor pricing strategies", "AI trends in healthcare", "best CRM tools for small teams")

## Instructions

This command demonstrates how to use Claude Code's web search and deep research capabilities within a workspace command. It produces a research briefing grounded in your business context.

### Step 1: Understand the Request

Parse the topic provided. Read `context/business-info.md` and `context/strategy.md` to understand why this research matters to the user's work.

### Step 2: Research

Search the web thoroughly for current, high-quality information on the topic. Focus on:
- Recent developments (within the last 6 months where possible)
- Credible sources (industry reports, established publications, official documentation)
- Multiple perspectives where relevant

Aim for depth over breadth. 5 excellent sources are better than 20 shallow ones.

### Step 3: Synthesize

Produce a research briefing with this structure:

1. **Executive summary** — 3-5 sentences capturing the key findings
2. **Key findings** — The most important facts, trends, or insights discovered, organized by theme
3. **Relevance to us** — How these findings connect to our business context and current strategy
4. **Opportunities or implications** — What should we consider doing based on this research?
5. **Sources** — List of sources used with brief descriptions of each

### Step 4: Output

Save to: `outputs/research-YYYY-MM-DD-{topic-slug}.md`

Replace {topic-slug} with a short kebab-case version of the topic (e.g., "competitor-pricing", "ai-healthcare-trends").

### Step 5: Summary

Provide a brief verbal summary of the 3 most surprising or actionable findings.