---
layout: publication
title: 'Mmevalpro: Calibrating Multimodal Benchmarks Towards Trustworthy And Efficient
  Evaluation'
authors: Jinsheng Huang, Liang Chen, Taian Guo, Fu Zeng, Yusheng Zhao, Bohan Wu, Ye
  Yuan, Haozhe Zhao, Zhihui Guo, Yichi Zhang, Jingyang Yuan, Wei Ju, Luchen Liu, Tianyu
  Liu, Baobao Chang, Ming Zhang
conference: No Venue
year: 2024
bibkey: huang2024mmevalpro
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2407.00468'}]
tags: ["Efficiency", "Evaluation"]
short_authors: Huang et al.
---
Large Multimodal Models (LMMs) exhibit impressive cross-modal understanding and reasoning abilities, often assessed through multiple-choice questions (MCQs) that include an image, a question, and several options. However, many benchmarks used for such evaluations suffer from systematic biases. Remarkably, Large Language Models (LLMs) without any visual perception capabilities achieve non-trivial performance, undermining the credibility of these evaluations. To address this issue while maintaining the efficiency of MCQ evaluations, we propose MMEvalPro, a benchmark designed to avoid Type-I errors through a trilogy evaluation pipeline and more rigorous metrics. For each original question from existing benchmarks, human annotators augment it by creating one perception question and one knowledge anchor question through a meticulous annotation process. MMEvalPro comprises 2,138 question triplets, totaling 6,414 distinct questions. Two-thirds of these questions are manually labeled by human experts, while the rest are sourced from existing benchmarks (MMMU, ScienceQA, and MathVista). Compared with the existing benchmarks, our experiments with the latest LLMs and LMMs demonstrate that MMEvalPro is more challenging (the best LMM lags behind human performance by 31.73%, compared to an average gap of 8.03% in previous benchmarks) and more trustworthy (the best LLM trails the best LMM by 23.09%, whereas the gap for previous benchmarks is just 14.64%). Our in-depth analysis explains the reason for the large performance gap and justifies the trustworthiness of evaluation, underscoring its significant potential for advancing future research.

https://huggingface.co/discussions/paper/668352551d6b7ca699ee1956