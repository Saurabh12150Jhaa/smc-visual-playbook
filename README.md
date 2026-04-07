# SMC Visual Playbook

> **NIFTY EDGE v4.0** — A visual-first Smart Money Concepts (SMC) trading playbook for Indian options markets.

[![Live Demo](https://img.shields.io/badge/Live-GitHub%20Pages-00d4aa?style=for-the-badge&logo=github)](https://saurabh12150jhaa.github.io/smc-visual-playbook/)

---

## Preview

<p align="center">
  <a href="https://saurabh12150jhaa.github.io/smc-visual-playbook/">
    <img src="https://img.shields.io/badge/OPEN%20LIVE%20PLAYBOOK-00d4aa?style=for-the-badge&logoColor=white&logo=googlechrome" alt="Open Live Playbook" />
  </a>
</p>

---

## What Is This?

A **single-page interactive playbook** that teaches SMC trading for Nifty/BankNifty options using **SVG diagrams, visual charts, and interactive tools** — not walls of text. Built for traders who learn by *seeing*.

---

## Features

### Visual Diagrams (SVG)
| Diagram | What It Shows |
|---------|--------------|
| **Order Block Formation** | OB candle identification, impulse, FVG zone, retrace path, entry point, SL placement |
| **OB Refinement Flow** | 15-min → 5-min → 1-min zoom with entry types (OB Open / 50% Fib / Wick Base) |
| **3 BOS Types** | Side-by-side: Type 1 (body > wick), Type 2 (body > body), Type 3 (wick only) |
| **CHoCH + Two Rules** | Full reversal flow with "DO NOT ENTER" warning → retrace → Rule 2 confirmation |
| **Liquidity Sweep** | Retail stops, sweep wick, volume spike, OB formation, reversal entry |
| **Killzone Timeline** | Institutional activity curve across 09:15–15:10 IST with strategy annotations |
| **PA Trailing System** | Price path with HL trail, T1/T2 partial exits, 40/30/30 rule visualization |

### Strategy Cards
- **S11** — Liquidity Sweep Reversal (48% WR, 1:3.3 R:R, +₹5,270 EV)
- **S12** — FVG Fill + OB Confluence (52% WR, 1:2.4 R:R, +₹3,590 EV)
- **S13** — BOS Continuation (45% WR, 1:2.6 R:R, +₹2,925 EV)
- **S14** — CHoCH Reversal (42% WR, 1:3.3 R:R, +₹5,030 EV)

Each with step-by-step flow boxes showing the complete entry process.

### Interactive Tools
| Tool | Description |
|------|-------------|
| **Pre-Trade Checklist** | 14-item interactive checklist with GO / NO-GO indicator |
| **Trade Scoring Calculator** | 9-criteria scorer (0–12) with position sizing guidance |
| **Rule Quiz Flashcards** | 25 cards with show/hide answers, correct/review tracking |
| **Notes & Journal** | Persistent daily notes + observations (localStorage) |

### Content Sections
- 9 Iron Rules with circuit breakers (2% daily / 4% weekly / 8% monthly)
- Tradable OB 8-Feature checklist (5 mandatory + 3 confluence)
- Option buying rules (strike selection, expiry, theta awareness)
- OI Confluence (5 rules combining SMC + Open Interest)
- Advanced tools: Volume Profile, Delta Volume, aVWAP, IV Percentile, Multi-Index Divergence
- IST real-time clock

---

## Tech Stack

- **Zero dependencies** — pure HTML + CSS + vanilla JS
- **SVG diagrams** — no external images or libraries
- **localStorage** — for notes persistence
- **Single file** — everything in one `index.html`

---

## Quick Start

```bash
# Clone
git clone https://github.com/Saurabh12150Jhaa/smc-visual-playbook.git

# Open locally
open index.html
```

Or just visit the **[Live Demo](https://saurabh12150jhaa.github.io/smc-visual-playbook/)**.

---

## Related Projects

| Project | Description | Link |
|---------|-------------|------|
| **SMC Trading Strategies** | 10-strategy dashboard with learning progress | [Live](https://saurabh12150jhaa.github.io/smc-trading-strategies/) · [Repo](https://github.com/Saurabh12150Jhaa/smc-trading-strategies) |
| **SMC Trading Terminal** | Terminal-style rulebook with collapsible sections | [Live](https://saurabh12150jhaa.github.io/smc-trading-terminal/) · [Repo](https://github.com/Saurabh12150Jhaa/smc-trading-terminal) |
| **SMC Trading Windows** | Visual killzone patterns with SVG diagrams & live timeline | [Live](https://saurabh12150jhaa.github.io/smc-trading-windows/) · [Repo](https://github.com/Saurabh12150Jhaa/smc-trading-windows) |

---

## Disclaimer

> 89% of Indian F&O traders lose money (SEBI Jan 2023). This is an **educational tool**, not financial advice. Consult a SEBI-registered advisor before trading. Trade only with capital you can afford to lose.

---

*NIFTY EDGE v4.0 — Built by Saurabh Jha. Based on Vertex SMC, KenneDyne Spot, PR Sundar, ICT, and live Indian market experience.*
