# Introduction to Tidyverts with the Australian retail turnover data

This case study is meant to be a quick introduction to time series analysis in R, using the [**Tidyverts**](https://tidyverts.org) family of R packages. Tidyverts is the work of Rob Hyndman, professor of statistics at Monash University, and his team. The family is intended to be the next-generation replacement for the very popular `forecast` package, and is currently under active development.

The main reference for Tidyverts is the textbook [_Forecasting: Principles and Practice, 3rd Edition_](https://otexts.com/fpp3/), by Hyndman and Athanasopoulos. It's highly recommended to read that in conjunction with working through the notebooks here.

## Summary

The R Notebooks in this directory are as follows. Each notebook also has a corresponding HTML file, which is the rendered output from running the code. This is best viewed on our [https://microsoft.github.io/forecasting/](https://microsoft.github.io/forecasting/) GitHub Page.

- [`01_explore.Rmd`](01_explore.Rmd) [`(.html)`](01_explore.nb.html) introduces the `aus_retail` dataset and performs some exploratory analysis, generating graphs and tables.
- [`02_model.Rmd`](02_model.Rmd) [`(.html)`](02_model.nb.html) fits a range of simple time series models to the data and discusses the results.

## Package installation

The following packages are needed to run the notebooks in this directory:

- rmarkdown
- dplyr
- tidyr
- ggplot2
- tsibble
- tsibbledata
- fable
- feasts
- urca
- future
- future.apply

It's likely that you will already have many of these (particularly the [Tidyverse](https://tidyverse.org) packages) installed, if you use R for data science tasks.

```r
install.packages("tidyverse") # installs all tidyverse packages
install.packages("rmarkdown")
install.packages(c("future", "future.apply"))
install.packages(c("tsibble", "fable", "feasts", "urca"))
```
