---
layout: publication
title: 'Videomamba: State Space Model For Efficient Video Understanding'
authors: Kunchang Li, Xinhao Li, Yi Wang, Yinan He, Yali Wang, Limin Wang, Yu Qiao
conference: No Venue
year: 2024
bibkey: li2024videomamba
additional_links: [{name: Code, url: 'https://github.com/OpenGVLab/VideoMamba'}, {
    name: Code, url: 'https://huggingface.co/discussions/paper/65efca60e2f3a2d6588c8395'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2403.06977'}]
tags: ["Efficiency"]
short_authors: Li et al.
---
Addressing the dual challenges of local redundancy and global dependencies in video understanding, this work innovatively adapts the Mamba to the video domain. The proposed VideoMamba overcomes the limitations of existing 3D convolution neural networks and video transformers. Its linear-complexity operator enables efficient long-term modeling, which is crucial for high-resolution long video understanding. Extensive evaluations reveal VideoMamba's four core abilities: (1) Scalability in the visual domain without extensive dataset pretraining, thanks to a novel self-distillation technique; (2) Sensitivity for recognizing short-term actions even with fine-grained motion differences; (3) Superiority in long-term video understanding, showcasing significant advancements over traditional feature-based models; and (4) Compatibility with other modalities, demonstrating robustness in multi-modal contexts. Through these distinct advantages, VideoMamba sets a new benchmark for video understanding, offering a scalable and efficient solution for comprehensive video understanding. All the code and models are available at https://github.com/OpenGVLab/VideoMamba.

https://huggingface.co/discussions/paper/65efca60e2f3a2d6588c8395