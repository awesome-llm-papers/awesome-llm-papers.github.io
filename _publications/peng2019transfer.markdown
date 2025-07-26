---
layout: publication
title: 'Transfer Learning In Biomedical Natural Language Processing: An Evaluation
  Of BERT And Elmo On Ten Benchmarking Datasets'
authors: Yifan Peng, Shankai Yan, Zhiyong Lu
conference: Proceedings of the 18th BioNLP Workshop and Shared Task
year: 2019
bibkey: peng2019transfer
citations: 750
additional_links: [{name: Code, url: 'https://github.com/ncbi-nlp/BLUE_Benchmark'},
  {name: Paper, url: 'https://arxiv.org/abs/1906.05474'}]
tags: ["Datasets", "Evaluation", "Fine-Tuning", "Model Architecture", "Training Techniques"]
short_authors: Yifan Peng, Shankai Yan, Zhiyong Lu
---
Inspired by the success of the General Language Understanding Evaluation
benchmark, we introduce the Biomedical Language Understanding Evaluation (BLUE)
benchmark to facilitate research in the development of pre-training language
representations in the biomedicine domain. The benchmark consists of five tasks
with ten datasets that cover both biomedical and clinical texts with different
dataset sizes and difficulties. We also evaluate several baselines based on
BERT and ELMo and find that the BERT model pre-trained on PubMed abstracts and
MIMIC-III clinical notes achieves the best results. We make the datasets,
pre-trained models, and codes publicly available at
https://github.com/ncbi-nlp/BLUE_Benchmark.