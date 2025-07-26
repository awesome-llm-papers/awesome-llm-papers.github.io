---
layout: publication
title: 'Clipper: A Low-latency Online Prediction Serving System'
authors: Daniel Crankshaw, Xin Wang, Giulio Zhou, Michael J. Franklin, Joseph E. Gonzalez,
  Ion Stoica
conference: Arxiv
year: 2017
bibkey: crankshaw2017clipper
citations: 304
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1612.03079'}]
tags: ["Applications"]
short_authors: Crankshaw et al.
---
Machine learning is being deployed in a growing number of applications which
demand real-time, accurate, and robust predictions under heavy query load.
However, most machine learning frameworks and systems only address model
training and not deployment.
  In this paper, we introduce Clipper, a general-purpose low-latency prediction
serving system. Interposing between end-user applications and a wide range of
machine learning frameworks, Clipper introduces a modular architecture to
simplify model deployment across frameworks and applications. Furthermore, by
introducing caching, batching, and adaptive model selection techniques, Clipper
reduces prediction latency and improves prediction throughput, accuracy, and
robustness without modifying the underlying machine learning frameworks. We
evaluate Clipper on four common machine learning benchmark datasets and
demonstrate its ability to meet the latency, accuracy, and throughput demands
of online serving applications. Finally, we compare Clipper to the TensorFlow
Serving system and demonstrate that we are able to achieve comparable
throughput and latency while enabling model composition and online learning to
improve accuracy and render more robust predictions.