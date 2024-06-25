---
title: Multi-Path Long-Term Vessel Trajectories Forecasting with Probabilistic Feature
  Fusion for Problem Shifting
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
date: '2024-01-01'
publishDate: '2024-06-25T15:51:44.019825Z'
publication_types:
- article-journal
publication: '*arXiv preprint arXiv:2310.18948*'
doi: doi.org/10.48550/arXiv.2310.18948
abstract: This paper addresses the challenge of boosting the precision of multi-path
  long-term vessel trajectory forecasting on engineered sequences of Automatic Identification
  System (AIS) data using feature fusion for problem shifting. We have developed a
  deep auto-encoder model and a phased framework approach to predict the next 12 hours
  of vessel trajectories using 1 to 3 hours of AIS data as input. To this end, we
  fuse the spatiotemporal features from the AIS messages with probabilistic features
  engineered from historical AIS data referring to potential routes and destinations.
  As a result, we reduce the forecasting uncertainty by shifting the problem into
  a trajectory reconstruction problem. The probabilistic features have an F1-Score
  of approximately 85% and 75% for the vessel route and destination prediction, respectively.
  Under such circumstances, we achieved an R2 Score of over 98% with different layer
  structures and varying feature combinations; the high R2 Score is a natural outcome
  of the well-defined shipping lanes in the study region. However, our proposal stands
  out among competing approaches as it demonstrates the capability of complex decision-making
  during turnings and route selection. Furthermore, we have shown that our model achieves
  more accurate forecasting with average and median errors of 11km and 6km, respectively,
  a 25% improvement from the current state-of-the-art approaches. The resulting model
  from this proposal is deployed as part of a broader Decision Support System to safeguard
  whales by preventing the risk of vessel-whale collisions under the smartWhales initiative
  and acting on the Gulf of St. Lawrence in Atlantic Canada.
links:
- name: URL
  url: https://www.semanticscholar.org/paper/ddb6da0b0a60d8b54b7f740421170b0b287110e7
---
