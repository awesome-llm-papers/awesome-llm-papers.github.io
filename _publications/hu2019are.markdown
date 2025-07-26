---
layout: publication
title: Are You Looking? Grounding To Multiple Modalities In Vision-and-language Navigation
authors: Ronghang Hu, Daniel Fried, Anna Rohrbach, Dan Klein, Trevor Darrell, Kate
  Saenko
conference: Proceedings of the 57th Annual Meeting of the Association for Computational
  Linguistics
year: 2019
bibkey: hu2019are
citations: 77
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1906.00347'}]
tags: ["Datasets", "Evaluation"]
short_authors: Hu et al.
---
Vision-and-Language Navigation (VLN) requires grounding instructions, such as
"turn right and stop at the door", to routes in a visual environment. The
actual grounding can connect language to the environment through multiple
modalities, e.g. "stop at the door" might ground into visual objects, while
"turn right" might rely only on the geometric structure of a route. We
investigate where the natural language empirically grounds under two recent
state-of-the-art VLN models. Surprisingly, we discover that visual features may
actually hurt these models: models which only use route structure, ablating
visual features, outperform their visual counterparts in unseen new
environments on the benchmark Room-to-Room dataset. To better use all the
available modalities, we propose to decompose the grounding procedure into a
set of expert models with access to different modalities (including object
detections) and ensemble them at prediction time, improving the performance of
state-of-the-art models on the VLN task.