---
layout: publication
title: 'Unpacking SDXL Turbo: Interpreting Text-to-image Models With Sparse Autoencoders'
authors: Viacheslav Surkov, Chris Wendler, Mikhail Terekhov, Justin Deschenaux, Robert
  West, Caglar Gulcehre
conference: No Venue
year: 2024
bibkey: surkov2024unpacking
additional_links: [{name: Code, url: 'https://github.com/surkovv/sdxl-unbox'}, {name: Code,
    url: 'https://huggingface.co/discussions/paper/672367e405cb6b4c147215b4'}, {name: Paper,
    url: 'https://arxiv.org/abs/hf2410.22366'}]
tags: ["Has Code", "Model Architecture"]
short_authors: Surkov et al.
---
Sparse autoencoders (SAEs) have become a core ingredient in the reverse engineering of large-language models (LLMs). For LLMs, they have been shown to decompose intermediate representations that often are not interpretable directly into sparse sums of interpretable features, facilitating better control and subsequent analysis. However, similar analyses and approaches have been lacking for text-to-image models. We investigated the possibility of using SAEs to learn interpretable features for a few-step text-to-image diffusion models, such as SDXL Turbo. To this end, we train SAEs on the updates performed by transformer blocks within SDXL Turbo's denoising U-net. We find that their learned features are interpretable, causally influence the generation process, and reveal specialization among the blocks. In particular, we find one block that deals mainly with image composition, one that is mainly responsible for adding local details, and one for color, illumination, and style. Therefore, our work is an important first step towards better understanding the internals of generative text-to-image models like SDXL Turbo and showcases the potential of features learned by SAEs for the visual domain. Code is available at https://github.com/surkovv/sdxl-unbox

https://huggingface.co/discussions/paper/672367e405cb6b4c147215b4