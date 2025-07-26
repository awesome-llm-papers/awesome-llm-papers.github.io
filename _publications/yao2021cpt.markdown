---
layout: publication
title: 'CPT: Colorful Prompt Tuning For Pre-trained Vision-language Models'
authors: Yuan Yao, Ao Zhang, Zhengyan Zhang, Zhiyuan Liu, Tat-seng Chua, Maosong Sun
conference: Arxiv
year: 2021
bibkey: yao2021cpt
citations: 86
additional_links: [{name: Code, url: 'https://github.com/thunlp/CPT'}, {name: Paper,
    url: 'https://arxiv.org/abs/2109.11797'}]
tags: ["Fine-Tuning", "Prompting", "Training Techniques"]
short_authors: Yao et al.
---
Pre-Trained Vision-Language Models (VL-PTMs) have shown promising
capabilities in grounding natural language in image data, facilitating a broad
variety of cross-modal tasks. However, we note that there exists a significant
gap between the objective forms of model pre-training and fine-tuning,
resulting in a need for large amounts of labeled data to stimulate the visual
grounding capability of VL-PTMs for downstream tasks. To address the challenge,
we present Cross-modal Prompt Tuning (CPT, alternatively, Colorful Prompt
Tuning), a novel paradigm for tuning VL-PTMs, which reformulates visual
grounding into a fill-in-the-blank problem with color-based co-referential
markers in image and text, maximally mitigating the gap. In this way, CPT
enables strong few-shot and even zero-shot visual grounding capabilities of
VL-PTMs. Comprehensive experimental results show that the prompt-tuned VL-PTMs
outperform their fine-tuned counterparts by a large margin (e.g., 17.3%
absolute accuracy improvement, and 73.8% relative standard deviation reduction
on average with one shot in RefCOCO evaluation). We make the data and code for
this paper publicly available at https://github.com/thunlp/CPT.