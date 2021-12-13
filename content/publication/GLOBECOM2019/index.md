---
title: Spatial-aware approximate big data stream processing
publication_types:
  - "1"
authors:
  - Isam Mashhour Al Jawarneh
  - Paolo Bellavista
  - Luca Foschini
  - Rebecca Montanari
author_notes:
  - "lead & corresponding author: Isam Mashhour Al Jawarneh"
publication: in *2019 IEEE global communications conference (GLOBECOM)*
publication_short: in *IEEE GLOBECOM 2019*
abstract: The widespread adoption of ubiquitous IoT edge devices and modern
  telemetry spewing out unprecedented avalanches of spatially-tagged datasets
  that if could interactively be explored would offer deep insights into
  interesting natural phenomena, which might remain otherwise illusive. Online
  application of spatial queries is expensive, a problem that is further
  inflated by the fact that we, more than often, do not have access to a full
  dataset population in non- stationary settings. As a way of coping up,
  sampling stands out as a natural solution for approximating estimators such as
  averages and totals of some interesting correlated parameters. In any sampling
  design, representativeness remains the main issue upon which a method is
  regarded good or bad. In a loose way, in a spatial context, this means fairly
  sampling quantities in a way that preserves spatial characteristics so as to
  provide more accurate approximates for spatial query responses. Current big
  data management systems either do not offer over-the-counter spatial-aware
  online sampling solutions or, at best, rely on randomness, which causes too
  many imponderables for an overall estimation. We herein have designed a QoS-
  spatial-aware online sampling method that outperforms vanilla baselines by
  statically significant magnitudes. Our method sits atop Apache Spark
  Structured Streaming's codebase and have been tested against a benchmark that
  is consisting of millions-records of spatially- augmented dataset.
draft: false
featured: true
tags:
  - geospatial AQP
  - geospatial big data management
  - big data streams
  - unibo
url_pdf: "pubs/Globecom19.pdf"
image:
  caption: ""
  focal_point: ""
  preview_only: false
summary: summary
url_dataset: ""
url_project: ""
url_source: ""
url_video: ""
date: 2019-12-09T22:29:31.598Z
url_code: "https://github.com/IsamAljawarneh/SpatialSPE"
---
