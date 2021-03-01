# Introduction

In this project, I build a generative adversarial network (GAN) for the generation of financial time-series. To capture the sequential properties of financial time-series, the generator and discriminator use a temporal convolutional network (TCN)

# Notebooks

GAN_sine_cosine.ipynb: This notebook can be used to generate new multivariate sine/cosine waves. It was used to fine tune all the model parameters.

GAN_financial_time_series.ipynb: This notebook is used to generate new financial time-series observations. The dataset is created within the notebook. The parameters for the reproduction of the final report results are already preset.

# Parameters
window_size: This parameter determines the length of each observations for both, the training samples and the generation of new samples

ticker: The ticker of the underlying asset. Please refer to https://finance.yahoo.com/ for valid tickers

period: The trading period we want to fetch from yahoo (valid periods: 1d,5d,1mo,3mo,6mo,1y,2y,5y,10y,ytd,max)

interval: The sampling interval (valid intervals: 1m,2m,5m,15m,30m,60m,90m,1h,1d,5d,1wk,1mo,3mo)
