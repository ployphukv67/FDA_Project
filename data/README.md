# Data snapshot

Raw input files for `FDA_Bubble_Detection_v5.ipynb`. The notebook reads these files only; it does not download anything.

Downloaded on 2026-11-11.

| File | Content | Source |
|---|---|---|
| `49_Industry_Portfolios_CSV.zip` | Monthly industry returns (value- and equal-weighted), firm counts, firm size, BE/ME | Ken French Data Library |
| `49_Industry_Portfolios_daily_CSV.zip` | Daily industry returns | Ken French Data Library |
| `F-F_Research_Data_Factors_CSV.zip` | Mkt-RF, SMB, HML, RF (monthly) | Ken French Data Library |
| `BAA.csv`, `AAA.csv` | Moody's corporate bond yields | FRED |
| `GS10.csv`, `TB3MS.csv` | 10-year Treasury yield, 3-month T-bill rate | FRED |
| `USREC.csv` | NBER recession indicator | FRED |
| `ie_data.xls` | Shiller CAPE (file last saved 2026-10-05) | shillerdata.com |

To update the data, replace the files with newer downloads under the same names and rerun the notebook.
