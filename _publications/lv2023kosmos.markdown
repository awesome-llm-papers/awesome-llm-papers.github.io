---
layout: publication
title: 'Kosmos-2.5: A Multimodal Literate Model'
authors: Tengchao Lv, Yupan Huang, Jingye Chen, Lei Cui, Shuming Ma, Yaoyao Chang,
  Shaohan Huang, Wenhui Wang, Li Dong, Weiyao Luo, Shaoxiang Wu, Guoxin Wang, Cha
  Zhang, Furu Wei
conference: No Venue
year: 2023
bibkey: lv2023kosmos
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2309.11419'}]
tags: ["Model Architecture"]
short_authors: Lv et al.
---
We present Kosmos-2.5, a multimodal literate model for machine reading of text-intensive images. Pre-trained on large-scale text-intensive images, Kosmos-2.5 excels in two distinct yet cooperative transcription tasks: (1) generating spatially-aware text blocks, where each block of text is assigned its spatial coordinates within the image, and (2) producing structured text output that captures styles and structures into the markdown format. This unified multimodal literate capability is achieved through a shared Transformer architecture, task-specific prompts, and flexible text representations. We evaluate Kosmos-2.5 on end-to-end document-level text recognition and image-to-markdown text generation. Furthermore, the model can be readily adapted for any text-intensive image understanding task with different prompts through supervised fine-tuning, making it a general-purpose tool for real-world applications involving text-rich images. This work also paves the way for the future scaling of multimodal large language models.

https://huggingface.co/discussions/paper/650bc0782ec41a31f31b1465