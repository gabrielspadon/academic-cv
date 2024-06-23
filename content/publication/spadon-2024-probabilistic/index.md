---
title: Probabilistic Feature Augmentation for AIS-Based Multi-Path Long-Term Vessel
  Trajectory Forecasting
authors:
- Gabriel Spadon
- Jay Kumar
- Derek Eden
- Josh van Berkel
- Tom Foster
- Amilcar Soares
- Ronan Fablet
- Stan Matwin
- Ronald Pelot
date: '2023-01-01'
publishDate: '2024-06-23T19:22:55.438890Z'
publication_types:
- article-journal
publication: '*arXiv preprint arXiv:2310.18948*'
abstract: Maritime transportation is paramount in achieving global economic growth,
  entailing concurrent ecological obligations in sustainability and safeguarding endangered
  marine species, most notably preserving large whale populations. In this regard,
  the Automatic Identification System (AIS) data plays a significant role by offering
  real-time streaming data on vessel movement, allowing enhanced traffic monitoring.
  This study explores using AIS data to prevent vessel-to-whale collisions by forecasting
  long-term vessel trajectories from engineered AIS data sequences. For such a task,
  we have developed an encoder-decoder model architecture using Bidirectional Long
  Short-Term Memory Networks (Bi-LSTM) to predict the next 12 hours of vessel trajectories
  using 1 to 3 hours of AIS data as input. We feed the model with probabilistic features
  engineered from historical AIS data that refer to each trajectory's potential route
  and destination. The model then predicts the vessel's trajectory, considering these
  additional features by leveraging convolutional layers for spatial feature learning
  and a position-aware attention mechanism that increases the importance of recent
  timesteps of a sequence during temporal feature learning. The probabilistic features
  have an F1 Score of approximately 85% and 75% for each feature type, respectively,
  demonstrating their effectiveness in augmenting information to the neural network.
  We test our model on the Gulf of St. Lawrence, a region known to be the habitat
  of North Atlantic Right Whales (NARW). Our model achieved a high R2 score of over
  98% using various techniques and features. It stands out among other approaches
  as it can make complex decisions during turnings and path selection. Our study highlights
  the potential of data engineering and trajectory forecasting models for marine life
  species preservation.
links:
- name: URL
  url: https://www.semanticscholar.org/paper/ddb6da0b0a60d8b54b7f740421170b0b287110e7
---
