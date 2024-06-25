---
title: 'Pay Attention to Evolution: Time Series Forecasting With Deep Graph-Evolution
  Learning'
authors:
- Gabriel Spadon
- Shenda Hong
- Bruno Brandoli
- Stan Matwin
- Jose F. Rodrigues-Jr
- Jimeng Sun
date: '2022-09-01'
publishDate: '2024-06-25T18:02:11.164707Z'
publication_types:
- article-journal
publication: '*IEEE Transactions on Pattern Analysis and Machine Intelligence*'
doi: 10.1109/TPAMI.2021.3076155
abstract: "Time-series forecasting is one of the most active research topics in artificial
  intelligence. It has the power to bring light to problems in several areas of knowledge,
  such as epidemiological studies, healthcare inference, and climate change analysis.
  Applications in real-world time series should consider two factors for achieving
  reliable predictions: modeling dynamic dependencies among multiple variables and
  adjusting the model's intrinsic hyperparameters. An open gap in the literature is
  that statistical and ensemble learning approaches systematically present lower predictive
  performance than deep learning methods. The existing applications consistently disregard
  the data sequence aspect entangled with multivariate data represented in more than
  one time series. Conversely, this work presents a novel neural network architecture
  for time-series forecasting that combines the power of graph evolution with deep
  recurrent learning on distinct data distributions, named after Recurrent Graph Evolution
  Neural Network (ReGENN). The idea is to infer multiple multivariate relationships
  between co-occurring time-series by assuming that the temporal data depends not
  only on inner variables and intra-temporal relationships (i.e., observations from
  itself) but also on outer variables and inter-temporal relationships (i.e., observations
  from other-selves). An extensive set of experiments was conducted comparing ReGENN
  with tens of ensemble methods and classical statistical ones. The results outperformed
  both statistical and ensemble-learning approaches, showing an improvement of 64.87
  percent over the competing algorithms on the SARS-CoV-2 dataset of the renowned
  John Hopkins University for 188 countries simultaneously. For further validation,
  we tested our architecture in two other public datasets of different domains, the
  PhysioNet Computing in Cardiology Challenge 2012 and Brazilian Weather datasets.
  We also analyzed the Evolution Weights arising from the hidden layers of ReGENN
  to describe how the variables of the dataset interact with each other; and, as a
  result of looking at inter and intra-temporal relationships simultaneously, we concluded
  that time-series forecasting is majorly improved if paying attention to how multiple
  multivariate data synchronously evolve."
tags:
- Time Series Forecasting
- Deep Learning
- Graph Evolution
- Recurrent Neural Networks
- Multivariate Data
---
