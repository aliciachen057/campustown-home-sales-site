# Agent log

Add a dated entry each time you work with your AI coding agent, with the newest entry at the bottom. Each entry records what you asked the agent, what it produced, and what you checked or changed. Paste your key prompts in exactly as you typed them. Include at least one time the agent got something wrong, and how you caught it.

Copy this outline for each entry:

```markdown
## YYYY-MM-DD: What you worked on

- **Asked:** "Paste your prompt here."
- **Agent produced:** What it made or changed.
- **Checked or changed:** How you checked it, and what you fixed.
```

## 2026-11-15: Add city selector to the dashboard

- **Asked:** "Update the existing College Town Home Sales Dashboard by adding an interactive dropdown menu that allows users to select one of the 18 cities."
- **Agent produced:** Added a city dropdown and four calculated metrics to `index.html`, while preserving the existing median-price bar chart and design.
- **Checked or changed:** Verified the CSV produces 18 cities and 35,402 included sales after excluding prices under $10,000. The first JavaScript syntax check used an unsupported process-substitution path and failed; rerunning it through a temporary file passed.

## 2026-11-15: Improve dashboard summaries and responsive layout

- **Asked:** "Review and improve my existing College Town Home Sales Dashboard without removing any current features. Add summary cards for total home sales, overall median sale price, and cities included; improve the layout, spacing, colors, responsive chart and city selector; verify calculations from the CSV; continue excluding sales under $10,000; format prices as whole dollar amounts with commas; and fix errors or bugs."
- **Agent produced:** Added three data-driven summary cards, improved spacing and color treatment, made the selector and chart more usable on small screens, and replaced chart string interpolation with DOM construction.
- **Checked or changed:** Recalculated the CSV directly: 35,402 included sales, 18 cities, and a $410,000 overall median. JavaScript syntax and Git whitespace checks passed. Browser checks confirmed the desktop summary, 18 bars, mobile layout at 390px, city selection updates, and no console errors.
