---
layout: publication
title: Identifying Multi-modal Knowledge Neurons In Pretrained Transformers Via Two-stage
  Filtering
authors: Sato Yugen, Takagi Tomohiro
conference: 'Proceedings of the 60th Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2025
bibkey: sato2025identifying
citations: 50
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2503.22941'}]
tags: [Model Architecture, Interpretability And Explainability, Evaluation, BERT,
  ACL, Transformer, GPT, Multimodal Models, Datasets, Alt]
---
Recent advances in large language models (LLMs) have led to the development
of multimodal LLMs (MLLMs) in the fields of natural language processing (NLP)
and computer vision. Although these models allow for integrated visual and
language understanding, they present challenges such as opaque internal
processing and the generation of hallucinations and misinformation. Therefore,
there is a need for a method to clarify the location of knowledge in MLLMs.
  In this study, we propose a method to identify neurons associated with
specific knowledge using MiniGPT-4, a Transformer-based MLLM. Specifically, we
extract knowledge neurons through two stages: activation differences filtering
using inpainting and gradient-based filtering using GradCAM. Experiments on the
image caption generation task using the MS COCO 2017 dataset, BLEU, ROUGE, and
BERTScore quantitative evaluation, and qualitative evaluation using an
activation heatmap showed that our method is able to locate knowledge with
higher accuracy than existing methods.
  This study contributes to the visualization and explainability of knowledge
in MLLMs and shows the potential for future knowledge editing and control.