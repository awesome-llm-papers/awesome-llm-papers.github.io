---
layout: publication
title: Object Hallucination In Image Captioning
authors: Anna Rohrbach, Lisa Anne Hendricks, Kaylee Burns, Trevor Darrell, Kate Saenko
conference: Proceedings of the 2018 Conference on Empirical Methods in Natural Language
  Processing
year: 2018
bibkey: rohrbach2018object
citations: 254
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1809.02156'}]
tags: ["EMNLP"]
short_authors: Rohrbach et al.
---
Despite continuously improving performance, contemporary image captioning
models are prone to "hallucinating" objects that are not actually in a scene.
One problem is that standard metrics only measure similarity to ground truth
captions and may not fully capture image relevance. In this work, we propose a
new image relevance metric to evaluate current models with veridical visual
labels and assess their rate of object hallucination. We analyze how captioning
model architectures and learning objectives contribute to object hallucination,
explore when hallucination is likely due to image misclassification or language
priors, and assess how well current sentence metrics capture object
hallucination. We investigate these questions on the standard image captioning
benchmark, MSCOCO, using a diverse set of models. Our analysis yields several
interesting findings, including that models which score best on standard
sentence metrics do not always have lower hallucination and that models which
hallucinate more tend to make errors driven by language priors.