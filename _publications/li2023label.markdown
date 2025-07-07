---
layout: publication
title: Label Supervised Llama Finetuning
authors: Zongxi Li et al.
conference: Arxiv
year: 2023
citations: 17
bibkey: li2023label
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2310.01208'}]
tags: [RAG, Few-Shot, Reinforcement Learning, Fine-Tuning, BERT, Attention Mechanism,
  Prompting, Model Architecture]
---
The recent success of Large Language Models (LLMs) has gained significant
attention in both academia and industry. Substantial efforts have been made to
enhance the zero- and few-shot generalization capabilities of open-source LLMs
through finetuning. Currently, the prevailing approach is instruction-tuning,
which trains LLMs to complete real-world tasks by generating responses guided
by natural language instructions. It is worth noticing that such an approach
may underperform in sequence and token classification tasks. Unlike text
generation tasks, classification tasks have a limited label space, where
precise label prediction is more appreciated than generating diverse and
human-like responses. Prior research has unveiled that instruction-tuned LLMs
cannot outperform BERT, prompting us to explore the potential of leveraging
latent representations from LLMs for supervised label prediction. In this
paper, we introduce a label-supervised adaptation for LLMs, which aims to
finetuning the model with discriminant labels. We evaluate this approach with
Label Supervised LLaMA (LS-LLaMA), based on LLaMA-2-7B, a relatively
small-scale LLM, and can be finetuned on a single GeForce RTX4090 GPU. We
extract latent representations from the final LLaMA layer and project them into
the label space to compute the cross-entropy loss. The model is finetuned by
Low-Rank Adaptation (LoRA) to minimize this loss. Remarkably, without intricate
prompt engineering or external knowledge, LS-LLaMA substantially outperforms
LLMs ten times its size in scale and demonstrates consistent improvements
compared to robust baselines like BERT-Large and RoBERTa-Large in text
classification. Moreover, by removing the causal mask from decoders, LS-unLLaMA
achieves the state-of-the-art performance in named entity recognition (NER).
Our work will shed light on a novel approach to adapting LLMs for various
downstream tasks.