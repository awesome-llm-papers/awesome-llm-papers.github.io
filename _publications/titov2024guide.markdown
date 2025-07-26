---
layout: publication
title: 'Guide-and-rescale: Self-guidance Mechanism For Effective Tuning-free Real
  Image Editing'
authors: Vadim Titov, Madina Khalmatova, Alexandra Ivanova, Dmitry Vetrov, Aibek Alanov
conference: No Venue
year: 2024
bibkey: titov2024guide
additional_links: [{name: Code, url: 'https://github.com/FusionBrainLab/Guide-and-Rescale'},
  {name: Code, url: 'https://huggingface.co/discussions/paper/66d8408d6ff4d323370c5d96'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2409.01322'}]
tags: ["Evaluation", "Fine-Tuning", "Has Code"]
short_authors: Titov et al.
---
Despite recent advances in large-scale text-to-image generative models, manipulating real images with these models remains a challenging problem. The main limitations of existing editing methods are that they either fail to perform with consistent quality on a wide range of image edits or require time-consuming hyperparameter tuning or fine-tuning of the diffusion model to preserve the image-specific appearance of the input image. We propose a novel approach that is built upon a modified diffusion sampling process via the guidance mechanism. In this work, we explore the self-guidance technique to preserve the overall structure of the input image and its local regions appearance that should not be edited. In particular, we explicitly introduce layout-preserving energy functions that are aimed to save local and global structures of the source image. Additionally, we propose a noise rescaling mechanism that allows to preserve noise distribution by balancing the norms of classifier-free guidance and our proposed guiders during generation. Such a guiding approach does not require fine-tuning the diffusion model and exact inversion process. As a result, the proposed method provides a fast and high-quality editing mechanism. In our experiments, we show through human evaluation and quantitative analysis that the proposed method allows to produce desired editing which is more preferable by humans and also achieves a better trade-off between editing quality and preservation of the original image. Our code is available at https://github.com/FusionBrainLab/Guide-and-Rescale.

https://huggingface.co/discussions/paper/66d8408d6ff4d323370c5d96