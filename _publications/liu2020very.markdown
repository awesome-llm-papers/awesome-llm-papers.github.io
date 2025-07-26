---
layout: publication
title: Very Deep Transformers For Neural Machine Translation
authors: Xiaodong Liu, Kevin Duh, Liyuan Liu, Jianfeng Gao
conference: Arxiv
year: 2020
bibkey: liu2020very
citations: 73
additional_links: [{name: Code, url: 'https://github.com/namisan/exdeep-nmt'}, {name: Paper,
    url: 'https://arxiv.org/abs/2008.07772'}]
tags: ["Model Architecture", "Training Techniques"]
short_authors: Liu et al.
---
We explore the application of very deep Transformer models for Neural Machine
Translation (NMT). Using a simple yet effective initialization technique that
stabilizes training, we show that it is feasible to build standard
Transformer-based models with up to 60 encoder layers and 12 decoder layers.
These deep models outperform their baseline 6-layer counterparts by as much as
2.5 BLEU, and achieve new state-of-the-art benchmark results on WMT14
English-French (43.8 BLEU and 46.4 BLEU with back-translation) and WMT14
English-German (30.1 BLEU).The code and trained models will be publicly
available at: https://github.com/namisan/exdeep-nmt.