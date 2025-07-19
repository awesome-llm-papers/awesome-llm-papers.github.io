---
layout: publication
title: Meta-learning With Sparse Experience Replay For Lifelong Language Learning
authors: Holla et al.
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2020
bibkey: holla2020meta
citations: 187
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2009.04891'}]
tags: [AAAI]
---
Lifelong learning requires models that can continuously learn from sequential
streams of data without suffering catastrophic forgetting due to shifts in data
distributions. Deep learning models have thrived in the non-sequential learning
paradigm; however, when used to learn a sequence of tasks, they fail to retain
past knowledge and learn incrementally. We propose a novel approach to lifelong
learning of language tasks based on meta-learning with sparse experience replay
that directly optimizes to prevent forgetting. We show that under the realistic
setting of performing a single pass on a stream of tasks and without any task
identifiers, our method obtains state-of-the-art results on lifelong text
classification and relation extraction. We analyze the effectiveness of our
approach and further demonstrate its low computational and space complexity.