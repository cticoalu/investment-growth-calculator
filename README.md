# 📈 Investment Growth Calculator

An interactive, browser-based investment growth calculator with support for custom contributions, **Roth IRA** max contribution modeling, and **401k** max contribution modeling — complete with dual near-term / long-term return rate projections.

🔗 **[Try it live →](https://cticoalu.github.io/investment-growth-calculator/)**

---

## Features

- **Three contribution modes**
  - Custom monthly contribution amount
  - Max Roth IRA — starts at $7,500 (2026) and increases $500/year
  - Max 401k — starts at $24,500 (2026) and increases $1,000/year

- **Dual return rate modeling**
  - Set a near-term rate (e.g. 10.5% based on current Wall Street consensus)
  - Set a long-term steady-state rate (e.g. 7.5% historical average)
  - Choose how many years before the rate transitions
  - Chart highlights the near-term period visually

- **Stacked bar chart** showing year-by-year breakdown of:
  - Initial principal
  - Contributions over time
  - Estimated market returns

- **Hover tooltips** showing total balance, rate applied, and contribution limit for that year

- **Adjustable parameters**
  - Initial investment up to $1,000,000
  - 1–40 year horizon
  - Annual, monthly, or daily compounding
  - Return rates from 1% to 20%

- Fully responsive — works on desktop and mobile
- No dependencies, no backend, no data collected — runs entirely in your browser

---

## Background & Motivation

This tool was built to help visualize the long-term power of compound growth, particularly in the context of tax-advantaged retirement accounts like Roth IRAs and 401ks. It was also designed to reflect real-world market conditions — including the ability to model a higher near-term return rate (based on current analyst forecasts) before transitioning to a more conservative long-term average.

The default near-term rate of **10.5%** reflects the weighted projected 2026 return for a diversified portfolio allocation of Small/Mid Cap (41%), Large Cap Value/Blend (39%), Large Cap Growth (10%), and Global/International (10%), based on analyst consensus as of April 2026.

---

## How to Use

1. Select a contribution mode: **Custom**, **Max Roth IRA**, or **Max 401k**
2. Set your **initial investment** (up to $1,000,000)
3. Adjust your **annual return rates** — near-term and long-term
4. Set your **time horizon** in years
5. Hover over any bar on the chart to see the exact balance and breakdown for that year

---

## Tech Stack

- **HTML/CSS/JavaScript** — single self-contained file, no frameworks
- **[Chart.js 4.4.1](https://www.chartjs.org/)** — for the interactive stacked bar chart
- Hosted via **GitHub Pages**

---

## Disclaimer

This calculator is for **illustrative and educational purposes only**. It does not constitute financial advice. Actual market returns are not guaranteed and will vary. Roth IRA and 401k contribution limits are subject to change by the IRS. Consult a qualified financial advisor before making investment decisions.

---

## Credits

**Designed & built by [Claude](https://claude.ai) (Anthropic)**
*Claude Sonnet 4.6 — April 2026*

Prompted and published by **[C Ticoalu]**

---

*If you find this useful, consider giving it a ⭐ on GitHub!*
