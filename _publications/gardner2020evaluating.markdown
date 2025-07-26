---
layout: publication
title: Evaluating Models' Local Decision Boundaries Via Contrast Sets
authors: Matt Gardner, Yoav Artzi, Victoria Basmova, Jonathan Berant, Ben Bogin, Sihao
  Chen, Pradeep Dasigi, Dheeru Dua, Yanai Elazar, Ananth Gottumukkala, Nitish Gupta,
  Hanna Hajishirzi, Gabriel Ilharco, Daniel Khashabi, Kevin Lin, Jiangming Liu, Nelson
  F. Liu, Phoebe Mulcaire, Qiang Ning, Sameer Singh, Noah A. Smith, Sanjay Subramanian,
  Reut Tsarfaty, Eric Wallace, Ally Zhang, Ben Zhou
conference: 'Findings of the Association for Computational Linguistics: EMNLP 2020'
year: 2020
bibkey: gardner2020evaluating
citations: 276
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2004.02709'}]
tags: ["EMNLP", "Evaluation"]
short_authors: Gardner et al.
---
Standard test sets for supervised learning evaluate in-distribution
generalization. Unfortunately, when a dataset has systematic gaps (e.g.,
annotation artifacts), these evaluations are misleading: a model can learn
simple decision rules that perform well on the test set but do not capture a
dataset's intended capabilities. We propose a new annotation paradigm for NLP
that helps to close systematic gaps in the test data. In particular, after a
dataset is constructed, we recommend that the dataset authors manually perturb
the test instances in small but meaningful ways that (typically) change the
gold label, creating contrast sets. Contrast sets provide a local view of a
model's decision boundary, which can be used to more accurately evaluate a
model's true linguistic capabilities. We demonstrate the efficacy of contrast
sets by creating them for 10 diverse NLP datasets (e.g., DROP reading
comprehension, UD parsing, IMDb sentiment analysis). Although our contrast sets
are not explicitly adversarial, model performance is significantly lower on
them than on the original test sets---up to 25% in some cases. We release our
contrast sets as new evaluation benchmarks and encourage future dataset
construction efforts to follow similar annotation processes.