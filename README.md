# Creative Agency Project & Retainer Simulator

An interactive financial and capacity modeling sandbox built for freelancers, creative studios, and boutique agencies. Drag sliders and flip operational toggles to stress-test pricing, client volume, scope creep, and subcontracting tradeoffs in real time before committing to new retainers.

![License](https://img.shields.io/badge/license-MIT-111111?style=flat-square)
![Stack](https://img.shields.io/badge/built%20with-HTML%20%7C%20Tailwind%20CSS%20%7C%20Vanilla%20JS-1D3557?style=flat-square)
![Architecture](https://img.shields.io/badge/architecture-Zero--Dependency%20Single%20File-E63946?style=flat-square)

---

## Live Demo

> **Tip:** Once you enable GitHub Pages in your repository settings, replace this link with your live URL:  
> `https://surefirestudios.github.io/agency-retainer-simulator/`

---

## Why I Built This

Most pricing calculators only look at gross revenue, ignoring the hidden operational drag of **unbilled scope creep**, **fixed overhead**, and **weekly capacity limits**. 

This simulator models the real unit economics of a creative studio—pinpointing the exact "sweet spot" where net profit peaks before adding one more client triggers overtime burnout or erodes your effective hourly rate.

---

## Key Features

* **Real-Time Studio Parameters (Sliders):**
  * **Target Hourly Rate:** `$50/hr` to `$300/hr`
  * **Estimated Hours / Client / Month:** `10 hrs` to `120 hrs`
  * **Active Retainer Clients:** `1` to `10` clients
  * **Scope Creep Buffer:** `0%` to `50%` unbilled revision drag
  * **Monthly Fixed Overhead:** `$500` to `$10,000`
* **Pricing & Delivery Levers (Toggles):**
  * **Rush Fee Multiplier (`+25% Rev`):** Models expedited turnaround surcharges on core deliverables.
  * **Hosting & Maintenance (`+$350/client`):** Simulates high-margin recurring support retainers (`+3 hrs/client/mo`).
  * **Subcontract Web Dev (`-40% Hours`):** Trades `30%` of base project revenue to offload `40%` of studio production hours.
  * **Value-Based Pricing (`+20% Cap`):** Applies a `+20%` package premium while capping unbilled scope creep at `5%`.
* **Interactive Dual-Axis Scaling Chart:**
  * Compares **Monthly Net Profit ($)** against **Effective Hourly Rate ($/hr)** across `1–10` active clients.
  * Automatically highlights the studio's **Sweet Spot (`≤ 45 hrs/wk`)** and allows clicking any data column to jump directly to that client load.
* **Dollar & Weekly Hour Waterfall Breakdowns:**
  * Visualizes how much potential value is captured as net profit versus lost to overhead, subcontractors, or unbilled scope creep.
  * Tracks weekly workload against a standard `40-hour` workweek, flagging overtime hours in real time.
* **Dynamic Advisory Engine & Scenario Presets:**
  * One-click presets (**Solo Boutique**, **High-Margin Retainer**, **Agency Scale-Up**) plus context-aware recommendations tailored to your current bottleneck.

---

## Design & Technical Architecture

* **Swiss Geometric UI:** High-contrast editorial grid aesthetic using off-white paper surfaces (`#F8F7F4`), crisp ink borders (`#111111`), tabular monospace numerals (`IBM Plex Mono`), and geometric typography (`Plus Jakarta Sans`).
* **Zero-Build Portability:** Engineered as a self-contained, client-side HTML/CSS/JS application with custom inline SVG rendering—requiring zero backend infrastructure, build steps, or package installs.

---

## Getting Started

1. Clone or download this repository:
   ```bash
   git clone https://github.com/surefirestudios/agency-retainer-simulator.git
   ```
2. Open `index.html` (or `agency_simulator.html`) directly in any modern web browser.

---

## License

This project is open source and available under the [MIT License](https://opensource.org/licenses/MIT).
