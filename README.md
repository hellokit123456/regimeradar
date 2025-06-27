# regimeradar
# SOC Regime Radar

The SOC Regime Radar project is a data-driven system developed to detect and visualize market mood using high-frequency microstructure data. The project processes large datasets of bid and ask prices to identify different market regimes, such as stable, volatile, or imbalanced conditions, using structured slicing, statistical analysis, and visual exploration.

## Objective

To analyze order book microstructure data, especially bid and ask price movements, in order to identify patterns that reveal the mood or state of the market. The system helps detect transitions between market regimes and provides insight into liquidity, volatility, and order flow behavior.

## Key Features

* Efficient reading and manipulation of large bid-ask datasets using pandas and numpy
* Array slicing and rolling window logic for time-based and event-based feature extraction
* Visualization of spreads, mid-price dynamics, and imbalance metrics using matplotlib
* Scalable framework to handle high-frequency or full-depth order book data
* Insightful plots to reveal transitions in market regimes based on structure and activity

## Technologies Used

* Python
* pandas
* numpy
* matplotlib



## Insights

* Rapid widening of bid-ask spread may indicate market stress or a regime shift
* Sustained order book imbalance can show directional bias or lack of liquidity
* Volatility in mid-price series is often an early indicator of mood change
* Microstructure features offer a reliable signal of market condition even without trade data

## Possible Extensions

* Use machine learning models to classify market regimes based on extracted features
* Integrate real-time data sources for live regime tracking
* Apply analysis across multiple instruments or asset classes
* Build a dashboard to monitor regime changes continuously.
