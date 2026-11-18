# Agent log

Add a dated entry each time you work with your AI coding agent, with the newest entry at the bottom. Each entry records what you asked the agent, what it produced, and what you checked or changed. Paste your key prompts in exactly as you typed them. Include at least one time the agent got something wrong, and how you caught it.

Copy this outline for each entry:

```markdown
## YYYY-MM-DD: What you worked on

- **Asked:** "Paste your prompt here."
- **Agent produced:** What it made or changed.
- **Checked or changed:** How you checked it, and what you fixed.
```
## 2026-11-18 — Claude (claude.ai)
Task: Replace the placeholder index.html with a dashboard built from data/college_town_home_sales.csv:
KPIs, median sale price by city (bar chart), sortable city table, campus filter.
Rules: sales from $10,000 to $5,000,000 only; days on market = contract_date − list_date when both exist;
price per sq ft only when living_area_sqft > 0; no deduplication by address.
Check: city medians (sales ≥ $1,000) matched the table in docs/data_description_sheet.md.
