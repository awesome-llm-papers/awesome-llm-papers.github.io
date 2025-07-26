---
layout: publication
title: 'I2vgen-xl: High-quality Image-to-video Synthesis Via Cascaded Diffusion Models'
authors: Shiwei Zhang, Jiayu Wang, Yingya Zhang, Kang Zhao, Hangjie Yuan, Zhiwu Qin,
  Xiang Wang, Deli Zhao, Jingren Zhou
conference: No Venue
year: 2023
bibkey: zhang2023i2vgen
additional_links: [{name: Code, url: 'https://i2vgen-xl.github.io'}, {name: Code,
    url: 'https://huggingface.co/discussions/paper/654af0ffe4432d6c7b0dff7a'}, {name: Paper,
    url: 'https://arxiv.org/abs/hf2311.04145'}]
tags: ["Has Code"]
short_authors: Zhang et al.
---
Video synthesis has recently made remarkable strides benefiting from the rapid development of diffusion models. However, it still encounters challenges in terms of semantic accuracy, clarity and spatio-temporal continuity. They primarily arise from the scarcity of well-aligned text-video data and the complex inherent structure of videos, making it difficult for the model to simultaneously ensure semantic and qualitative excellence. In this report, we propose a cascaded I2VGen-XL approach that enhances model performance by decoupling these two factors and ensures the alignment of the input data by utilizing static images as a form of crucial guidance. I2VGen-XL consists of two stages: i) the base stage guarantees coherent semantics and preserves content from input images by using two hierarchical encoders, and ii) the refinement stage enhances the video's details by incorporating an additional brief text and improves the resolution to 1280times720. To improve the diversity, we collect around 35 million single-shot text-video pairs and 6 billion text-image pairs to optimize the model. By this means, I2VGen-XL can simultaneously enhance the semantic accuracy, continuity of details and clarity of generated videos. Through extensive experiments, we have investigated the underlying principles of I2VGen-XL and compared it with current top methods, which can demonstrate its effectiveness on diverse data. The source code and models will be publicly available at https://i2vgen-xl.github.io.

https://huggingface.co/discussions/paper/654af0ffe4432d6c7b0dff7a