---
layout: publication
title: Dynamic Base Model Shift For Delta Compression
authors: Huang et al.
conference: Proceedings of the 21st international conference on Parallel architectures
  and compilation techniques
year: 2025
bibkey: huang2025dynamic
citations: 274
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2505.11344'}]
tags: [RAG, Transformer, Model Architecture, Efficiency And Optimization, Quantization,
  Pruning]
---
Transformer-based models with the pretrain-finetune paradigm bring about significant progress, along with the heavy storage and deployment costs of finetuned models on multiple tasks. Delta compression attempts to lower the costs by reducing the redundancy of delta parameters (i.e., the difference between the finetuned and pre-trained model weights) through pruning or quantization. However, existing methods by default employ the pretrained model as the base model and compress the delta parameters for every task, which may causes significant performance degradation, especially when the compression rate is extremely high. To tackle this issue, we investigate the impact of different base models on the performance of delta compression and find that the pre-trained base model can hardly be optimal. To this end, we propose Dynamic Base Model Shift (DBMS), which dynamically adapts the base model to the target task before performing delta compression. Specifically, we adjust two parameters, which respectively determine the magnitude of the base model shift and the overall scale of delta compression, to boost the compression performance on each task. Through low-cost learning of these two parameters, our DBMS can maintain most of the finetuned model's performance even under an extremely high compression ratio setting, significantly surpassing existing methods. Moreover, our DBMS is orthogonal and can be integrated with a variety of other methods, and it has been evaluated across different types of models including language, vision transformer, and multi-modal models.