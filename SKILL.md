---
name: manufacturing-quality-tool-builder
description: Use this skill when the user wants to turn manufacturing, quality control, yield, defect, WIP, labor, capacity, or cost data into a simple GitHub-ready analysis web tool with formulas, clear outputs, and improvement suggestions.
---

# Manufacturing Quality Tool Builder

Use this skill to build a small manufacturing or quality-management web tool, especially for classroom projects, factory observation notes, yield analysis, WIP analysis, labor efficiency, defect analysis, or improvement proposals.

## Workflow

1. Define the manufacturing problem.
   - Write one sentence describing the factory or quality issue.
   - Identify input data, such as production quantity, good quantity, defect quantity, WIP quantity, labor count, work hours, target yield, standard hourly capacity, unit cost, or rework cost.
   - Identify outputs, such as yield, defect rate, quality loss, target gap, output per person, output per person-hour, WIP coverage time, capacity achievement rate, or improvement advice.

2. Confirm formulas.
   - Yield rate = good quantity / total quantity * 100%.
   - Defect rate = defect quantity / total quantity * 100%.
   - Quality loss cost = defect quantity * (unit manufacturing cost + unit rework cost).
   - Output per person = good quantity / labor count.
   - Output per person-hour = good quantity / (labor count * work hours).
   - WIP coverage time = WIP quantity / hourly good output.
   - Capacity achievement rate = hourly good output / standard hourly capacity * 100%.

3. Build the tool.
   - Prefer one `index.html` file with embedded CSS and JavaScript for simple GitHub Pages delivery.
   - Put the working calculator or analysis tool on the first screen.
   - Use Traditional Chinese labels for Taiwan classroom assignments.
   - Make all important assumptions visible in the result or README.

4. Add interpretation.
   - If actual yield is above target, suggest maintaining process stability.
   - If actual yield is slightly below target, suggest checking the main defect categories.
   - If actual yield is far below target, suggest using Pareto analysis and 5M1E cause analysis.
   - If capacity achievement is low, suggest checking labor allocation, bottleneck stations, and equipment waiting time.
   - If WIP coverage time is high, suggest checking queue, transportation, waiting, and process balance.

5. Verify before delivery.
   - Test one sample case manually.
   - Check that empty or zero values do not break the page.
   - Include a short README with purpose, formulas, and sample results.
   - Provide the GitHub repository URL and GitHub Pages URL when finished.

## Quality Checklist

- The tool works without installation.
- The formulas are shown or explained.
- Results are easy to read on phone and desktop.
- The topic clearly connects to manufacturing, quality management, WIP, labor efficiency, or process improvement.
- The repository includes `index.html` and `README.md`.
