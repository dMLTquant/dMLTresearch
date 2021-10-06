[//]: # "START - Navigation between Markdown pages inside of GitHub."

••• **[home](/README.md)** ••• **[docs](/docs/index.md)** ••• **[scripts](/scripts/index.md)** •••

[//]: # "END - Navigation between Markdown pages inside of GitHub."

---[//]: # "START - Navigation between Markdown pages inside of GitHub."

••• **[home](/README.md)** ••• **[docs](/docs/index.md)** ••• **[scripts](/scripts/index.md)** •••

[//]: # "END - Navigation between Markdown pages inside of GitHub."

---[//]: # "START - Navigation between Markdown pages inside of GitHub."

••• **[home](/README.md)** ••• **[docs](/docs/index.md)** ••• **[scripts](/scripts/index.md)** •••

[//]: # "END - Navigation between Markdown pages inside of GitHub."

---[//]: # "START - Navigation between Markdown pages inside of GitHub."

••• **[home](/README.md)** ••• **[docs](/docs/index.md)** ••• **[scripts](/scripts/index.md)** •••

[//]: # "END - Navigation between Markdown pages inside of GitHub."

---[//]: # "START - Navigation between Markdown pages inside of GitHub."

••• **[home](/README.md)** ••• **[docs](/docs/index.md)** ••• **[scripts](/scripts/index.md)** •••

[//]: # "END - Navigation between Markdown pages inside of GitHub."

---[//]: # "START - Navigation between Markdown pages inside of GitHub."

••• **[home](/README.md)** ••• **[docs](/docs/index.md)** ••• **[scripts](/scripts/index.md)** •••

[//]: # "END - Navigation between Markdown pages inside of GitHub."

---[//]: # "START - Navigation between Markdown pages inside of GitHub."

••• **[home](/README.md)** ••• **[docs](/docs/index.md)** ••• **[scripts](/scripts/index.md)** •••

[//]: # "END - Navigation between Markdown pages inside of GitHub."

---[//]: # "START - Navigation between Markdown pages inside of GitHub."

••• **[home](/README.md)** ••• **[docs](/docs/index.md)** ••• **[scripts](/scripts/index.md)** •••

[//]: # "END - Navigation between Markdown pages inside of GitHub."

---[//]: # "START - Navigation between Markdown pages inside of GitHub."

••• **[home](/README.md)** ••• **[docs](/docs/index.md)** ••• **[scripts](/scripts/index.md)** •••

[//]: # "END - Navigation between Markdown pages inside of GitHub."

---[//]: # "START - Navigation between Markdown pages inside of GitHub."

••• **[home](/README.md)** ••• **[docs](/docs/index.md)** ••• **[scripts](/scripts/index.md)** •••

[//]: # "END - Navigation between Markdown pages inside of GitHub."

---[//]: # "START - Navigation between Markdown pages inside of GitHub."

••• **[home](/README.md)** ••• **[docs](/docs/index.md)** ••• **[scripts](/scripts/index.md)** •••

[//]: # "END - Navigation between Markdown pages inside of GitHub."

---[//]: # "START - Navigation between Markdown pages inside of GitHub."

••• **[home](/README.md)** ••• **[docs](/docs/index.md)** ••• **[scripts](/scripts/index.md)** •••

[//]: # "END - Navigation between Markdown pages inside of GitHub."

---[//]: # "START - Navigation between Markdown pages inside of GitHub."

••• **[home](/README.md)** ••• **[docs](/docs/index.md)** • [macroeconomics](/docs/index.md#macroeconomics) • [technical analysis](/docs/index.md#technical-analysis) ••• **[scripts](/scripts/index.md)** •••

[//]: # "END - Navigation between Markdown pages inside of GitHub."

---

# Autoregressive Integrated Moving Average (ARIMA)

<details><summary>resources</summary>

---

- [Investopedia | Autoregressive Integrated Moving Average](https://www.investopedia.com/terms/a/autoregressive-integrated-moving-average-arima.asp)

---

</details>

An autoregressive integrated moving average, or ARIMA, is a statistical analysis model that uses time series data to either better understand the data set or to predict future trends.

A statistical model is autoregressive if it predicts future values based on past values. For example, an ARIMA model might seek to predict a stock's future prices based on its past performance or forecast a company's earnings based on past periods.

### An ARIMA model components

- `Autoregression (AR)`
  - refers to a model that shows a changing variable that regresses on its own lagged, or prior, values.
- `Integrated (I)`
  - represents the differencing of raw observations to allow for the time series to become stationary
  - i.e., data values are replaced by the difference between the data values and the previous values.
- `Moving average (MA)`
  - incorporates the dependency between an observation and a residual error from a moving average model applied to lagged observations.

### ARIMA Parameters

Each component in ARIMA functions as a parameter with a standard notation. For ARIMA models, a standard notation would be ARIMA with p, d, and q, where integer values substitute for the parameters to indicate the type of ARIMA model used. The parameters can be defined as:

- `p` : the number of lag observations in the model; also known as the lag order.
- `d` : the number of times that the raw observations are differenced; also known as the degree of differencing.
- `q` : the size of the moving average window; also known as the order of the moving average.
