---
layout: publication
title: 'VINCIE: Unlocking In-context Image Editing From Video'
authors: Qu et al.
conference: ACM Transactions on Graphics
year: 2025
bibkey: qu2025vincie
citations: 141
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2506.10941'}]
tags: [Training Techniques, Evaluation, Transformer, Model Architecture, Reinforcement
    Learning, Applications, Multimodal Models, Datasets, Merging]
---
In-context image editing aims to modify images based on a contextual sequence comprising text and previously generated images. Existing methods typically depend on task-specific pipelines and expert models (e.g., segmentation and inpainting) to curate training data. In this work, we explore whether an in-context image editing model can be learned directly from videos. We introduce a scalable approach to annotate videos as interleaved multimodal sequences. To effectively learn from this data, we design a block-causal diffusion transformer trained on three proxy tasks: next-image prediction, current segmentation prediction, and next-segmentation prediction. Additionally, we propose a novel multi-turn image editing benchmark to advance research in this area. Extensive experiments demonstrate that our model exhibits strong in-context image editing capabilities and achieves state-of-the-art results on two multi-turn image editing benchmarks. Despite being trained exclusively on videos, our model also shows promising abilities in multi-concept composition, story generation, and chain-of-editing applications.