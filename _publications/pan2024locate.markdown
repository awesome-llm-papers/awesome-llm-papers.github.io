---
layout: publication
title: 'Locate, Assign, Refine: Taming Customized Promptable Image Inpainting'
authors: Pan et al.
conference: Arxiv
year: 2024
bibkey: pan2024locate
citations: 62
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2403.19534'}]
tags: [RAG, Training Techniques, Attention Mechanism, Prompting, Transformer, Model
    Architecture, Reinforcement Learning, Multimodal Models]
---
Prior studies have made significant progress in image inpainting guided by
either text description or subject image. However, the research on inpainting
with flexible guidance or control, i.e., text-only, image-only, and their
combination, is still in the early stage. Therefore, in this paper, we
introduce the multimodal promptable image inpainting project: a new task model,
and data for taming customized image inpainting. We propose LAR-Gen, a novel
approach for image inpainting that enables seamless inpainting of specific
region in images corresponding to the mask prompt, incorporating both the text
prompt and image prompt. Our LAR-Gen adopts a coarse-to-fine manner to ensure
the context consistency of source image, subject identity consistency, local
semantic consistency to the text description, and smoothness consistency. It
consists of three mechanisms: (i) Locate mechanism: concatenating the noise
with masked scene image to achieve precise regional editing, (ii) Assign
mechanism: employing decoupled cross-attention mechanism to accommodate
multi-modal guidance, and (iii) Refine mechanism: using a novel RefineNet to
supplement subject details. Additionally, to address the issue of scarce
training data, we introduce a novel data engine to automatically extract
substantial pairs of data consisting of local text prompts and corresponding
visual instances from a vast image data, leveraging publicly available
pre-trained large models. Extensive experiments and various application
scenarios demonstrate the superiority of LAR-Gen in terms of both identity
preservation and text semantic consistency.