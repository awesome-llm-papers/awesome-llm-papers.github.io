---
layout: publication
title: 'When Not To Trust Language Models: Investigating Effectiveness Of Parametric
  And Non-parametric Memories'
authors: Alex Mallen, Akari Asai, Victor Zhong, Rajarshi Das, Daniel Khashabi, Hannaneh
  Hajishirzi
conference: 'Proceedings of the 61st Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2023
bibkey: mallen2022when
citations: 109
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2212.10511'}]
tags: ["Datasets", "RAG"]
short_authors: Mallen et al.
---
Despite their impressive performance on diverse tasks, large language models
(LMs) still struggle with tasks requiring rich world knowledge, implying the
limitations of relying solely on their parameters to encode a wealth of world
knowledge. This paper aims to understand LMs' strengths and limitations in
memorizing factual knowledge, by conducting large-scale knowledge probing
experiments of 10 models and 4 augmentation methods on PopQA, our new
open-domain QA dataset with 14k questions. We find that LMs struggle with less
popular factual knowledge, and that scaling fails to appreciably improve
memorization of factual knowledge in the long tail. We then show that
retrieval-augmented LMs largely outperform orders of magnitude larger LMs,
while unassisted LMs remain competitive in questions about high-popularity
entities. Based on those findings, we devise a simple, yet effective, method
for powerful and efficient retrieval-augmented LMs, which retrieves
non-parametric memories only when necessary. Experimental results show that
this significantly improves models' performance while reducing the inference
costs.