---
layout: publication
title: Efficient Model Development Through Fine-tuning Transfer
authors: Lin et al.
conference: 2019 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2025
bibkey: lin2025efficient
citations: 289
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2503.20110'}]
tags: [Training Techniques, CVPR, Evaluation, Efficiency And Optimization, Reinforcement
    Learning, Fine Tuning]
---
Modern LLMs struggle with efficient updates, as each new pretrained model
version requires repeating expensive alignment processes. This challenge also
applies to domain- or language-specific models, where fine-tuning on
specialized data must be redone for every new base model release. In this
paper, we explore the transfer of fine-tuning updates between model versions.
Specifically, we derive the diff vector from one source model version, which
represents the weight changes from fine-tuning, and apply it to the base model
of a different target version. Through empirical evaluations on various
open-weight model versions, we show that transferring diff vectors can
significantly improve the target base model, often achieving performance
comparable to its fine-tuned counterpart. For example, reusing the fine-tuning
updates from Llama 3.0 8B leads to an absolute accuracy improvement of 10.7% on
GPQA over the base Llama 3.1 8B without additional training, surpassing Llama
3.1 8B Instruct. In a multilingual model development setting, we show that this
approach can significantly increase performance on target-language tasks
without retraining, achieving an absolute improvement of 4.7% and 15.5% on
Global MMLU for Malagasy and Turkish, respectively, compared to Llama 3.1 8B
Instruct. Our controlled experiments reveal that fine-tuning transfer is most
effective when the source and target models are linearly connected in the
parameter space. Additionally, we demonstrate that fine-tuning transfer offers
a stronger and more computationally efficient starting point for further
fine-tuning. Finally, we propose an iterative recycling-then-finetuning
approach for continuous model development, which improves both efficiency and
effectiveness. Our findings suggest that fine-tuning transfer is a viable
strategy to reduce training costs while maintaining model performance.