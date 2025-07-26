---
layout: publication
title: 'HERO: Hierarchical Encoder For Video+language Omni-representation Pre-training'
authors: Linjie Li, Yen-chun Chen, Yu Cheng, Zhe Gan, Licheng Yu, Jingjing Liu
conference: Proceedings of the 2020 Conference on Empirical Methods in Natural Language
  Processing (EMNLP)
year: 2020
bibkey: li2020hero
citations: 342
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2005.00200'}]
tags: ["EMNLP", "Model Architecture", "Training Techniques"]
short_authors: Li et al.
---
We present HERO, a novel framework for large-scale video+language
omni-representation learning. HERO encodes multimodal inputs in a hierarchical
structure, where local context of a video frame is captured by a Cross-modal
Transformer via multimodal fusion, and global video context is captured by a
Temporal Transformer. In addition to standard Masked Language Modeling (MLM)
and Masked Frame Modeling (MFM) objectives, we design two new pre-training
tasks: (i) Video-Subtitle Matching (VSM), where the model predicts both global
and local temporal alignment; and (ii) Frame Order Modeling (FOM), where the
model predicts the right order of shuffled video frames. HERO is jointly
trained on HowTo100M and large-scale TV datasets to gain deep understanding of
complex social dynamics with multi-character interactions. Comprehensive
experiments demonstrate that HERO achieves new state of the art on multiple
benchmarks over Text-based Video/Video-moment Retrieval, Video Question
Answering (QA), Video-and-language Inference and Video Captioning tasks across
different domains. We also introduce two new challenging benchmarks How2QA and
How2R for Video QA and Retrieval, collected from diverse video content over
multimodalities.