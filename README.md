# FOMC Impact Analysis on Financial Assets: A Quantitative Strategy

This document details a quantitative strategy designed to evaluate the impact of Federal Open Market Committee (FOMC) announcements on financial assets.

## Table of Contents
- [Summary](#summary)
- [Rationale Behind the Strategy](#rationale-behind-the-strategy)
- [Future Recommendations](#future-recommendations)

## Summary
Our quantitative strategy has revealed significant insights into the performance of our investment strategy and thought process. The Sharpe ratio experiences notable decay from an impressive 4.82 during in-sample testing to 1.92 out-of-sample testing. Nevertheless, our strategy consistently outperforms both in-sample and out-of-sample Sharpe ratios when contrasted with a basic entry/exit optimized model. This discrepancy highlights the importance of our unique classification approach, which effectively identifies anomalies tied to Mean Reversion and Trends, especially the post-announcement drift in our segmented data. 

## Rationale Behind the Strategy
- **Objective**: The strategy's primary aim is to discern the impact of FOMC announcements on the Fed Funds rate.
- **Classification**: Announcements are categorized into 'Tightening', 'Easing', or 'No Change' scenarios.
- **Bond Movement Analysis**: The strategy refines its approach by evaluating short-term bond price movements on announcement days, ascertaining whether bond prices closed above or below their previous day's levels.
- **Segmentation**: This methodology creates six distinct situations, providing insights into market anticipations before the FOMC announcements.
- **ETF Analysis**: Further granularity is added by assessing whether the 'SPY' ETF's price lies above or below its 20-day rolling average, capturing potential mean reversion or trending patterns post-announcement.
- **Core Essence**: By integrating well-established financial factors such as mean reversion and trend, the strategy aims to exploit potential market anomalies or patterns succeeding FOMC news releases.

## Future Recommendations
While the current results are promising, future iterations of this strategy should consider:
1. Extending the dataset to include a more extensive range of announcements and market conditions.
2. Integrating machine learning models to refine classifications and predictions further.

![image](https://github.com/jai-chau/FOMCTrading/assets/78785071/5aee794e-f97c-408a-bfe4-bbd04e4516ef)
![image](https://github.com/jai-chau/FOMCTrading/assets/78785071/64f6a22c-5d62-479e-9d96-f85387f7273c)

