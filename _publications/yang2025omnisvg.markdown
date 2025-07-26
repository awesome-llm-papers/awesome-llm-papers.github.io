---
layout: publication
title: 'Omnisvg: A Unified Scalable Vector Graphics Generation Model'
authors: Yiying Yang, Wei Cheng, Sijin Chen, Xianfang Zeng, Jiaxu Zhang, Liao Wang,
  Gang Yu, Xingjun Ma, Yu-gang Jiang
conference: No Venue
year: 2025
bibkey: yang2025omnisvg
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2504.06263'}]
tags: ["Tools"]
short_authors: Yang et al.
---
Scalable Vector Graphics (SVG) is an important image format widely adopted in graphic design because of their resolution independence and editability. The study of generating high-quality SVG has continuously drawn attention from both designers and researchers in the AIGC community. However, existing methods either produces unstructured outputs with huge computational cost or is limited to generating monochrome icons of over-simplified structures. To produce high-quality and complex SVG, we propose OmniSVG, a unified framework that leverages pre-trained Vision-Language Models (VLMs) for end-to-end multimodal SVG generation. By parameterizing SVG commands and coordinates into discrete tokens, OmniSVG decouples structural logic from low-level geometry for efficient training while maintaining the expressiveness of complex SVG structure. To further advance the development of SVG synthesis, we introduce MMSVG-2M, a multimodal dataset with two million richly annotated SVG assets, along with a standardized evaluation protocol for conditional SVG generation tasks. Extensive experiments show that OmniSVG outperforms existing methods and demonstrates its potential for integration into professional SVG design workflows.

https://huggingface.co/discussions/paper/67f5e3751b29460f6a087aa7