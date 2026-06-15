# Final Results Freeze

**Generated:** 2025-10-07T20:37:33

This folder contains a frozen snapshot of the key artifacts used in the thesis.

## Structure

- `kenya/` — Prediction outputs, metrics, probabilities, and figures  
- `tanzania_bottlenecks/` — Regression summary, coefficients, residual diagnostics  
- `shared/` — Ablation CSV + ablation plots  
- `models/semdr_lite/` — Trained light classifier artifacts (e.g., calibrated SVM, label encoder)

## Kenya (current best run)
- Accuracy:  0.51440329218107
- Macro-F1:  0.3408457096809394
- Weighted-F1: 0.4849802374471749

## Reproduction Notes
- Kenya predictions originated from `outputs/kenya_test_predictions_with_precedents.csv`
- Figures came from `outputs/figures_kenya/` and `outputs/figures_explainability/`
- Tanzania bottleneck regression: see `outputs/tanzania_regression_summary.txt` and figures in `outputs/figures_tanzania/`
- Ablation charts + combined CSV are under `outputs/figures_ablation/` and `outputs/ablation_combined.csv`

> If you rerun experiments, re-execute this script to refresh the freeze.
