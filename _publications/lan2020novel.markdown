---
layout: publication
title: 'PONE: A Novel Automatic Evaluation Metric For Open-domain Generative Dialogue
  Systems'
authors: Tian Lan, Xian-ling Mao, Wei Wei, Xiaoyan Gao, Heyan Huang
conference: Arxiv
year: 2020
citations: 15
bibkey: lan2020novel
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2004.02399'}]
tags: [Model Architecture, Attention Mechanism, RAG, Reinforcement Learning, Evaluation]
---
Open-domain generative dialogue systems have attracted considerable attention
over the past few years. Currently, how to automatically evaluate them, is
still a big challenge problem. As far as we know, there are three kinds of
automatic methods to evaluate the open-domain generative dialogue systems: (1)
Word-overlap-based metrics; (2) Embedding-based metrics; (3) Learning-based
metrics. Due to the lack of systematic comparison, it is not clear which kind
of metrics are more effective. In this paper, we will first measure
systematically all kinds of automatic evaluation metrics over the same
experimental setting to check which kind is best. Through extensive
experiments, the learning-based metrics are demonstrated that they are the most
effective evaluation metrics for open-domain generative dialogue systems.
Moreover, we observe that nearly all learning-based metrics depend on the
negative sampling mechanism, which obtains an extremely imbalanced and
low-quality dataset to train a score model. In order to address this issue, we
propose a novel and feasible learning-based metric that can significantly
improve the correlation with human judgments by using augmented POsitive
samples and valuable NEgative samples, called PONE. Extensive experiments
demonstrate that our proposed evaluation method significantly outperforms the
state-of-the-art learning-based evaluation methods, with an average correlation
improvement of 13.18%. In addition, we have publicly released the codes of our
proposed method and state-of-the-art baselines.