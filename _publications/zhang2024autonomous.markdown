---
layout: publication
title: Autonomous Data Selection With Zero-shot Generative Classifiers For Mathematical
  Texts
authors: Zhang et al.
conference: 2018 IEEE/CVF Conference on Computer Vision and Pattern Recognition
year: 2024
bibkey: zhang2024autonomous
citations: 261
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2402.07625'}]
tags: [RAG, Training Techniques, CVPR, Evaluation, Efficiency And Optimization, Datasets]
---
We present Autonomous Data Selection (AutoDS), a method that leverages base language models themselves as zero-shot "generative classifiers" to automatically curate high-quality mathematical texts. Unlike prior approaches that require human annotations or training a dedicated data filter, AutoDS relies solely on a model's logits to determine whether a given passage is mathematically informative and educational. By integrating AutoDS into a continual pretraining pipeline, we substantially boost downstream performance on challenging math benchmarks (MATH, GSM8K, and BBH) while using far fewer tokens than previous methods. Empirically, our approach achieves roughly a twofold improvement in pretraining token efficiency over strong baselines, underscoring the potential of self-directed data selection in enhancing mathematical reasoning. We release our curated AutoMathText dataset to facilitate future research in automated domain-specific data curation. The AutoMathText dataset is available at https://huggingface.co/datasets/math-ai/AutoMathText. The code is available at https://github.com/yifanzhang-pro/AutoMathText.