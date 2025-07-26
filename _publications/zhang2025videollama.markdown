---
layout: publication
title: 'Videollama 3: Frontier Multimodal Foundation Models For Image And Video Understanding'
authors: Boqiang Zhang, Kehan Li, Zesen Cheng, Zhiqiang Hu, Yuqian Yuan, Guanzheng
  Chen, Sicong Leng, Yuming Jiang, Hang Zhang, Xin Li, Peng Jin, Wenqi Zhang, Fan
  Wang, Lidong Bing, Deli Zhao
conference: No Venue
year: 2025
bibkey: zhang2025videollama
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/6791ccef89c55efdc9fd46a9'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2501.13106'}]
tags: ["Datasets", "Fine-Tuning", "Tools", "Training Techniques"]
short_authors: Zhang et al.
---
In this paper, we propose VideoLLaMA3, a more advanced multimodal foundation model for image and video understanding. The core design philosophy of VideoLLaMA3 is vision-centric. The meaning of "vision-centric" is two-fold: the vision-centric training paradigm and vision-centric framework design. The key insight of our vision-centric training paradigm is that high-quality image-text data is crucial for both image and video understanding. Instead of preparing massive video-text datasets, we focus on constructing large-scale and high-quality image-text datasets. VideoLLaMA3 has four training stages: 1) vision-centric alignment stage, which warms up the vision encoder and projector; 2) vision-language pretraining stage, which jointly tunes the vision encoder, projector, and LLM with large-scale image-text data covering multiple types (including scene images, documents, charts) as well as text-only data. 3) multi-task fine-tuning stage, which incorporates image-text SFT data for downstream tasks and video-text data to establish a foundation for video understanding. 4) video-centric fine-tuning, which further improves the model's capability in video understanding. As for the framework design, to better capture fine-grained details in images, the pretrained vision encoder is adapted to encode images of varying sizes into vision tokens with corresponding numbers, rather than a fixed number of tokens. For video inputs, we reduce the number of vision tokens according to their similarity so that the representation of videos will be more precise and compact. Benefit from vision-centric designs, VideoLLaMA3 achieves compelling performances in both image and video understanding benchmarks.

https://huggingface.co/discussions/paper/6791ccef89c55efdc9fd46a9