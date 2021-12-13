---
title: ApproxSSPS
date: 2021-11-25T21:42:21.558Z
summary: ApproxSSPS is a system that aims at maintaining the stability of distributed geospatial data processing systems during peak data arrival rates, with quality-of-service guarantees.
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
url_code: "https://github.com/IsamAljawarneh/ApproximateStream"
url_pdf: ""
url_slides: ""
url_video: ""
---
#### Overview

- `ApproxSSPS` ia a system for approximate processing of geo-referenced mobility data, at scale with quality of service guarantees. 
- It specifically focuses on stateful aggregations (e.g., means, counts) and top-N queries. 
- Also, it features a controller that interactively learns the latency statistics and calculates proper sampling rates to meet latency or/and accuracy targets. 
- An overarching trait of `ApproxSSPS` is its ability to strike a plausible balance between latency and accuracy targets. 
- We evaluate `ApproxSSPS` on Apache Spark Structured Streaming with real mobility data. 
- We also compared `ApproxSSPS` against a state-of-the-art online adaptive processing system. 
  - Our extensive experiments prove that `ApproxSSPS` can fulfill latency and accuracy targets with varying sets of parameter configurations and load intensities (i.e., transient peaks in data loads versus slow ar-riving streams). 
  - Moreover, our results show that ApproxSSPS outperforms the baseline counterpart by significant magnitudes. 
- In short, `ApproxSSPS` is a novel spatial data stream processing system that can deliver real accurate results in a timely manner, by dynamically specifying the limits on data samples.

**publication:** [MDPI Sensors 2021]({{< relref "/publication/sensors2021" >}})  (journal impact factor (indexed in *ISI Thomson Reuters*): 3.576)
