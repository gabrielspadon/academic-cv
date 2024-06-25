---
title: Unfolding AIS Transmission Behavior for Vessel Movement Modeling on Noisy Data
  Leveraging Machine Learning
authors:
- Gabriel Spadon
- Martha D. Ferreira
- Amilcar Soares
- Stan Matwin
date: '2023-01-01'
publishDate: '2024-06-25T19:31:11.907501Z'
publication_types:
- article-journal
publication: '*IEEE Access*'
doi: 10.1109/ACCESS.2022.3197215
abstract: The oceans are a source of an impressive mixture of complex data that could
  be used to uncover relationships yet to be discovered. Such data comes from the
  oceans and their surface, such as Automatic Identification System (AIS) messages
  used for tracking vessels’ trajectories. AIS messages are transmitted over radio
  or satellite at ideally periodic time intervals but vary irregularly over time.
  As such, this paper aims to model the AIS message transmission behavior through
  neural networks for forecasting upcoming AIS messages’ content from multiple vessels,
  particularly in a simultaneous approach despite messages’ temporal irregularities
  as outliers. We present a set of experiments comprising multiple algorithms for
  forecasting tasks with horizon sizes of varying lengths. Deep learning models (e.g.,
  neural networks) revealed themselves to adequately preserve vessels’ spatial awareness
  regardless of temporal irregularity. We show how convolutional layers, feed-forward
  networks, and recurrent neural networks can improve such tasks by working together.
  Experimenting with short, medium, and large-sized sequences of messages, our model
  achieved  $6/37/38%  of the Relative Percentage Difference– the lower, the better,
  whereas we observed  92/45/96%  on the Elman’s RNN, 51/52/40%  on the GRU, and  129/98/61%  on
  the LSTM. These results support our model as a driver for improving the prediction
  of vessel routes when analyzing multiple vessels of diverging types simultaneously
  under temporally noise data.
tags:
- AIS Transmission Forecasting
- Vessel Movement Modeling
- Deep Learning
- Temporal Irregularity
- Neural Networks
reading_time: false
---
