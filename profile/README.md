# EsportsMath Labs (Applied Probability Institute)

[![Portal](https://img.shields.io/badge/Portal-esportsmath.org-00E5FF.svg)](https://esportsmath.org)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![Open Science](https://img.shields.io/badge/Data-Open%20Access-purple.svg)](https://esportsmath.org/en/research/)
[![Affiliation](https://img.shields.io/badge/Institution-Applied%20Probability%20Institute-gold.svg)](https://esportsmath.org/en/about/)

**EsportsMath Labs** is an independent quantitative research collective operating under the **Applied Probability Institute**. We engineer deterministic game-theoretic draft models, open-access stochastic simulation engines, and discrete probability benchmarks for Counter-Strike 2 (CS2), Dota 2, and professional esports market economies.

---

## 🔬 Core Open-Source Repositories

| Repository | Focus & Domain | Stack / Engine | License |
| :--- | :--- | :--- | :--- |
| **[`cs2-veto-minimax`](https://github.com/esportsmath-labs/cs2-veto-minimax)** | Backward induction minimax pick/ban veto engine for CS2 Active Duty 7-map pool (Bo1, Bo3, Bo5) | TypeScript / ESM | MIT |
| **[`elo-glicko2-predictor`](https://github.com/esportsmath-labs/elo-glicko2-predictor)** | Dual Elo / Glicko-2 rating engine with conditional series distribution estimators (Bo1/Bo3/Bo5) | TypeScript / ESM | MIT |
| **[`round-ev-tracker`](https://github.com/esportsmath-labs/round-ev-tracker)** | Markov state machine for MR12 economy cascades, pistol momentum decay & Half-Kelly bet sizing | TypeScript / ESM | MIT |
| **[`player-impact-rar`](https://github.com/esportsmath-labs/player-impact-rar)** | Role-Adjusted Rating (RAR z-scores) & Negative Binomial kill-prop distribution generator | TypeScript / ESM | MIT |
| **[`research-papers`](https://github.com/esportsmath-labs/research-papers)** | Preprints, 10,000-map telemetry datasets, Python reproducibility suites, and BibTeX sources | Open Science / CSV / Py | CC-BY-4.0 |

---

## 📊 Research Pillars

1. **Game-Theoretic Draft Equilibria**: Recursive backward induction and subgame perfect equilibria across the Active Duty 7-map pool (Mirage, Inferno, Nuke, Dust II, Ancient, Anubis, Vertigo), quantifying pick advantage and map pool depth asymmetry.
2. **Dynamic Skill Calibration & Volatility**: Implementation of Mark Glickman's Glicko-2 algorithm ($\mu$, $\phi$, $\sigma$) calibrated specifically to esports roster continuity, regional latency boundaries, and Tier-1 tournament decay rates.
3. **Discrete Markovian State Transitions**: Modeling MR12 economy cascades, pistol round conversion momentum ($+24.8\%$ second-round cascade multiplier), and capital growth under fractional Half-Kelly sizing ($f^* = \frac{p(b+1)-1}{2b}$).
4. **Role-Standardized Performance & Prop Overdispersion**: Normalization of performance metrics (KPR, ADR, Opening Duel success) across positional roles (Entry, AWPer, Rifler, Support, IGL) utilizing Negative Binomial distributions for overdispersed prop pricing.

---

## 🌐 Publications & Live Interactive Calculators

All research papers, empirical datasets, and interactive zero-runtime JavaScript calculators are accessible open-access at **[esportsmath.org](https://esportsmath.org)**:
- **CS2 Veto & Map Draft Simulator**: [esportsmath.org/en/tools/map-veto-analyzer/](https://esportsmath.org/en/tools/map-veto-analyzer/)
- **Match & Series Probability Predictor**: [esportsmath.org/en/tools/elo-calculator/](https://esportsmath.org/en/tools/elo-calculator/)
- **In-Play Round Momentum & EV Tracker**: [esportsmath.org/en/tools/round-ev-tracker/](https://esportsmath.org/en/tools/round-ev-tracker/)
- **Player Prop & Performance Model**: [esportsmath.org/en/tools/player-impact-calculator/](https://esportsmath.org/en/tools/player-impact-calculator/)
- **10,000-Map Telemetry Preprint**: [esportsmath.org/research/cs2-dota2-tier1-telemetry-study/](https://esportsmath.org/en/research/cs2-dota2-tier1-telemetry-study/)

---

### Citation

If you utilize our algorithms, datasets, or simulation engines in your research or applications, please cite:

```bibtex
@article{esportsmath2026telemetry,
  title={Empirical Analysis of In-Play Economy Cascades and Map Veto Equilibria in Professional Counter-Strike 2: A 10,000-Map Telemetry Study},
  author={{EsportsMath Labs}},
  journal={Applied Probability Institute Research Hub},
  year={2026},
  url={https://esportsmath.org/en/research/cs2-dota2-tier1-telemetry-study/}
}
```
