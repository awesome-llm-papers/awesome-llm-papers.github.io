---
layout: publication
title: 'Fingpt-hpc: Efficient Pretraining And Finetuning Large Language Models For
  Financial Applications With High-performance Computing'
authors: Liu et al.
conference: SSRN Electronic Journal
year: 2024
bibkey: liu2024fingpt
citations: 99
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2402.13533'}]
tags: [RAG, Training Techniques, GPT, Transformer, Model Architecture, Efficiency
    And Optimization, Applications, Fine Tuning, Large Scale Training, Quantization]
---
Large language models (LLMs) are computationally intensive. The computation
workload and the memory footprint grow quadratically with the dimension (layer
width). Most of LLMs' parameters come from the linear layers of the transformer
structure and are highly redundant. These linear layers contribute more than
80% of the computation workload and 99% of the model size. To pretrain and
finetune LLMs efficiently, there are three major challenges to address: 1)
reducing redundancy of the linear layers; 2) reducing GPU memory footprint; 3)
improving GPU utilization when using distributed training. Prior methods, such
as LoRA and QLoRA, utilized low-rank matrices and quantization to reduce the
number of trainable parameters and model size, respectively. However, the
resulting model still consumes a large amount of GPU memory. In this paper, we
present high-performance GPU-based methods that exploit low-rank structures to
pretrain and finetune LLMs for financial applications. We replace one
conventional linear layer of the transformer structure with two narrower linear
layers, which allows us to reduce the number of parameters by several orders of
magnitude. By quantizing the parameters into low precision (8-bit and 4-bit),
the memory consumption of the resulting model is further reduced. Compared with
existing LLMs, our methods achieve a speedup of 1.3X and a model compression
ratio of 2.64X for pretaining without accuracy drop. For finetuning, our
methods achieve an average accuracy increase of 6.3% and 24.0% in general tasks
and financial tasks, respectively, and GPU memory consumption ratio of 6.3X.
The sizes of our models are smaller than 0.59 GB, allowing inference on a
smartphone.