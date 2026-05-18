# Repository

Companion code for a Medium article.

## Business context

Time series analysis is used for finance, healthcare, industrial IoT, and many other fields. Statistical methods like ARIMA and Exponential Smoothing have been the primary tools for forecasting for decades. More recently, deep learning models such as Long Short-Term Memory networks (LSTMs) and Transformers have redefined the space -- now large language models (LLMs) and changing how we do time series analysis.

Classical and Deep Learning Approaches to Time Series Before the rise of machine learning, time series analysis was largely a domain of statistical models. ARIMA (AutoRegressive Integrated Moving Average) provided a way to model linear dependencies, while seasonal decomposition techniques helped uncover underlying trends. Economists and engineers relied on these methods to forecast stock prices, optimize supply chains, and monitor equipment failures.

Deep learning changed the game. LSTMs and GRUs (Gated Recurrent Units) introduced the ability to capture long-range dependencies in sequential data, making them useful for time series forecasting. CNNs (Convolutional Neural Networks) found applications in irregularly sampled data, while Transformers like Informer and TimeNet extended attention mechanisms to improve efficiency in long time series forecasting. These approaches significantly outperformed classical methods, but they required large labeled datasets, careful feature engineering, and domain-specific model tuning.

## Disclaimer

Educational/demo code only. Not financial, safety, or engineering advice. Use at your own risk. Verify results independently before any production or operational use.

## License

MIT — see [LICENSE](LICENSE).