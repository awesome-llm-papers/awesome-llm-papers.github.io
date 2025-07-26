---
layout: publication
title: 'Pythia: Ai-assisted Code Completion System'
authors: Alexey Svyatkovskiy, Ying Zhao, Shengyu Fu, Neel Sundaresan
conference: Proceedings of the 25th ACM SIGKDD International Conference on Knowledge
  Discovery &amp; Data Mining
year: 2019
bibkey: svyatkovskiy2019pythia
citations: 135
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1912.00742'}]
tags: ["Evaluation", "Has Code", "KDD", "Tools"]
short_authors: Svyatkovskiy et al.
---
In this paper, we propose a novel end-to-end approach for AI-assisted code
completion called Pythia. It generates ranked lists of method and API
recommendations which can be used by software developers at edit time. The
system is currently deployed as part of Intellicode extension in Visual Studio
Code IDE. Pythia exploits state-of-the-art large-scale deep learning models
trained on code contexts extracted from abstract syntax trees. It is designed
to work at a high throughput predicting the best matching code completions on
the order of 100 \\(ms\\).
  We describe the architecture of the system, perform comparisons to
frequency-based approach and invocation-based Markov Chain language model, and
discuss challenges serving Pythia models on lightweight client devices.
  The offline evaluation results obtained on 2700 Python open source software
GitHub repositories show a top-5 accuracy of 92%, surpassing the baseline
models by 20% averaged over classes, for both intra and cross-project
settings.