---
layout: publication
title: 'Textmonkey: An Ocr-free Large Multimodal Model For Understanding Document'
authors: Liu et al.
conference: Lecture Notes in Computer Science
year: 2024
bibkey: liu2024textmonkey
citations: 134
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2403.04473'}]
tags: [Interpretability And Explainability, Training Techniques, Attention Mechanism,
  Evaluation, Model Architecture, Reinforcement Learning, Multimodal Models, Datasets]
---
We present TextMonkey, a large multimodal model (LMM) tailored for
text-centric tasks. Our approach introduces enhancement across several
dimensions: By adopting Shifted Window Attention with zero-initialization, we
achieve cross-window connectivity at higher input resolutions and stabilize
early training; We hypothesize that images may contain redundant tokens, and by
using similarity to filter out significant tokens, we can not only streamline
the token length but also enhance the model's performance. Moreover, by
expanding our model's capabilities to encompass text spotting and grounding,
and incorporating positional information into responses, we enhance
interpretability. It also learns to perform screenshot tasks through
finetuning. Evaluation on 12 benchmarks shows notable improvements: 5.2% in
Scene Text-Centric tasks (including STVQA, TextVQA, and OCRVQA), 6.9% in
Document-Oriented tasks (such as DocVQA, InfoVQA, ChartVQA, DeepForm, Kleister
Charity, and WikiTableQuestions), and 2.8% in Key Information Extraction tasks
(comprising FUNSD, SROIE, and POIE). It outperforms in scene text spotting with
a 10.9% increase and sets a new standard on OCRBench, a comprehensive
benchmark consisting of 29 OCR-related assessments, with a score of 561,
surpassing previous open-sourced large multimodal models for document
understanding. Code will be released at https://github.com/Yuliang-Liu/Monkey.