---
title: QoS-Aware Approximate Query Processing for Smart Cities Spatial Data Streams
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
publication_short: In *MDPI Sensors*
abstract: Large amounts of georeferenced data streams arrive daily to stream
  processing systems. This is attributable to the overabundance of affordable
  IoT devices. In addition, interested practitioners desire to exploit Internet
  of Things (IoT) data streams for strategic decision-making purposes. However,
  mobility data are highly skewed and their arrival rates fluctuate. This nature
  poses an extra challenge on data stream processing systems, which are required
  in order to achieve pre-specified latency and accuracy goals. In this paper,
  we propose ApproxSSPS, which is a system for approximate processing of
  geo-referenced mobility data, at scale with quality of service guarantees. We
  focus on stateful aggregations (e.g., means, counts) and top-N queries.
  ApproxSSPS features a controller that interactively learns the latency
  statistics and calculates proper sampling rates to meet latency or/and
  accuracy targets. An overarching trait of ApproxSSPS is its ability to strike
  a plausible balance between latency and accuracy targets. We evaluate
  ApproxSSPS on Apache Spark Structured Streaming with real mobility data. We
  also compared ApproxSSPS against a state-of-the-art online adaptive processing
  system. Our extensive experiments prove that ApproxSSPS can fulfill latency
  and accuracy targets with varying sets of parameter configurations and load
  intensities (i.e., transient peaks in data loads versus slow arriving
  streams). Moreover, our results show that ApproxSSPS outperforms the baseline
  counterpart by significant magnitudes. In short, ApproxSSPS is a novel spatial
  data stream processing system that can deliver real accurate results in a
  timely manner, by dynamically specifying the limits on data samples.
draft: false
featured: true
tags:
  - geospatial AQP
  - geospatial big data management
  - big data streams
  - unibo
slides: ""
url_pdf: ""
image:
  caption: ""
  focal_point: ""
  preview_only: false
summary: summary
url_dataset: ""
url_project: https://isamaljawarneh.github.io/ApproximateStream/
url_source: https://isamaljawarneh.github.io/ApproximateStream/
url_video: ""
url_dataset: 'https://isamaljawarneh.github.io/ApproximateStream/'
url_poster: ''
url_slides: ''
url_video: ''
url_slides: ''

author_notes:
  - "corresponding author: Isam Mashhour Al Jawarneh"
doi: ""
publication: In *MDPI Sensors*
projects:
  - ApproxSSPS
date: 2021-06-06T21:50:00.000Z
url_slides: ""
publishDate: 2021-06-06T21:50:00.000Z
url_poster: ""
url_code: https://isamaljawarneh.github.io/ApproximateStream/
---
{{% callout note %}}
Click the *Cite* button above to export or download the citations.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code.](https://github.com/IsamAljawarneh/ApproximateStream)
