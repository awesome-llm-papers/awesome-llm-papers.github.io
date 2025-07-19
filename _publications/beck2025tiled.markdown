---
layout: publication
title: 'Tiled Flash Linear Attention: More Efficient Linear RNN And Xlstm Kernels'
authors: Beck et al.
conference: 2021 IEEE Winter Conference on Applications of Computer Vision (WACV)
year: 2025
bibkey: beck2025tiled
citations: 111
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2503.14376'}]
tags: [RAG, Training Techniques, Attention Mechanism, Alt, Evaluation, Transformer,
  Model Architecture, Time Series, Language Modeling, Applications, Large Scale Training,
  Datasets]
---
Linear RNNs with gating recently demonstrated competitive performance compared to Transformers in language modeling. Although their linear compute scaling in sequence length offers theoretical runtime advantages over Transformers, realizing these benefits in practice requires optimized custom kernels, as Transformers rely on the highly efficient Flash Attention kernels (Dao, 2024). Leveraging the chunkwise-parallel formulation of linear RNNs, Flash Linear Attention (FLA) (Yang & Zhang, 2024) shows that linear RNN kernels are faster than Flash Attention, by parallelizing over chunks of the input sequence. However, since the chunk size of FLA is limited, many intermediate states must be materialized in GPU memory. This leads to low arithmetic intensity and causes high memory consumption and IO cost, especially for long-context pre-training. In this work, we present Tiled Flash Linear Attention (TFLA), a novel kernel algorithm for linear RNNs, that enables arbitrary large chunk sizes and high arithmetic intensity by introducing an additional level of sequence parallelization within each chunk. First, we apply TFLA to the xLSTM with matrix memory, the mLSTM (Beck et al., 2024). Second, we propose an mLSTM variant with sigmoid input gate and reduced computation for even faster kernel runtimes at equal language modeling performance. In our speed benchmarks, we show that our new mLSTM kernels based on TFLA outperform highly optimized Flash Attention, Linear Attention and Mamba kernels, setting a new state of the art for efficient long-context sequence modeling primitives.