---
layout: publication
title: 'Bytetransformer: A High-performance Transformer Boosted For Variable-length
  Inputs'
authors: Yujia Zhai et al.
conference: 2023 IEEE International Parallel and Distributed Processing Symposium
  (IPDPS)
year: 2022
citations: 29
bibkey: zhai2022high
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2210.03052'}]
tags: [Model Architecture, Attention Mechanism, Transformer, Fine-Tuning, Applications,
  Tools, Efficiency and Optimization, BERT]
---
Transformers have become keystone models in natural language processing over
the past decade. They have achieved great popularity in deep learning
applications, but the increasing sizes of the parameter spaces required by
transformer models generate a commensurate need to accelerate performance.
Natural language processing problems are also routinely faced with
variable-length sequences, as word counts commonly vary among sentences.
Existing deep learning frameworks pad variable-length sequences to a maximal
length, which adds significant memory and computational overhead. In this
paper, we present ByteTransformer, a high-performance transformer boosted for
variable-length inputs. We propose a padding-free algorithm that liberates the
entire transformer from redundant computations on zero padded tokens. In
addition to algorithmic-level optimization, we provide architecture-aware
optimizations for transformer functional modules, especially the
performance-critical algorithm Multi-Head Attention (MHA). Experimental results
on an NVIDIA A100 GPU with variable-length sequence inputs validate that our
fused MHA outperforms PyTorch by 6.13x. The end-to-end performance of
ByteTransformer for a forward BERT transformer surpasses state-of-the-art
transformer frameworks, such as PyTorch JIT, TensorFlow XLA, Tencent
TurboTransformer, Microsoft DeepSpeed-Inference and NVIDIA FasterTransformer,
by 87%, 131%, 138%, 74% and 55%, respectively. We also demonstrate the
general applicability of our optimization methods to other BERT-like models,
including ALBERT, DistilBERT, and DeBERTa.