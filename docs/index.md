---
layout: default
title: HKUST-DNN-DA
---

## About
HKUST-DNN-DA forecasts the trends of COVID-19 at the state level using deep neural networks.
Based on observations of deaths and cases since the outbreak \[<a href="#data-source">1</a>\], our models are trained to forecast state-level weekly incident cases in Germany.
Model training is particularly enhanced by data augmentation on these observed data.


## Latest state-level forecast
(updated on {{site.updated_on}})  
<img src="fig/de{{site.model_date|date:'%y%m%d'}}/projection_GM07_{{site.model_date|date:'%y%m%d'}}.png" width="400">
<img src="fig/de{{site.model_date|date:'%y%m%d'}}/projection_GM02_{{site.model_date|date:'%y%m%d'}}.png" width="400">

[more results](results.md)

## Contact
<a href="mailto:fcy@cse.ust.hk">Chung-Yan FONG</a> and <a href="http://home.cse.ust.hk/~dyyeung" target="_blank">Professor Dit-Yan YEUNG</a>  
Department of Computer Science and Engineering  
The Hong Kong University of Science and Technology

## Data source
\[1\] <a href="https://github.com/cfong32/covid19-forecast-hub-de/tree/master/data-truth/RKI" target="_blank">https://github.com/cfong32/covid19-forecast-hub-de/tree/master/data-truth/RKI</a>  
