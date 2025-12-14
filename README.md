## Time Series Modelling — R Markdown Notebooks

This repository contains a set of R Markdown notebooks that walk through key steps in time series analysis,
from exploration and stationarity diagnostics to forecasting and econometric modelling.

### Contents

* **`app1timeseries.Rmd` — Exploratory analysis & decomposition (AirPassengers)**

  * Introduces exploratory time series analysis using the classic **AirPassengers** dataset.
  * Highlights **trend** and **seasonality** through decomposition.
  * Demonstrates **logarithmic transformations** to stabilise variance and improve interpretability.

* **`app2timeseries.Rmd`** and **`app2timeseries_.Rmd` — Stationarity & unit root testing**

  * Applies unit root and stationarity tests to real macroeconomic series:

    * **French unemployment rate**
    * **US inflation rate**
  * Uses **ADF (Augmented Dickey–Fuller)** and **KPSS** tests to assess **stationarity**, a crucial prerequisite before fitting many time series models.

* **`app3timeseries.Rmd` — ARIMA forecasting (CAC 40)**

  * Builds and evaluates **ARIMA** models on **CAC 40** data.
  * Focuses on model selection and **forecasting**.

* **`app4timeseries.Rmd` — Dynamic regression (Koyck, Cochrane-Orcutt, ARDL)**

  * Explores **dynamic regression** approaches to model relationships over time.
  * Uses **Koyck** and **ARDL** specifications to study the link between **unemployment** and **inflation** in the **United States**.

### Learning goals

By reading through the notebooks, you will see how to:

* Diagnose trend/seasonality and transform series when needed
* Test stationarity with ADF and KPSS
* Fit and use ARIMA models for forecasting
* Model economic relationships with dynamic regression (distributed lags, ARDL)

### How to run

Open each `.Rmd` file in RStudio and knit it, or run code chunks interactively.
