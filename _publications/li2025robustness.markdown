---
layout: publication
title: On The Robustness Of Transformers Against Context Hijacking For Linear Classification
authors: Li et al.
conference: 2021 IEEE/CVF International Conference on Computer Vision (ICCV)
year: 2025
bibkey: li2025robustness
citations: 250
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2502.15609'}]
tags: [ICCV, Training Techniques, In Context Learning, Transformer, Model Architecture,
  Efficiency And Optimization, Reinforcement Learning, Security]
---
Transformer-based Large Language Models (LLMs) have demonstrated powerful
in-context learning capabilities. However, their predictions can be disrupted
by factually correct context, a phenomenon known as context hijacking,
revealing a significant robustness issue. To understand this phenomenon
theoretically, we explore an in-context linear classification problem based on
recent advances in linear transformers. In our setup, context tokens are
designed as factually correct query-answer pairs, where the queries are similar
to the final query but have opposite labels. Then, we develop a general
theoretical analysis on the robustness of the linear transformers, which is
formulated as a function of the model depth, training context lengths, and
number of hijacking context tokens. A key finding is that a well-trained deeper
transformer can achieve higher robustness, which aligns with empirical
observations. We show that this improvement arises because deeper layers enable
more fine-grained optimization steps, effectively mitigating interference from
context hijacking. This is also well supported by our numerical experiments.
Our findings provide theoretical insights into the benefits of deeper
architectures and contribute to enhancing the understanding of transformer
architectures.