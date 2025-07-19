---
layout: publication
title: 'LVC: A Lightweight Compression Framework For Enhancing Vlms In Long Video
  Understanding'
authors: Wang et al.
conference: 2020 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2025
bibkey: wang2025lvc
citations: 160
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2504.06835'}]
tags: [Training Techniques, Attention Mechanism, Tools, CVPR, Evaluation, Model Architecture,
  Multimodal Models, Datasets]
---
Long video understanding is a complex task that requires both spatial detail
and temporal awareness. While Vision-Language Models (VLMs) obtain frame-level
understanding capabilities through multi-frame input, they suffer from
information loss due to the sparse sampling strategy. In contrast, Video Large
Language Models (Video-LLMs) capture temporal relationships within visual
features but are limited by the scarcity of high-quality video-text datasets.
To transfer long video understanding capabilities to VLMs with minimal data and
computational cost, we propose Lightweight Video Compression (LVC), a novel
method featuring the Query-Attention Video Compression mechanism, which
effectively tackles the sparse sampling problem in VLMs. By training only the
alignment layer with 10k short video-text pairs, LVC significantly enhances the
temporal reasoning abilities of VLMs. Extensive experiments show that LVC
provides consistent performance improvements across various models, including
the InternVL2 series and Phi-3.5-Vision. Notably, the InternVL2-40B-LVC
achieves scores of 68.2 and 65.9 on the long video understanding benchmarks
MLVU and Video-MME, respectively, with relative improvements of 14.6% and 7.7%.
The enhanced models and code will be publicly available soon.