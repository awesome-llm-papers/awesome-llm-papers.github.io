---
layout: publication
title: 'Realgeneral: Unifying Visual Generation Via Temporal In-context Learning With
  Video Models'
authors: Lin et al.
conference: Lecture Notes in Computer Science
year: 2025
bibkey: lin2025realgeneral
citations: 389
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2503.10406'}]
tags: [RAG, Training Techniques, Attention Mechanism, Tools, In Context Learning,
  Model Architecture, Multimodal Models, Large Scale Training, Datasets]
---
Unifying diverse image generation tasks within a single framework remains a
fundamental challenge in visual generation. While large language models (LLMs)
achieve unification through task-agnostic data and generation, existing visual
generation models fail to meet these principles. Current approaches either rely
on per-task datasets and large-scale training or adapt pre-trained image models
with task-specific modifications, limiting their generalizability. In this
work, we explore video models as a foundation for unified image generation,
leveraging their inherent ability to model temporal correlations. We introduce
RealGeneral, a novel framework that reformulates image generation as a
conditional frame prediction task, analogous to in-context learning in LLMs. To
bridge the gap between video models and condition-image pairs, we propose (1) a
Unified Conditional Embedding module for multi-modal alignment and (2) a
Unified Stream DiT Block with decoupled adaptive LayerNorm and attention mask
to mitigate cross-modal interference. RealGeneral demonstrates effectiveness in
multiple important visual generation tasks, e.g., it achieves a 14.5%
improvement in subject similarity for customized generation and a 10%
enhancement in image quality for canny-to-image task. Project page:
https://lyne1.github.io/RealGeneral/