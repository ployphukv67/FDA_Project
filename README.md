# FDA_Project

Industry bubble and crash early-warning system for 48 Fama-French industries.

| Path | Content |
|---|---|
| `FDA_Bubble_Detection_v5.ipynb` | Main notebook (GSADF, HMM, walk-forward Logit / Random Forest, breadth, backtest), saved with all outputs |
| `data/` | Local data snapshot read by the notebook (see `data/README.md`) |
| `figures/` | Charts saved by the notebook |
| `FDA_Project_Final.ipynb` | Earlier S&P 500 version |

Run: `pip install hmmlearn shap xlrd`, then run the notebook from the repository root. A full run takes about 20 minutes.
