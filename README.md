<p align="center">
  <a href="https://www.kaggle.com/code/hassanjameelahmed/nike-nke-stock-exploratory-data-analysis" target="_blank">
    <img src="2017.png" alt="ADBE" width="500">
  </a>
</p>

# Nike (NKE) Stock Market Price Data (2000-2026) -> PRD (app.md)
## e. Dataset Coverage
This dataset comprehensively covers the daily stock market trading data for Nike Inc. (Ticker: NKE), an American multinational corporation engaged in the design, development, manufacturing, and worldwide marketing and sales of footwear, apparel, equipment, accessories, and services. The data reflects trading activity on major US exchanges.

## g. Provenance and Data Transformations
**Provenance**: The original source of the data originates from established global financial markets tracking the New York Stock Exchange.
**Transformations**: The raw, tick-by-tick trading data has been transformed and aggregated into standard daily summary metrics (Open, High, Low, Close, and Volume). The data is often adjusted to account for historical corporate actions such as stock splits and dividend distributions to ensure a continuous and smooth time series for accurate long-term analysis.

## i. Biggest Problems and Challenges Facing This Project
1. **Handling Market Anomalies & Non-Trading Days**: Dealing with gaps in the continuous timeline caused by weekends, unpredicted market closures, and designated public holidays.
2. **Corporate Adjustments**: Accurately back-adjusting historical prices for forward/reverse stock splits to maintain statistical consistency.
3. **Data Integrity**: Ensuring that out-of-bounds anomalies or API transmission errors do not corrupt the continuity of the historical data over a span of two-plus decades.
