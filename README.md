# Banking & Fintech Consumer Complaint Analysis (2017–2023)

I built this project around a cleaned complaints dataset to understand **what banking/fintech customers complain about most**, how complaints change over time, and how companies respond.

## What this analysis answers
- Which **products** generate the most complaints?
- What are the **top issues** customers report?
- Which states show the highest complaint volume?
- What are the most common **company response types**?
- Are responses typically marked as **timely**?

## Quick results from this dataset
- Total complaints analyzed: **62,516**
- Date range: **2017-05-01 → 2023-08-28**
- Top product: **checking or savings account**
- Top issue: **managing an account**
- Top state: **CA**
- Most common response: **closed with explanation**
- Timely response rate: **93.8%**

## Files in this repo
- `consumer_complaint_analysis.ipynb` — notebook (cleaning + analysis + charts)
- `data/consumer_complaints_banking_sample_20000.csv` — representative sample (GitHub-friendly)
- `outputs/` — charts (PNG) and cleaned dataset export (generated when you run the notebook)

## Charts (in outputs/)
- Top products by complaint volume
- Top issues
- Response types
- Top states
- Monthly trend

## How to run
**Google Colab**
1) Open the notebook in Colab.
2) Upload `data/consumer_complaints_banking_sample_20000.csv` (or your full file if you have it).
3) Run all cells.
4) Upload the charts from `outputs/` back to GitHub.

## Notes
- This repo includes a 20k-row sample to keep uploads small. The full cleaned file is ~17.7MB.
