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
