---
layout: publication
title: Multimodal Few-shot Learning With Frozen Language Models
authors: Maria Tsimpoukelli, Jacob Menick, Serkan Cabi, S. M. Ali Eslami, Oriol Vinyals,
  Felix Hill
conference: Arxiv
year: 2021
bibkey: tsimpoukelli2021multimodal
citations: 248
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2106.13884'}]
tags: ["Few-Shot"]
short_authors: Tsimpoukelli et al.
---
When trained at sufficient scale, auto-regressive language models exhibit the
notable ability to learn a new language task after being prompted with just a
few examples. Here, we present a simple, yet effective, approach for
transferring this few-shot learning ability to a multimodal setting (vision and
language). Using aligned image and caption data, we train a vision encoder to
represent each image as a sequence of continuous embeddings, such that a
pre-trained, frozen language model prompted with this prefix generates the
appropriate caption. The resulting system is a multimodal few-shot learner,
with the surprising ability to learn a variety of new tasks when conditioned on
examples, represented as a sequence of multiple interleaved image and text
embeddings. We demonstrate that it can rapidly learn words for new objects and
novel visual categories, do visual question-answering with only a handful of
examples, and make use of outside knowledge, by measuring a single model on a
variety of established and new benchmarks.