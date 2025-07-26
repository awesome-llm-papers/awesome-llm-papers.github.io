---
layout: publication
title: Adversarial Filters Of Dataset Biases
authors: Ronan Le Bras, Swabha Swayamdipta, Chandra Bhagavatula, Rowan Zellers, Matthew
  E. Peters, Ashish Sabharwal, Yejin Choi
conference: Arxiv
year: 2020
bibkey: bras2020adversarial
citations: 146
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2002.04108'}]
tags: ["Datasets", "Ethics & Fairness"]
short_authors: Bras et al.
---
Large neural models have demonstrated human-level performance on language and
vision benchmarks, while their performance degrades considerably on adversarial
or out-of-distribution samples. This raises the question of whether these
models have learned to solve a dataset rather than the underlying task by
overfitting to spurious dataset biases. We investigate one recently proposed
approach, AFLite, which adversarially filters such dataset biases, as a means
to mitigate the prevalent overestimation of machine performance. We provide a
theoretical understanding for AFLite, by situating it in the generalized
framework for optimum bias reduction. We present extensive supporting evidence
that AFLite is broadly applicable for reduction of measurable dataset biases,
and that models trained on the filtered datasets yield better generalization to
out-of-distribution tasks. Finally, filtering results in a large drop in model
performance (e.g., from 92% to 62% for SNLI), while human performance still
remains high. Our work thus shows that such filtered datasets can pose new
research challenges for robust generalization by serving as upgraded
benchmarks.