---
layout: publication
title: Alternating Synthetic And Real Gradients For Neural Language Modeling
authors: Shang Fangxin, Zhang Hao
conference: Proceedings of the National Academy of Sciences
year: 2019
bibkey: shang2019alternating
citations: 69
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1902.10630'}]
tags: [Alt, Language Modeling, Training Techniques]
---
Training recurrent neural networks (RNNs) with backpropagation through time
(BPTT) has known drawbacks such as being difficult to capture longterm
dependencies in sequences. Successful alternatives to BPTT have not yet been
discovered. Recently, BP with synthetic gradients by a decoupled neural
interface module has been proposed to replace BPTT for training RNNs. On the
other hand, it has been shown that the representations learned with synthetic
and real gradients are different though they are functionally identical. In
this project, we explore ways of combining synthetic and real gradients with
application to neural language modeling tasks. Empirically, we demonstrate the
effectiveness of alternating training with synthetic and real gradients after
periodic warm restarts on language modeling tasks.