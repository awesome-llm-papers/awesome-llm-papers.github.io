---
layout: publication
title: 'Kangaroo: Lossless Self-speculative Decoding Via Double Early Exiting'
authors: Fangcheng Liu, Yehui Tang, Zhenhua Liu, Yunsheng Ni, Kai Han, Yunhe Wang
conference: No Venue
year: 2024
bibkey: liu2024kangaroo
additional_links: [{name: Code, url: 'https://github.com/Equationliu/Kangaroo'}, {
    name: Code, url: 'https://huggingface.co/discussions/paper/66306c7bcde3fb5e077eafcf'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2404.18911'}]
tags: ["Has Code", "Tools", "Training Techniques"]
short_authors: Liu et al.
---
Speculative decoding has demonstrated its effectiveness in accelerating the inference of large language models while maintaining a consistent sampling distribution. However, the conventional approach of training a separate draft model to achieve a satisfactory token acceptance rate can be costly. Drawing inspiration from early exiting, we propose a novel self-speculative decoding framework Kangaroo, which uses a fixed shallow sub-network as a self-draft model, with the remaining layers serving as the larger target model. We train a lightweight and efficient adapter module on top of the sub-network to bridge the gap between the sub-network and the full model's representation ability. It is noteworthy that the inference latency of the self-draft model may no longer be negligible compared to the large model, necessitating strategies to increase the token acceptance rate while minimizing the drafting steps of the small model. To address this challenge, we introduce an additional early exiting mechanism for generating draft tokens. Specifically, we halt the small model's subsequent prediction during the drafting phase once the confidence level for the current token falls below a certain threshold. Extensive experiments on the Spec-Bench demonstrate the effectiveness of Kangaroo. Under single-sequence verification, Kangaroo achieves speedups up to 1.68times on Spec-Bench, outperforming Medusa-1 with 88.7% fewer additional parameters (67M compared to 591M). The code for Kangaroo is available at https://github.com/Equationliu/Kangaroo.

https://huggingface.co/discussions/paper/66306c7bcde3fb5e077eafcf