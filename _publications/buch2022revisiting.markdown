---
layout: publication
title: Revisiting The "video" In Video-language Understanding
authors: "Shyamal Buch, Crist\xF3bal Eyzaguirre, Adrien Gaidon, Jiajun Wu, Li Fei-fei,\
  \ Juan Carlos Niebles"
conference: 2022 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2022
bibkey: buch2022revisiting
citations: 84
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2206.01720'}]
tags: ["CVPR"]
short_authors: Buch et al.
---
What makes a video task uniquely suited for videos, beyond what can be
understood from a single image? Building on recent progress in self-supervised
image-language models, we revisit this question in the context of video and
language tasks. We propose the atemporal probe (ATP), a new model for
video-language analysis which provides a stronger bound on the baseline
accuracy of multimodal models constrained by image-level understanding. By
applying this model to standard discriminative video and language tasks, such
as video question answering and text-to-video retrieval, we characterize the
limitations and potential of current video-language benchmarks. We find that
understanding of event temporality is often not necessary to achieve strong or
state-of-the-art performance, even compared with recent large-scale
video-language models and in contexts intended to benchmark deeper video-level
understanding. We also demonstrate how ATP can improve both video-language
dataset and model design. We describe a technique for leveraging ATP to better
disentangle dataset subsets with a higher concentration of temporally
challenging data, improving benchmarking efficacy for causal and temporal
understanding. Further, we show that effectively integrating ATP into full
video-level temporal models can improve efficiency and state-of-the-art
accuracy.