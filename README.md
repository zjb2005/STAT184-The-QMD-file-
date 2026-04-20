# HW #4.3 — First Data Analysis QMD

Repo for STAT 184 HW #4.3. Everything for the assignment is built from a single Quarto document that renders to PDF.

## What this project is about

Three separate mini-analyses, all written up in one `.qmd` file:

1. **Busiest Airports (2020–2025)** — annual passenger traffic at ATL, FRA, PKX, DXB, LAX, and LHR, pulled into a table and a line chart to look at how air travel recovered after COVID.
2. **Monte Carlo Numerical Integration** — estimating the area under the Chi-squared PDF (df = 5) by random sampling at n = 10, 100, 1,000, and 10,000 points.
3. **GenAI Prompting Comparison** — tidying the `calcium.csv` data, writing a plan-informed prompt for Claude Sonnet 4.6, and comparing its output against the generic prompt output the instructor provided.

## Where the data came from

- Airport passenger numbers: public airport statistics and Wikipedia (in millions).
- `calcium.csv`: provided by the instructor. Two treatment groups (Null Treatment, 15 women; Diet/Exercise, 16 women) measured at Year 0 through Year 3.
- Generic prompt PNGs (`generic_group_means.png`, `generic_individual_lines.png`): provided by the instructor, used only for comparison in Section 3.

## Current plan

Full plan is in `PLAN.md`. Short version: finish the QMD, render it to PDF, keep the repo clean with branches and issues, push everything before the deadline.

## How the repo is organized

```
.
├── README.md                     # this file
├── PLAN.md                       # project + repo plan
├── hw4.3JunboZhaoV6.qmd          # main Quarto source
├── hw4.3JunboZhaoV6.pdf          # rendered output
├── calcium.csv                   # tidied-from data for Section 3
├── generic_group_means.png       # instructor-provided comparison image
└── generic_individual_lines.png  # instructor-provided comparison image
```

Branches:
- `main` — graded version, only updated through pull requests.
- `dev` — where new work actually happens before it gets merged.

## How to reproduce

1. Clone the repo.
2. Open `hw4.3JunboZhaoV6.qmd` in RStudio.
3. Make sure `tidyverse`, `knitr`, and `kableExtra` are installed.
4. Click Render (or run `quarto render hw4.3JunboZhaoV6.qmd`). The PDF should build without edits as long as `calcium.csv` and the two PNGs are sitting next to the QMD.

## Contact

Junbo Zhao
Email: nmsl24371@gmail.com/jzz5658@psu.edu
