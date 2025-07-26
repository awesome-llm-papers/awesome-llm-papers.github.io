---
layout: publication
title: 'Olmotrace: Tracing Language Model Outputs Back To Trillions Of Training Tokens'
authors: Jiacheng Liu, Taylor Blanton, Yanai Elazar, Sewon Min, Yensung Chen, Arnavi
  Chheda-kothary, Huy Tran, Byron Bischoff, Eric Marsh, Michael Schmitz, Cassidy Trier,
  Aaron Sarnat, Jenna James, Jon Borchardt, Bailey Kuehl, Evie Cheng, Karen Farley,
  Sruthi Sreeram, Taira Anderson, David Albright, Carissa Schoenick, Luca Soldaini,
  Dirk Groeneveld, Rock Yuren Pang, Pang Wei Koh, Noah A. Smith, Sophie Lebrecht,
  Yejin Choi, Hannaneh Hajishirzi, Ali Farhadi, Jesse Dodge
conference: No Venue
year: 2025
bibkey: liu2025olmotrace
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2504.07096'}]
tags: ["Training Techniques"]
short_authors: Liu et al.
---
We present OLMoTrace, the first system that traces the outputs of language models back to their full, multi-trillion-token training data in real time. OLMoTrace finds and shows verbatim matches between segments of language model output and documents in the training text corpora. Powered by an extended version of infini-gram (Liu et al., 2024), our system returns tracing results within a few seconds. OLMoTrace can help users understand the behavior of language models through the lens of their training data. We showcase how it can be used to explore fact checking, hallucination, and the creativity of language models. OLMoTrace is publicly available and fully open-source.

https://huggingface.co/discussions/paper/67f72bb3f9d51b79dca06d8c