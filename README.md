# Who Wins the Groza? A Statistical Model for Predicting College Football's Best Kicker Award

A data-driven analysis of the Lou Groza Award (college football's top placekicking honor) that identifies the statistical thresholds required to win and predicts winners with 95.8% accuracy.

## Overview

This research analyzes 70 elite college football kickers (2001-2025) to establish objective performance benchmarks that separate Groza Award winners from finalists. The analysis reveals that five statistical categories (overall FG%, total FGM, FGM from 50+ yards, longest FG distance, and FGM per game) drive award selection.

## Key Findings

- Groza winners outperform runners-up in 15 of 17 statistical categories analyzed
- A 10-point scoring system predicts winners with 95.8% accuracy when a clear statistical leader exists
- Kickers scoring 9 points in the scoring system historically win 77.8% of the time (100% when they're the statistical leader)
- Every Groza winner since 2015 has tied or outscored all runners-up using this model

## Repository Contents

- `kicker_data.csv` — Complete dataset of 70 elite kickers with 28 statistical categories (2001-2025)
- `calculator.html` — Interactive scoring calculator for evaluating kicker performance in real-time
- `methodology.md` — Detailed explanation of statistical methods and thresholds

## The Five Laws of Lou

To contend for the Groza Award, kickers need to meet these benchmarks:

| Category | Minimum | Ideal |
|----------|---------|-------|
| **FG% (Total)** | 81.8% | 91.46%+ |
| **FGM (Total)** | 15 | 24+ |
| **FGM from 50+** | 1 | 2+ |
| **Longest FG** | 47 yards | 55+ yards |
| **FGM Per Game** | 1.1 | 1.79+ |

## Using the Calculator

Open `calculator.html` in any web browser and enter a kicker's season statistics. The calculator will:
- Score the kicker on a 10-point scale
- Show which benchmarks they meet or exceed
- Estimate their historical win probability

## Data Sources

- Official NCAA Records
- ESPN
- Sports Reference
- CFBStats.com

## Methodology

This analysis uses descriptive statistics (means, medians, percentiles) to establish minimum and ideal performance thresholds. The "Ideal" threshold represents the top 90% average of winners (excluding bottom 3 outliers per category).

A 10-point scoring rubric assigns:
- **1 point** for meeting minimum thresholds
- **2 points** for exceeding ideal thresholds

Backtesting against historical results (2004-2025) validates the model's predictive power.

## Key Limitations

- Analysis includes bowl and playoff game statistics, which occur after Groza is awarded 
- Does not adjust for weather, bad snaps, or holds
- Does not factor in "clutch" moments or game-winning FGs
- Sample size: 70 kickers over 22 years

See the full paper for complete methodology and limitations.

## Full Research Paper

For the complete analysis, findings, and academic discussion, see:
[Who Wins the Groza? - Full Paper](https://andrewelsass.com/groza-award-analysis/)

## Author

Andrew Elsass

## License

This research and data are provided as open-source materials for educational and analytical purposes.