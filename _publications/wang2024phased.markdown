---
layout: publication
title: Phased Consistency Model
authors: Fu-yun Wang, Zhaoyang Huang, Alexander William Bergman, Dazhong Shen, Peng
  Gao, Michael Lingelbach, Keqiang Sun, Weikang Bian, Guanglu Song, Yu Liu, Hongsheng
  Li, Xiaogang Wang
conference: No Venue
year: 2024
bibkey: wang2024phased
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2405.18407'}]
tags: ["Has Code"]
short_authors: Wang et al.
---
The consistency model (CM) has recently made significant progress in accelerating the generation of diffusion models. However, its application to high-resolution, text-conditioned image generation in the latent space (a.k.a., LCM) remains unsatisfactory. In this paper, we identify three key flaws in the current design of LCM. We investigate the reasons behind these limitations and propose the Phased Consistency Model (PCM), which generalizes the design space and addresses all identified limitations. Our evaluations demonstrate that PCM significantly outperforms LCM across 1--16 step generation settings. While PCM is specifically designed for multi-step refinement, it achieves even superior or comparable 1-step generation results to previously state-of-the-art specifically designed 1-step methods. Furthermore, we show that PCM's methodology is versatile and applicable to video generation, enabling us to train the state-of-the-art few-step text-to-video generator. More details are available at https://g-u-n.github.io/projects/pcm/.

https://huggingface.co/discussions/paper/6656961f85c7a647ebc80109