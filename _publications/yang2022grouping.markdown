---
layout: publication
title: 'Gtrans: Grouping And Fusing Transformer Layers For Neural Machine Translation'
authors: Jian Yang et al.
conference: IEEE/ACM Transactions on Audio, Speech, and Language Processing
year: 2022
citations: 16
bibkey: yang2022grouping
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2207.14467'}]
tags: [Transformer, WMT, Model Architecture, Evaluation]
---
Transformer structure, stacked by a sequence of encoder and decoder network
layers, achieves significant development in neural machine translation.
However, vanilla Transformer mainly exploits the top-layer representation,
assuming the lower layers provide trivial or redundant information and thus
ignoring the bottom-layer feature that is potentially valuable. In this work,
we propose the Group-Transformer model (GTrans) that flexibly divides
multi-layer representations of both encoder and decoder into different groups
and then fuses these group features to generate target words. To corroborate
the effectiveness of the proposed method, extensive experiments and analytic
experiments are conducted on three bilingual translation benchmarks and two
multilingual translation tasks, including the IWLST-14, IWLST-17, LDC, WMT-14
and OPUS-100 benchmark. Experimental and analytical results demonstrate that
our model outperforms its Transformer counterparts by a consistent gain.
Furthermore, it can be successfully scaled up to 60 encoder layers and 36
decoder layers.