---
layout: publication
title: 'Describe Anything: Detailed Localized Image And Video Captioning'
authors: Long Lian, Yifan Ding, Yunhao Ge, Sifei Liu, Hanzi Mao, Boyi Li, Marco Pavone,
  Ming-yu Liu, Trevor Darrell, Adam Yala, Yin Cui
conference: No Venue
year: 2025
bibkey: lian2025describe
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2504.16072'}]
tags: ["Datasets"]
short_authors: Lian et al.
---
Generating detailed and accurate descriptions for specific regions in images and videos remains a fundamental challenge for vision-language models. We introduce the Describe Anything Model (DAM), a model designed for detailed localized captioning (DLC). DAM preserves both local details and global context through two key innovations: a focal prompt, which ensures high-resolution encoding of targeted regions, and a localized vision backbone, which integrates precise localization with its broader context. To tackle the scarcity of high-quality DLC data, we propose a Semi-supervised learning (SSL)-based Data Pipeline (DLC-SDP). DLC-SDP starts with existing segmentation datasets and expands to unlabeled web images using SSL. We introduce DLC-Bench, a benchmark designed to evaluate DLC without relying on reference captions. DAM sets new state-of-the-art on 7 benchmarks spanning keyword-level, phrase-level, and detailed multi-sentence localized image and video captioning.

https://huggingface.co/discussions/paper/6808467e867c3ef14f832831