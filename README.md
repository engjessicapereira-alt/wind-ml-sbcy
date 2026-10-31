# Wind Speed Modeling and Multi-Horizon Forecasting at SBCY

This repository contains the code used in the study:

**Modeling and Multi-Horizon Forecasting of Wind Speed Using Machine Learning in Cuiabá–Várzea Grande, Mato Grosso, Brazil**

The study evaluates machine learning models for contemporaneous modeling and short-term wind speed forecasting at Marechal Rondon International Airport (SBCY), using hourly data from 1991 to 2020.

The experiments include:
- contemporaneous wind speed modeling;
- forecasts for 1, 3, and 6 hours ahead;
- Linear Regression, Random Forest, and HistGradientBoosting;
- temporal predictors and recent wind-speed history;
- observed meteorological variables;
- ERA5 and ERA5-Land reanalysis data;
- predictor importance analysis;
- ablation experiments;
- model parsimony analysis;
- temporal validation and final testing.

The code and documentation required to reproduce the main analyses will be organized in this repository.
### Experimento adicional com direção observada do vento

A direção local do vento, proveniente da série observacional consolidada, também foi avaliada como preditor no horizonte de t+1 h. A variável foi representada por componentes seno e cosseno, com identificação específica das condições de calmaria.

Foram avaliadas duas configurações adicionais: a inclusão da direção local no modelo parcimonioso e a substituição das componentes direcionais do ERA5-Land pela direção local. Em ambos os casos, as alterações em MAE, RMSE e R² foram marginais e não indicaram ganho consistente de desempenho. Assim, a configuração parcimoniosa original foi mantida.
