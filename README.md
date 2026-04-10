[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/01780565306/ReliabilityAware-HEMS/blob/main/ReliabilityAware_HEMS_KayesBinYousuf.ipynb)

# Reliability-Aware HEMS: Full Extension of LT-ST MPC Framework

**Author:** Kayes Bin Yousuf | Incoming MS ECE, Clarkson University

**Based on:** Lin, Zamora, Jiang et al. - Multi-Level Home Energy
Management System with LT-ST MPC
## Overview
A reliability-aware extension to the LT-ST MPC home energy
management framework, adding uncertainty quantification and
CVaR-robust dispatch to the original paper's formulation.

## Key Contributions
- Heteroscedastic Conformal Prediction intervals for PV forecasting
- CVaR(95%) via scenario reduction (post-hoc on dispatch sequences)
- LT layer: Deterministic vs CVaR-aware dispatch comparison
- ST layer: Full uncertainty correction extending Eq. 36-42
- 24h rolling horizon simulation (1h LT + 5-min ST intervals)
- 5 result figures (A-E): dispatch, SoC, cost, coverage, grid power

## How to Run
Click the **Open in Colab** badge above to run instantly.
No external dataset required - NREL-like profiles are generated
programmatically.
