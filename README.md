Description: daily OHLC, Last, Close, Total Trade Quantity, and Turnover (Lacs) covering 2014–2018 with dense liquidity signals for indicator construction and volume aware slicing.
Appliclication: multivariate LSTM regression with technical indicators and liquidity features; suitable for indicator ablation and volume/turnover slice stability analyses.
Attributes: Date, Open, High, Low, Last, Close, Total Trade Quantity, Turnover (Lacs); instances across 2014–2018 with ample liquidity signals; rich ground for indicators/ablation.
Algorithms used: Multivariate LSTM regression with indicators; univariate LSTM baseline; ARIMA baseline; tree based tabular baseline on indicators for contrast.
