---
title: Efficient QoS-Aware Spatial Join Processing for Scalable NoSQL Storage
  Frameworks
publication_types:
  - "2"
authors:
  - Isam Mashhour Al Jawarneh
  - Paolo Bellavista
  - Antonio Corradi
  - Luca Foschini
  - Rebecca Montanari
author_notes:
  - "lead & corresponding author: Isam Mashhour Al Jawarneh"
publication: in *IEEE Transactions on Network and Service Management*
publication_short: in *IEEE Transactions on Network and Service Management*
abstract: Current cloud-enabled NoSQL database frameworks support flexible and
  scalable storage of huge amounts of data arriving through various and often
  heterogeneous channels. However, they do not natively provide optimised
  processing of spatial data, thus making it more difficult to perform accurate
  data analytics needed in many smart city application scenarios. To improve the
  performance of spatial data computation in the NoSQL MongoDB storage
  framework, this article proposes a novel data partitioning method based on
  dimensionality reduction. The underlying key idea is to reduce a spatial data
  representation from multi to single dimensionality, by still maintaining its
  geometrical meaning and by employing a specific geo-encoding scheme, i.e., a
  geohash string. In particular, the geohash string is used as a sharding key in
  order to store geometrically-nearby objects into the same chunks (and
  consequently into the same shard). In addition, as a distinctive feature, we
  have extended the MongoDB framework with a custom spatial QoS-aware optimizer
  that exploits our novel partitioning scheme to support two, typically
  expensive, types of spatial queries with QoS guarantees. Those queries are
  containment (and consequently top-N) and proximity. The paper also contributes
  to the existing literature with extensive experimental results about the
  performance of both our partitioning method and query optimizer; the reported
  results show that our solutions outperform baselines by orders of magnitude.
draft: false
featured: true
tags:
  - geospatial big data management
  - unibo
url_pdf: "pubs/TNSM3034150.pdf"
image:
  caption: ""
  focal_point: ""
  preview_only: false
summary: summary
url_dataset: ""
url_project: ""
url_source: ""
url_video: ""
date: 2020-10-27T19:23:35.513Z
---
