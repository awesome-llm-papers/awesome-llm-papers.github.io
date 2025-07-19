---
layout: publication
title: 'Tinyemo: Scaling Down Emotional Reasoning Via Metric Projection'
authors: Gutierrez Cristian
conference: IEEE Transactions on Image Processing
year: 2024
bibkey: gutierrez2024tinyemo
citations: 94
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2410.07062'}]
tags: [Interpretability And Explainability, Training Techniques, Tools, Ethics And
    Bias, Efficiency And Optimization, Fine Tuning, Datasets]
---
This paper introduces TinyEmo, a family of small multi-modal language models
for emotional reasoning and classification. Our approach features: (1) a
synthetic emotional instruct dataset for both pre-training and fine-tuning
stages, (2) a Metric Projector that delegates classification from the language
model allowing for more efficient training and inference, (3) a multi-modal
large language model (MM-LLM) for emotional reasoning, and (4) a semi-automated
framework for bias detection. TinyEmo is able to perform emotion classification
and emotional reasoning, all while using substantially fewer parameters than
comparable models. This efficiency allows us to freely incorporate more diverse
emotional datasets, enabling strong performance on classification tasks, with
our smallest model (700M parameters) outperforming larger state-of-the-art
models based on general-purpose MM-LLMs with over 7B parameters. Additionally,
the Metric Projector allows for interpretability and indirect bias detection in
large models without additional training, offering an approach to understand
and improve AI systems. We release code, models, and dataset at
https://github.com/ggcr/TinyEmo