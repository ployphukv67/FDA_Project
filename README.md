# FDA_Project

Industry Crash-Risk Advisor: monthly industry-level risk monitoring and decision support for 48 Fama-French industries.

| Path | Content |
|---|---|
| `FDA_Crash_Risk_Advisor_v6.ipynb` | Main notebook: Risk Ranking, Run-up Watch, Portfolio Exposure Review, contributing factors, monthly report; saved with all outputs |
| `FDA_Bubble_Detection_v5.ipynb` | Previous research version (bubble and crash early-warning framing), kept for reference |
| `data/` | Local data snapshot read by the notebook (see `data/README.md`) |
| `data.zip` | The same data files in one archive, for uploading to Colab |
| `figures/` | Charts saved by the notebook |
| `csv/` | Result tables exported by the v6 notebook (monthly risk levels since 1960, latest report, Run-up Watch, summary) |

Run locally: `pip install hmmlearn shap xlrd`, then run the notebook from the repository root.

Run in Colab: open `FDA_Crash_Risk_Advisor_v6.ipynb`, drag `data.zip` into the Files panel, then run all cells.

A full run takes about 35 minutes.
