---
layout: publication
title: 'GTC: Guided Training Of CTC Towards Efficient And Accurate Scene Text Recognition'
authors: Hu et al.
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2020
bibkey: hu2020gtc
citations: 118
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2002.01276'}]
tags: [RAG, Training Techniques, Attention Mechanism, Evaluation, Transformer, Model
    Architecture, AAAI, Datasets]
---
Connectionist Temporal Classification (CTC) and attention mechanism are two
main approaches used in recent scene text recognition works. Compared with
attention-based methods, CTC decoder has a much shorter inference time, yet a
lower accuracy. To design an efficient and effective model, we propose the
guided training of CTC (GTC), where CTC model learns a better alignment and
feature representations from a more powerful attentional guidance. With the
benefit of guided training, CTC model achieves robust and accurate prediction
for both regular and irregular scene text while maintaining a fast inference
speed. Moreover, to further leverage the potential of CTC decoder, a graph
convolutional network (GCN) is proposed to learn the local correlations of
extracted features. Extensive experiments on standard benchmarks demonstrate
that our end-to-end model achieves a new state-of-the-art for regular and
irregular scene text recognition and needs 6 times shorter inference time than
attentionbased methods.