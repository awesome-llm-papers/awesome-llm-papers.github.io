---
layout: publication
title: Multi-clue Reasoning With Memory Augmentation For Knowledge-based Visual Question
  Answering
authors: Yin et al.
conference: Proceedings of the Twenty-Sixth International Joint Conference on Artificial
  Intelligence
year: 2023
bibkey: yin2023multi
citations: 97
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2312.12723'}]
tags: [Tools, Evaluation, AAAI, IJCAI, Datasets, Reinforcement Learning]
---
Visual Question Answering (VQA) has emerged as one of the most challenging
tasks in artificial intelligence due to its multi-modal nature. However, most
existing VQA methods are incapable of handling Knowledge-based Visual Question
Answering (KB-VQA), which requires external knowledge beyond visible contents
to answer questions about a given image. To address this issue, we propose a
novel framework that endows the model with capabilities of answering more
general questions, and achieves a better exploitation of external knowledge
through generating Multiple Clues for Reasoning with Memory Neural Networks
(MCR-MemNN). Specifically, a well-defined detector is adopted to predict
image-question related relation phrases, each of which delivers two
complementary clues to retrieve the supporting facts from external knowledge
base (KB), which are further encoded into a continuous embedding space using a
content-addressable memory. Afterwards, mutual interactions between
visual-semantic representation and the supporting facts stored in memory are
captured to distill the most relevant information in three modalities (i.e.,
image, question, and KB). Finally, the optimal answer is predicted by choosing
the supporting fact with the highest score. We conduct extensive experiments on
two widely-used benchmarks. The experimental results well justify the
effectiveness of MCR-MemNN, as well as its superiority over other KB-VQA
methods.