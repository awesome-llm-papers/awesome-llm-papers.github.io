---
layout: publication
title: 'Convllava: Hierarchical Backbones As Visual Encoder For Large Multimodal Models'
authors: Chunjiang Ge, Sijie Cheng, Ziming Wang, Jiale Yuan, Yuan Gao, Jun Song, Shiji
  Song, Gao Huang, Bo Zheng
conference: No Venue
year: 2024
bibkey: ge2024convllava
additional_links: [{name: Code, url: 'https://github.com/alibaba/conv-llava'}, {name: Code,
    url: 'https://huggingface.co/discussions/paper/66540322d200a2ecdf78502c'}, {name: Paper,
    url: 'https://arxiv.org/abs/hf2405.15738'}]
tags: ["Model Architecture"]
short_authors: Ge et al.
---
High-resolution Large Multimodal Models (LMMs) encounter the challenges of excessive visual tokens and quadratic visual complexity. Current high-resolution LMMs address the quadratic complexity while still generating excessive visual tokens. However, the redundancy in visual tokens is the key problem as it leads to more substantial compute. To mitigate this issue, we propose ConvLLaVA, which employs ConvNeXt, a hierarchical backbone, as the visual encoder of LMM to replace Vision Transformer (ViT). ConvLLaVA compresses high-resolution images into information-rich visual features, effectively preventing the generation of excessive visual tokens. To enhance the capabilities of ConvLLaVA, we propose two critical optimizations. Since the low-resolution pretrained ConvNeXt underperforms when directly applied on high resolution, we update it to bridge the gap. Moreover, since ConvNeXt's original compression ratio is inadequate for much higher resolution inputs, we train a successive stage to further compress the visual tokens, thereby reducing redundancy. These optimizations enable ConvLLaVA to support inputs of 1536x1536 resolution generating only 576 visual tokens, capable of handling images of arbitrary aspect ratios. Experimental results demonstrate that our method achieves competitive performance with state-of-the-art models on mainstream benchmarks. The ConvLLaVA model series are publicly available at https://github.com/alibaba/conv-llava.

https://huggingface.co/discussions/paper/66540322d200a2ecdf78502c