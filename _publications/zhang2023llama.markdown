---
layout: publication
title: 'Llama-adapter: Efficient Fine-tuning Of Language Models With Zero-init Attention'
authors: Renrui Zhang, Jiaming Han, Chris Liu, Peng Gao, Aojun Zhou, Xiangfei Hu,
  Shilin Yan, Pan Lu, Hongsheng Li, Yu Qiao
conference: Arxiv
year: 2023
bibkey: zhang2023llama
citations: 139
additional_links: [{name: Code, url: 'https://github.com/OpenGVLab/LLaMA-Adapter'},
  {name: Paper, url: 'https://arxiv.org/abs/2303.16199'}]
tags: ["Fine-Tuning", "Model Architecture", "Training Techniques"]
short_authors: Zhang et al.
---
We present LLaMA-Adapter, a lightweight adaption method to efficiently
fine-tune LLaMA into an instruction-following model. Using 52K self-instruct
demonstrations, LLaMA-Adapter only introduces 1.2M learnable parameters upon
the frozen LLaMA 7B model, and costs less than one hour for fine-tuning on 8
A100 GPUs. Specifically, we adopt a set of learnable adaption prompts, and
prepend them to the word tokens at higher transformer layers. Then, a
zero-initialized attention mechanism with zero gating is proposed, which
adaptively injects the new instructional cues into LLaMA, while effectively
preserves its pre-trained knowledge. With our efficient training, LLaMA-Adapter
can generate high-quality responses, comparable to Alpaca with fully fine-tuned
7B parameters. Besides language commands, our approach can be simply extended
to multi-modal instructions for learning image-conditioned LLaMA model, which
achieves superior reasoning performance on ScienceQA and COCO Caption
benchmarks. Furthermore, we also evaluate the zero-initialized attention
mechanism for fine-tuning other pre-trained models (ViT, RoBERTa) on
traditional vision and language tasks, demonstrating the superior
generalization capacity of our approach. Code is released at
https://github.com/OpenGVLab/LLaMA-Adapter.