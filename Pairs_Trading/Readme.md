# Finding Candidates for Pairs-Trading Research

**Which Indian equity pairs might move together closely enough to justify a further trading investigation?**

This early notebook reduces the dimension of NSE stock data with principal components, groups stocks with DBSCAN clustering and applies statistical screens to candidate pairs. It then constructs rolling price-ratio z-scores for illustrative entry and exit signals.

## What the work does—and what the result means

The main contribution is a candidate-discovery workflow. A low screening p-value does not establish a tradable, persistent relationship. The original note reports 38 pairs outperforming the NIFTY 50 in 2015–2019; that historical statement has **not been independently revalidated** for selection leakage, costs, borrowing, survivorship or risk-adjusted performance. It is not presented as a current profitable strategy.

## Inspect the notebook

[Pairs-discovery notebook](Pairs-Trading%20using%20Unsupervised%20Machine%20Learning.ipynb) · [Price data](NseFinalData.csv) · [Industry data](Stocks_Industry.csv)

The notebook is large and contains saved outputs. Read the data range, candidate-selection step and evaluation period together before interpreting its comparisons. A stronger follow-up would separate pair discovery from later trading evaluation and model execution costs and hedge construction explicitly. No such new backtest is claimed here.

[Earlier-project index](../README.md) · [Current quantitative work](https://github.com/Fakhruddin12)
