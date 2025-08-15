📊 What does "stationary" mean?

A stationary time series has the following characteristics:

Its mean stays roughly constant over time.

Its variance (spread of values) remains stable.

It does not have trends or strong seasonal effects.

This is important because most traditional time series models (like ARIMA, SARIMA, etc.) require the data to be stationary in order to work correctly.


📊 what should u need about ADF test and KPSS test?

If your goal is data analysis or forecasting, you usually don’t need the full math. You just need to know:

ADF test → checks if a series is stationary by testing for a unit root.

Key output: p-value (if <0.05 → stationary).

Can include lagged terms automatically (autolag) to account for autocorrelation.

KPSS test → also checks stationarity, but opposite null hypothesis:

Null = series is stationary.

Key output: p-value (if <0.05 → reject stationarity).

In practice: people often run both tests together to be more confident.

You just need to know what the test tells you and how to interpret the result, not the derivation.



