# pv-yield-stimative
P50 and P90 stimative

In order to develop predictive control algorithms for efficient energy management and monitoring for grid connected photovoltaic systems, accurate and reliable photovoltaic (PV) power forecasts are required. A PV yield prediction system is presented based on an irradiance forecast model and a PV model. The PV power forecast is obtained from the irradiance forecast using the PV model. The proposed irradiance forecast model is based on multiple feed-forward neural networks. The global horizontal irradiance forecast has a mean absolute percentage error of 3.4% on a sunny day and 23% on a cloudy day for Stuttgart. PV power forecasts based on the neural network irradiance forecast have performed much better than the PV power persistence forecast model.

# Info
What is the difference between multi-year time series and TMY data?
A time series is a sequence of data, modeled or measured, representing regular intervals over a period of time (several years in the case of a multi-year time series). Solargis multi-year time series is most typically used for following purposes:

To understand seasonal and inter-annual variability of solar resource
To understand occurrence of extreme irradiance and temperature events - for design optimization of solar power systems
Input data for energy simulation of solar power systems
For accuracy enhancement of long-term satellite-derived irradiance estimates - when high-quality irradiation measurements are available at project site

A Typical Meteorological Year (TMY) dataset is derived from a multi-year time series.

TMY data is primarily used for energy simulation purposes, as popular simulation software such as PVsyst, SAM, etc. typically work with 8760 hourly values representing a typical year. The main reason for the popularity of TMY dataset for solar energy simulation is compatibility of such data with popular energy simulation software and speed of simulation.

However, as preparation of TMY data results in loss of information, it is recommended to use a multi-year time series for energy simulation purposes when possible.

https://solargis.com/docs/product-guides/time-series-and-tmy-data/multi-year-time-series-vs-tmy-data
