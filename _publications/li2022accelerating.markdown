---
layout: publication
title: Accelerating Attention Through Gradient-based Learned Runtime Pruning
authors: Zheng Li, Soroush Ghodrati, Amir Yazdanbakhsh, Hadi Esmaeilzadeh, Mingu Kang
conference: Arxiv
year: 2022
citations: 29
bibkey: li2022accelerating
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2204.03227'}]
tags: [Training Techniques, Transformer, GPT, RAG, Reinforcement Learning, Attention
    Mechanism, BERT, Efficiency and Optimization, Pruning, Model Architecture]
---
Self-attention is a key enabler of state-of-art accuracy for various
transformer-based Natural Language Processing models. This attention mechanism
calculates a correlation score for each word with respect to the other words in
a sentence. Commonly, only a small subset of words highly correlates with the
word under attention, which is only determined at runtime. As such, a
significant amount of computation is inconsequential due to low attention
scores and can potentially be pruned. The main challenge is finding the
threshold for the scores below which subsequent computation will be
inconsequential. Although such a threshold is discrete, this paper formulates
its search through a soft differentiable regularizer integrated into the loss
function of the training. This formulation piggy backs on the back-propagation
training to analytically co-optimize the threshold and the weights
simultaneously, striking a formally optimal balance between accuracy and
computation pruning. To best utilize this mathematical innovation, we devise a
bit-serial architecture, dubbed LeOPArd, for transformer language models with
bit-level early termination microarchitectural mechanism. We evaluate our
design across 43 back-end tasks for MemN2N, BERT, ALBERT, GPT-2, and Vision
transformer models. Post-layout results show that, on average, LeOPArd yields
1.9x and 3.9x speedup and energy reduction, respectively, while keeping the
average accuracy virtually intact (<0.2% degradation)