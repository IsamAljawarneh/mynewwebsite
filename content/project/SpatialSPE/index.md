---
title: SpatialSPE
date: 2021-11-25T21:42:21.558Z
summary:  SpatialSPE is an approximate query processing engine for fast-arriving geospatial data streams. It aims at maintaining the QoS during high-peak data streaming loads.
draft: false
featured: false
tags:
  - geospatial big data management
  - geospatial AQP
  - big data streams
  - unibo
image:
  filename: featured.jpg
  focal_point: Smart
  preview_only: false
links:
url_code: "https://github.com/IsamAljawarneh/SpatialSPE"
url_pdf: ""
url_slides: ""
url_video: ""
---
#### Overview

- `SpatialSPE` accepts a continuous query and QoS budgets (expressed as latency and accuracy targets) and employs our spatial-aware sampling method (that we dub as SAOS, which is an integral part of `SpatialSPE`) to select an appropriate sample, 
- then it computes an approximate answer and serves it to the user incrementally, together with rigorous error bounds. 
- We have implemented `SpatialSPE` on top of Spark Structured Streaming

**publication:** [IEEE CAMAD2020]({{< relref "/publication/camad2020" >}}) & [IEEE GLOBECOM2019]({{< relref "/publication/globecom2019" >}}) 
