---
layout: publication
title: Disentangling Language And Knowledge In Task-oriented Dialogs
authors: Dinesh Raghu, Nikhil Gupta, Mausam
conference: Arxiv
year: 2018
citations: 16
bibkey: raghu2018disentangling
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1805.01216'}]
tags: [Applications, Interpretability and Explainability, Model Architecture, Reinforcement
    Learning]
---
The Knowledge Base (KB) used for real-world applications, such as booking a
movie or restaurant reservation, keeps changing over time. End-to-end neural
networks trained for these task-oriented dialogs are expected to be immune to
any changes in the KB. However, existing approaches breakdown when asked to
handle such changes. We propose an encoder-decoder architecture (BoSsNet) with
a novel Bag-of-Sequences (BoSs) memory, which facilitates the disentangled
learning of the response's language model and its knowledge incorporation.
Consequently, the KB can be modified with new knowledge without a drop in
interpretability. We find that BoSsNet outperforms state-of-the-art models,
with considerable improvements (> 10%) on bAbI OOV test sets and other
human-human datasets. We also systematically modify existing datasets to
measure disentanglement and show BoSsNet to be robust to KB modifications.