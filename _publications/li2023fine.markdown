---
layout: publication
title: Fine-tuning Multimodal Llms To Follow Zero-shot Demonstrative Instructions
authors: Li et al.
conference: 2022 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2023
bibkey: li2023fine
citations: 230
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2308.04152'}]
tags: [Training Techniques, Prompting, CVPR, Evaluation, Ethics And Bias, Reinforcement
    Learning, Fine Tuning, Multimodal Models, Datasets]
---
Recent advancements in Multimodal Large Language Models (MLLMs) have been
utilizing Visual Prompt Generators (VPGs) to convert visual features into
tokens that LLMs can recognize. This is achieved by training the VPGs on
millions of image-caption pairs, where the VPG-generated tokens of images are
fed into a frozen LLM to generate the corresponding captions. However, this
image-captioning based training objective inherently biases the VPG to
concentrate solely on the primary visual contents sufficient for caption
generation, often neglecting other visual details. This shortcoming results in
MLLMs' underperformance in comprehending demonstrative instructions consisting
of multiple, interleaved, and multimodal instructions that demonstrate the
required context to complete a task. To address this issue, we introduce a
generic and lightweight Visual Prompt Generator Complete module (VPG-C), which
can infer and complete the missing details essential for comprehending
demonstrative instructions. Further, we propose a synthetic discriminative
training strategy to fine-tune VPG-C, eliminating the need for supervised
demonstrative instructions. As for evaluation, we build DEMON, a comprehensive
benchmark for demonstrative instruction understanding. Synthetically trained
with the proposed strategy, VPG-C achieves significantly stronger zero-shot
performance across all tasks of DEMON. Further evaluation on the MME and
OwlEval benchmarks also demonstrate the superiority of VPG-C. Our benchmark,
code, and pre-trained models are available at
https://github.com/DCDmllm/Cheetah.