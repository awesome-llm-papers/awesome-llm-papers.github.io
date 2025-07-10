---
layout: publication
title: 'Hallusionbench: An Advanced Diagnostic Suite For Entangled Language Hallucination
  And Visual Illusion In Large Vision-language Models'
authors: Tianrui Guan et al.
conference: 2024 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2023
citations: 16
bibkey: guan2023advanced
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2310.14566'}, {name: Code,
    url: 'https://github.com/tianyi-lab/HallusionBench'}]
tags: [Has Code, Model Architecture, Multimodal Models, GPT, Evaluation]
---
We introduce HallusionBench, a comprehensive benchmark designed for the
evaluation of image-context reasoning. This benchmark presents significant
challenges to advanced large visual-language models (LVLMs), such as
GPT-4V(Vision), Gemini Pro Vision, Claude 3, and LLaVA-1.5, by emphasizing
nuanced understanding and interpretation of visual data. The benchmark
comprises 346 images paired with 1129 questions, all meticulously crafted by
human experts. We introduce a novel structure for these visual questions
designed to establish control groups. This structure enables us to conduct a
quantitative analysis of the models' response tendencies, logical consistency,
and various failure modes. In our evaluation on HallusionBench, we benchmarked
15 different models, highlighting a 31.42% question-pair accuracy achieved by
the state-of-the-art GPT-4V. Notably, all other evaluated models achieve
accuracy below 16%. Moreover, our analysis not only highlights the observed
failure modes, including language hallucination and visual illusion, but also
deepens an understanding of these pitfalls. Our comprehensive case studies
within HallusionBench shed light on the challenges of hallucination and
illusion in LVLMs. Based on these insights, we suggest potential pathways for
their future improvement. The benchmark and codebase can be accessed at
https://github.com/tianyi-lab/HallusionBench.