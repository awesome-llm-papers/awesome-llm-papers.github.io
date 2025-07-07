---
layout: publication
title: 'CLIP-TD: CLIP Targeted Distillation For Vision-language Tasks'
authors: Zhecan Wang et al.
conference: Arxiv
year: 2022
citations: 17
bibkey: wang2022clip
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2201.05729'}]
tags: [Distillation, Training Techniques, Reinforcement Learning, Efficiency and Optimization,
  Multimodal Models, Model Architecture]
---
Contrastive language-image pretraining (CLIP) links vision and language
modalities into a unified embedding space, yielding the tremendous potential
for vision-language (VL) tasks. While early concurrent works have begun to
study this potential on a subset of tasks, important questions remain: 1) What
is the benefit of CLIP on unstudied VL tasks? 2) Does CLIP provide benefit in
low-shot or domain-shifted scenarios? 3) Can CLIP improve existing approaches
without impacting inference or pretraining complexity? In this work, we seek to
answer these questions through two key contributions. First, we introduce an
evaluation protocol that includes Visual Commonsense Reasoning (VCR), Visual
Entailment (SNLI-VE), and Visual Question Answering (VQA), across a variety of
data availability constraints and conditions of domain shift. Second, we
propose an approach, named CLIP Targeted Distillation (CLIP-TD), to
intelligently distill knowledge from CLIP into existing architectures using a
dynamically weighted objective applied to adaptively selected tokens per
instance. Experiments demonstrate that our proposed CLIP-TD leads to
exceptional gains in the low-shot (up to 51.9%) and domain-shifted (up to
71.3%) conditions of VCR, while simultaneously improving performance under
standard fully-supervised conditions (up to 2%), achieving state-of-art
performance on VCR compared to other single models that are pretrained with
image-text data only. On SNLI-VE, CLIP-TD produces significant gains in
low-shot conditions (up to 6.6%) as well as fully supervised (up to 3%). On
VQA, CLIP-TD provides improvement in low-shot (up to 9%), and in
fully-supervised (up to 1.3%). Finally, CLIP-TD outperforms concurrent works
utilizing CLIP for finetuning, as well as baseline naive distillation
approaches. Code will be made available.