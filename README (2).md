# STR Market Report — Work Sample

A sample short-term-rental market report built to demonstrate reporting approach for a job application (STR Reporting Specialist, Funkit).

**This is a demonstration, not a paid client engagement.** All figures are illustrative and styled after typical AirDNA-format data, clearly labeled as such throughout.

## What's here

- **[View the live report →](https://pranoy71.github.io/str-report-sample/)** — the polished, client-facing deliverable (Sedona, AZ sample market)
- **[STR_Sample_Report_Sedona.xlsx](./STR_Sample_Report_Sedona.xlsx)** — the underlying working sheet: monthly revenue/occupancy/ADR with live formulas (not hardcoded), a comp set with an outlier flagged and excluded from averages, and sourcing notes on every figure

## Approach

- Structured the sheet so figures, sources, and QA notes are all visible — nothing buried in a single summary tab
- Flagged and excluded a comp (Comp D) whose occupancy and revenue sat well outside the range of the rest of the set, with the reasoning documented rather than silently dropped
- Every RevPAR figure computed as a live formula (Occupancy × ADR), not a pasted number, so it recalculates if inputs change
- Report copy written for a business decision-maker: lead with the number that matters (est. annual revenue), then the reasoning behind it

Built by [Bishal Chandra Debnath](https://linkedin.com/in/bishal-chandra-debnath) · [GitHub](https://github.com/Pranoy71)
