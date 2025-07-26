---
layout: publication
title: 'Speakervid-5m: A Large-scale High-quality Dataset For Audio-visual Dyadic
  Interactive Human Generation'
authors: Youliang Zhang, Zhaoyang Li, Duomin Wang, Jiahe Zhang, Deyu Zhou, Zixin Yin,
  Xili Dai, Gang Yu, Xiu Li
conference: No Venue
year: 2025
bibkey: zhang2025speakervid
additional_links: [{name: Code, url: 'https://dorniwang.github.io/SpeakerVid-5M/'},
  {name: Code, url: 'https://huggingface.co/discussions/paper/6875c14a257d4f0435370574'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2507.09862'}]
tags: ["Datasets", "Has Code"]
short_authors: Zhang et al.
---
The rapid development of large-scale models has catalyzed significant breakthroughs in the digital human domain. These advanced methodologies offer high-fidelity solutions for avatar driving and rendering, leading academia to focus on the next major challenge: audio-visual dyadic interactive virtual human. To facilitate research in this emerging area, we present SpeakerVid-5M dataset, the first large-scale, high-quality dataset designed for audio-visual dyadic interactive virtual human generation. Totaling over 8,743 hours, SpeakerVid-5M contains more than 5.2 million video clips of human portraits. It covers diverse scales and interaction types, including monadic talking, listening, and dyadic conversations. Crucially, the dataset is structured along two key dimensions: interaction type and data quality. First, it is categorized into four types (dialogue branch, single branch, listening branch and multi-turn branch) based on the interaction scenario. Second, it is stratified into a large-scale pre-training subset and a curated, high-quality subset for Supervised Fine-Tuning (SFT). This dual structure accommodates a wide array of 2D virtual human tasks. In addition, we provide an autoregressive (AR)-based video chat baseline trained on this data, accompanied by a dedicated set of metrics and test data to serve as a benchmark VidChatBench for future work. Both the dataset and the corresponding data processing code will be publicly released. Project page: https://dorniwang.github.io/SpeakerVid-5M/

https://huggingface.co/discussions/paper/6875c14a257d4f0435370574