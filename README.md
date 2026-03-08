# Solar Savings Calculator

A 30-year cost comparison tool that helps homeowners evaluate the financial impact of investing in solar energy versus continuing to pay traditional electricity bills.

**[Live Demo →](https://mattolan.github.io/SolarCalculator/)**

![HTML](https://img.shields.io/badge/HTML-single%20file-orange)
![License](https://img.shields.io/badge/license-MIT-blue)

## Overview

This calculator models three scenarios side-by-side over a 30-year period:

- **Flat Electricity** — What you'd pay if rates never changed
- **Inflated Electricity** — Projected costs with annual rate increases
- **Solar + Loan** — Total cost of a financed solar installation

It calculates break-even points, cumulative savings, and displays year-by-year comparisons so you can make an informed decision about going solar.

## Features

- **Interactive inputs** — Adjust monthly bill, inflation rate, install cost, loan term, interest rate, and solar offset percentage
- **Summary cards** — At-a-glance 30-year totals for each scenario
- **Year-by-year table** — Detailed annual breakdown with running totals
- **Break-even analysis** — Two modes: Cash Flow (when solar costs less per year) and Investment (when cumulative savings turn positive)
- **Column toggles** — Show/hide flat or inflated electricity columns
- **Diff comparison** — Toggle between flat vs. solar and inflated vs. solar differences
- **Milestone markers** — Visual indicators for warranty period, loan payoff, and break-even year
- **Export to PDF** — Print-friendly styling for saving or sharing results
- **Fully responsive** — Works on desktop, tablet, and mobile
- **Zero dependencies** — Single HTML file, no build tools or frameworks required

## Default Assumptions

| Parameter | Default | Notes |
|-----------|---------|-------|
| Monthly Electric Bill | $300 | Current monthly cost |
| Inflation Rate | 2% | Annual electricity cost increase |
| Solar Install Cost | $29,000 | Total system cost |
| Loan Length | 15 years | Financing term |
| Loan Interest Rate | 6.5% | Annual interest rate |
| Solar Offset | 100% | Percentage of bill covered by solar |

> Defaults are based on typical residential values in Alberta, Canada (2026), where the deregulated electricity market and Micro-Generation Regulation apply.

## Usage

No installation needed. Just open `index.html` in any modern browser.

```bash
# Clone the repo
git clone https://github.com/mattolan/SolarCalculator.git

# Open in your browser
open SolarCalculator/index.html
```

Or visit the [live GitHub Pages site](https://mattolan.github.io/SolarCalculator/).

## Disclaimer

All figures and projections are estimates for general planning purposes only. They do not constitute financial, legal, or professional advice. Consult a qualified solar installer and financial advisor before making investment decisions.
