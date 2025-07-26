---
layout: publication
title: 'Soundwave: Less Is More For Speech-text Alignment In Llms'
authors: Yuhao Zhang, Zhiheng Liu, Fan Bu, Ruiyu Zhang, Benyou Wang, Haizhou Li
conference: No Venue
year: 2025
bibkey: zhang2025soundwave
additional_links: [{name: Code, url: 'https://github.com/FreedomIntelligence/Soundwave'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2502.12900'}]
tags: ["Model Architecture", "Training Techniques"]
short_authors: Zhang et al.
---
Existing end-to-end speech large language models (LLMs) usually rely on large-scale annotated data for training, while data-efficient training has not been discussed in depth. We focus on two fundamental problems between speech and text: the representation space gap and sequence length inconsistency. We propose Soundwave, which utilizes an efficient training strategy and a novel architecture to address these issues. Results show that Soundwave outperforms the advanced Qwen2-Audio in speech translation and AIR-Bench speech tasks, using only one-fiftieth of the training data. Further analysis shows that Soundwave still retains its intelligence during conversation. The project is available at https://github.com/FreedomIntelligence/Soundwave.

https://huggingface.co/discussions/paper/67b54852b986e35c41e06426