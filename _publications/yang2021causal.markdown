---
layout: publication
title: Causal Attention For Vision-language Tasks
authors: Xu Yang, Hanwang Zhang, Guojun Qi, Jianfei Cai
conference: 2021 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2021
bibkey: yang2021causal
citations: 107
additional_links: [{name: Code, url: 'https://github.com/yangxuntu/catt'}, {name: Paper,
    url: 'https://arxiv.org/abs/2103.03493'}]
tags: ["CVPR", "Model Architecture"]
short_authors: Yang et al.
---
We present a novel attention mechanism: Causal Attention (CATT), to remove
the ever-elusive confounding effect in existing attention-based vision-language
models. This effect causes harmful bias that misleads the attention module to
focus on the spurious correlations in training data, damaging the model
generalization. As the confounder is unobserved in general, we use the
front-door adjustment to realize the causal intervention, which does not
require any knowledge on the confounder. Specifically, CATT is implemented as a
combination of 1) In-Sample Attention (IS-ATT) and 2) Cross-Sample Attention
(CS-ATT), where the latter forcibly brings other samples into every IS-ATT,
mimicking the causal intervention. CATT abides by the Q-K-V convention and
hence can replace any attention module such as top-down attention and
self-attention in Transformers. CATT improves various popular attention-based
vision-language models by considerable margins. In particular, we show that
CATT has great potential in large-scale pre-training, e.g., it can promote the
lighter LXMERT~\cite\{tan2019lxmert\}, which uses fewer data and less
computational power, comparable to the heavier UNITER~\cite\{chen2020uniter\}.
Code is published in https://github.com/yangxuntu/catt.