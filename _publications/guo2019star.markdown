---
layout: publication
title: Star-transformer
authors: Qipeng Guo, Xipeng Qiu, Pengfei Liu, Yunfan Shao, Xiangyang Xue, Zheng Zhang
conference: Proceedings of the 2019 Conference of the North
year: 2019
bibkey: guo2019star
citations: 137
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1902.09113'}]
tags: ["Model Architecture"]
short_authors: Guo et al.
---
Although Transformer has achieved great successes on many NLP tasks, its
heavy structure with fully-connected attention connections leads to
dependencies on large training data. In this paper, we present
Star-Transformer, a lightweight alternative by careful sparsification. To
reduce model complexity, we replace the fully-connected structure with a
star-shaped topology, in which every two non-adjacent nodes are connected
through a shared relay node. Thus, complexity is reduced from quadratic to
linear, while preserving capacity to capture both local composition and
long-range dependency. The experiments on four tasks (22 datasets) show that
Star-Transformer achieved significant improvements against the standard
Transformer for the modestly sized datasets.