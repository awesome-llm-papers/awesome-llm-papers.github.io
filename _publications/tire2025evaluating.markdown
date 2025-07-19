---
layout: publication
title: Evaluating The Impact Of Data Cleaning On The Quality Of Generated Pull Request
  Descriptions
authors: "Tire Kutay, \xC7akar Berk, T\xFCz\xFCn Eray"
conference: 2019 34th IEEE/ACM International Conference on Automated Software Engineering
  (ASE)
year: 2025
bibkey: tire2025evaluating
citations: 69
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2505.01120'}]
tags: [Tools, LLM For Code, Evaluation, LLM for Code, RAG, Datasets]
---
Pull Requests (PRs) are central to collaborative coding, summarizing code
changes for reviewers. However, many PR descriptions are incomplete,
uninformative, or have out-of-context content, compromising developer workflows
and hindering AI-based generation models trained on commit messages and
original descriptions as "ground truth." This study examines the prevalence of
"noisy" PRs and evaluates their impact on state-of-the-art description
generation models. To do so, we propose four cleaning heuristics to filter
noise from an initial dataset of 169K+ PRs drawn from 513 GitHub repositories.
We train four models-BART, T5, PRSummarizer, and iTAPE-on both raw and cleaned
datasets. Performance is measured via ROUGE-1, ROUGE-2, and ROUGE-L metrics,
alongside a manual evaluation to assess description quality improvements from a
human perspective. Cleaning the dataset yields significant gains: average F1
improvements of 8.6% (ROUGE-1), 8.7% (ROUGE-2), and 8.5% (ROUGE-L). Manual
assessment confirms higher readability and relevance in descriptions generated
by the best-performing model, BART when trained on cleaned data. Dataset
refinement markedly enhances PR description generation, offering a foundation
for more accurate AI-driven tools and guidelines to assist developers in
crafting high-quality PR descriptions.