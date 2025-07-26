---
layout: publication
title: 'Infiniteyou: Flexible Photo Recrafting While Preserving Your Identity'
authors: Liming Jiang, Qing Yan, Yumin Jia, Zichuan Liu, Hao Kang, Xin Lu
conference: No Venue
year: 2025
bibkey: jiang2025infiniteyou
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2503.16418'}]
tags: ["Fine-Tuning", "Training Techniques"]
short_authors: Jiang et al.
---
Achieving flexible and high-fidelity identity-preserved image generation remains formidable, particularly with advanced Diffusion Transformers (DiTs) like FLUX. We introduce InfiniteYou (InfU), one of the earliest robust frameworks leveraging DiTs for this task. InfU addresses significant issues of existing methods, such as insufficient identity similarity, poor text-image alignment, and low generation quality and aesthetics. Central to InfU is InfuseNet, a component that injects identity features into the DiT base model via residual connections, enhancing identity similarity while maintaining generation capabilities. A multi-stage training strategy, including pretraining and supervised fine-tuning (SFT) with synthetic single-person-multiple-sample (SPMS) data, further improves text-image alignment, ameliorates image quality, and alleviates face copy-pasting. Extensive experiments demonstrate that InfU achieves state-of-the-art performance, surpassing existing baselines. In addition, the plug-and-play design of InfU ensures compatibility with various existing methods, offering a valuable contribution to the broader community.

https://huggingface.co/discussions/paper/67dcd1001f94b594ef4f3f44