---
layout: publication
title: Automatic Generation Of Pull Request Descriptions
authors: Zhongxin Liu, Xin Xia, Christoph Treude, David Lo, Shanping Li
conference: 2019 34th IEEE/ACM International Conference on Automated Software Engineering
  (ASE)
year: 2019
bibkey: liu2019automatic
citations: 97
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1909.06987'}]
tags: ["Datasets", "Evaluation", "Llm For Code", "Reinforcement Learning", "Training Techniques"]
short_authors: Liu et al.
---
Enabled by the pull-based development model, developers can easily contribute
to a project through pull requests (PRs). When creating a PR, developers can
add a free-form description to describe what changes are made in this PR and/or
why. Such a description is helpful for reviewers and other developers to gain a
quick understanding of the PR without touching the details and may reduce the
possibility of the PR being ignored or rejected. However, developers sometimes
neglect to write descriptions for PRs. For example, in our collected dataset
with over 333K PRs, more than 34% of the PR descriptions are empty. To
alleviate this problem, we propose an approach to automatically generate PR
descriptions based on the commit messages and the added source code comments in
the PRs. We regard this problem as a text summarization problem and solve it
using a novel sequence-to-sequence model. To cope with out-of-vocabulary words
in software artifacts and bridge the gap between the training loss function of
the sequence-to-sequence model and the evaluation metric ROUGE, which has been
shown to correspond to human evaluation, we integrate the pointer generator and
directly optimize for ROUGE using reinforcement learning and a special loss
function. We build a dataset with over 41K PRs and evaluate our approach on
this dataset through ROUGE and a human evaluation. Our evaluation results show
that our approach outperforms two baselines by significant margins.