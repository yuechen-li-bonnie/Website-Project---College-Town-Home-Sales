# Agent log

Add a dated entry each time you work with your AI coding agent, with the newest entry at the bottom. Each entry records what you asked the agent, what it produced, and what you checked or changed. Paste your key prompts in exactly as you typed them. Include at least one time the agent got something wrong, and how you caught it.

Copy this outline for each entry:

```markdown
## YYYY-MM-DD: What you worked on

- **Asked:** "Paste your prompt here."
- **Agent produced:** What it made or changed.
- **Checked or changed:** How you checked it, and what you fixed.
```
## 2026-11-19: College-Town Housing Market Dashboard

- **Asked:** I used ChatGPT Codex (GPT-6 Luna). My initial prompt was:

  Read AGENTS.md and docs/data_description_sheet.md first.

  Then replace the placeholder index.html with a clean, modern, responsive College-Town Housing Market Dashboard based on data/college_town_home_sales.csv.

  The webpage should include:
  1. A clear title and short introduction explaining the dataset.
  2. Summary statistics, including the total number of home sales and the number of cities.
  3. A bar chart comparing the median home sale price across cities, sorted from highest to lowest.
  4. A table showing each city's median sale price and number of sales.

  Exclude sales under $10,000 from the price analysis, and clearly state this rule on the webpage. Format all prices as whole US dollars.

  Use HTML, CSS, and JavaScript compatible with the existing GitHub Pages setup. Make the design visually appealing and easy to read on desktop and mobile.

  Do not modify the original files in the data/ folder. Verify that the calculations and webpage work correctly.

- **Agent produced:** Codex created a responsive dashboard showing 35,442 home sales across 18 cities, including summary statistics, a median price bar chart, and a city sales table.

- **Checked or changed:** I reviewed the code changes and confirmed that only index.html was modified. I checked the median price calculations, the $10,000 exclusion rule, and the displayed chart and table. My second prompt was:

  "Looks good. Commit this change on a new branch, push it to GitHub, and open a pull request into main."

  Codex created Pull Request #1. I merged it into main, confirmed successful GitHub Pages deployment, and verified that the public repository and website were accessible.
