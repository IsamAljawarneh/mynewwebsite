---
title: Deploying & Running Approximate Geospatial Query Processing at Scale on Microsoft Azure HDInsights
subtitle: 

# Summary for listings and search engines
summary: This tutorial shows an example of how to run an approximate stream processing on Azure HDInsights deployed with Apache Spark and Kafka. 

# Link this post with a project
projects: []

# Date published
date: "2021-07-01T00:00:00Z"

# Date updated
lastmod: "2021-07-01T00:00:00Z"

# Is this an unpublished draft?
draft: false

# Show this page in the Featured widget?
featured: false

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image:
  caption: 
  focal_point: ""
  placement: 2
  preview_only: false

authors:
- admin

tags:
- geospatial AQP

categories:
- Demo
---

## Overview
{{< hl >}}**This tutorial shows an example of how to run an approximate geospatial stream processing application on an Azure HDInsights cluster deployed with Apache Spark and Kafka**{{< /hl >}}

- you will learn how to:
- [x] create Azure HDInsight clusters deployed with Apache Spark & Kafka.
- [x] run an example dynamic application scenario common in smart city applications.

### Prerequisites
- Microsoft Azure subscription.
- basic knowledge of Jupyter Notebooks.
- basic knowledge of Scala programming language.
- basic knolwedge of Kafka topics.

{{% callout note %}}
Microsoft Azure Spark and Kafka HDInsight clusters need to be deployed within the same virtual network.
This tutorial exploits a template for this purpose. This allows the Spark cluster to communicate directly with Kafka. 
{{% /callout %}}

### [:notebook: Click here to continue reading the full `tutorial` :notebook:](https://isamaljawarneh.github.io/ApproximateStream/)

## The challenge
- Large amounts of georeferenced data streams arrive daily to stream processing systems. 
  - This is attributable to the overabundance of affordable IoT devices. 
- Interested practitioners desire to exploit Internet of Things (IoT) data streams for strategic decision-making 
  - `However`, mobility data are `highly skewed` and their `arrival rates fluctuate`. This nature poses an extra challenge on data stream processing systems, which are required in order to achieve pre-specified latency and accuracy goals. 
- Approximate Query Processing (AQP) over massively-arriving streams of geospatial data is becoming essential.

## The solution
- In this post, I will show you how to easily deploy and run an interactive QoS-aware framework in {{< icon name="microsoft" pack="fab" >}} Microsoft Azure, for performing AQP  approximate processing of geo-referenced mobility data, at scale with quality of service guarantees. 
  - We will focus on stateful aggregations (e.g., `means`, `counts`) and `top-N` queries. 
  - The example code has the ability to strike a plausible balance between latency and accuracy targets. 
- The deployment includes Apache Spark Structured Streaming and Apcahe Kafka communicating directly within the premises of a virtual network. 
- In short, geospatial AQP is esential for dynamic application scenarios prevalent in smart cities and urban informatics. The example we show in this post can deliver real accurate results in a timely manner, by employing a qualified QoS-aware geospatial startified-like online sampling method that we have designed.
 

