---
layout: publication
title: Long Context Transfer From Language To Vision
authors: Peiyuan Zhang, Kaichen Zhang, Bo Li, Guangtao Zeng, Jingkang Yang, Yuanhan
  Zhang, Ziyue Wang, Haoran Tan, Chunyuan Li, Ziwei Liu
conference: No Venue
year: 2024
bibkey: zhang2024long
additional_links: [{name: Code, url: 'https://github.com/EvolvingLMMs-Lab/LongVA'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2406.16852'}]
tags: ["Memory & Context"]
short_authors: Zhang et al.
---
Video sequences offer valuable temporal information, but existing large multimodal models (LMMs) fall short in understanding extremely long videos. Many works address this by reducing the number of visual tokens using visual resamplers. Alternatively, in this paper, we approach this problem from the perspective of the language model. By simply extrapolating the context length of the language backbone, we enable LMMs to comprehend orders of magnitude more visual tokens without any video training. We call this phenomenon long context transfer and carefully ablate its properties. To effectively measure LMMs' ability to generalize to long contexts in the vision modality, we develop V-NIAH (Visual Needle-In-A-Haystack), a purely synthetic long vision benchmark inspired by the language model's NIAH test. Our proposed Long Video Assistant (LongVA) can process 2000 frames or over 200K visual tokens without additional complexities. With its extended context length, LongVA achieves state-of-the-art performance on Video-MME among 7B-scale models by densely sampling more input frames. Our work is open-sourced at https://github.com/EvolvingLMMs-Lab/LongVA.

https://huggingface.co/discussions/paper/667a3a36b032d9a6594c8fe9