---
title: Locality-Preserving Spatial Partitioning for Geo Big Data Analytics in
  Main Memory Frameworks
publication_types:
  - "1"
authors:
  - Isam Mashhour Al Jawarneh
  - Paolo Bellavista
  - Antonio Corradi
  - Luca Foschini
  - Rebecca Montanari
author_notes:
  - "lead & corresponding: Isam Mashhour Al Jawarneh"
publication: in *GLOBECOM 2020-2020 IEEE Global Communications Conference*
publication_short: in *IEEE GLOBECOM 2020*
abstract: The easily reachable IoT edge devices have caused the accumulation of
  vast amounts of geo-referenced data traces that can help in performing deep
  insightful analytics. Geospatial data in real geometries are normally clumped
  into batches and has strong autocorrelation properties which can be exploited
  in discovering interesting insights. Current plain Cloud computing frameworks
  are not attuned to the shape of data. Most importantly, data splitting is an
  important precursor in data parallelization mechanisms. Current systems mostly
  focus on general data workloads, thus are giving attention mostly to load
  balancing while splitting the data to Cloud computing resources. However, many
  benefits can be reaped by being attuned to the spatial characteristics while
  distributing the data, thus striking a plausible balance between load
  balancing and spatial data locality preservation normally leads to achieving
  better time-based QoS goals, which then leads to an optimized provisioning of
  Cloud computing resources. In this paper, we have designed a spatial batch
  processing engine that comprises a custom spatial data locality aware
  partitioning method for disseminating spatial data loads in Cloud computing
  clusters. We have also extended a state-of-art benchmark density-based
  clustering method that is known as DBSCAN-MR and implemented a standard
  compliant prototype on top of a best-in-breed de facto Cloud-based main memory
  processing framework, Apache Spark. Our results show that our partitioning
  method with the associated spatial query optimizers can achieve gains that
  significantly outperform baselines.
tags:
  - geospatial AQP
  - geospatial big data management
  - unibo
url_pdf: "pubs/Globecom20.pdf"
image:
  caption: ""
  focal_point: ""
  preview_only: false
summary: summary
url_dataset: ""
url_project: ""
url_source: ""
url_video: ""

date: 2020-12-07T18:18:17.277Z
---
