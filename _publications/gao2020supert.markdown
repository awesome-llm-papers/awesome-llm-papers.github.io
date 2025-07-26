---
layout: publication
title: 'SUPERT: Towards New Frontiers In Unsupervised Evaluation Metrics For Multi-document
  Summarization'
authors: Yang Gao, Wei Zhao, Steffen Eger
conference: Proceedings of the 58th Annual Meeting of the Association for Computational
  Linguistics
year: 2020
bibkey: gao2020supert
citations: 109
additional_links: [{name: Code, url: 'https://github.com/yg211/acl20-ref-free-eval'},
  {name: Paper, url: 'https://arxiv.org/abs/2005.03724'}]
tags: ["Evaluation"]
short_authors: Yang Gao, Wei Zhao, Steffen Eger
---
We study unsupervised multi-document summarization evaluation metrics, which
require neither human-written reference summaries nor human annotations (e.g.
preferences, ratings, etc.). We propose SUPERT, which rates the quality of a
summary by measuring its semantic similarity with a pseudo reference summary,
i.e. selected salient sentences from the source documents, using contextualized
embeddings and soft token alignment techniques. Compared to the
state-of-the-art unsupervised evaluation metrics, SUPERT correlates better with
human ratings by 18-39%. Furthermore, we use SUPERT as rewards to guide a
neural-based reinforcement learning summarizer, yielding favorable performance
compared to the state-of-the-art unsupervised summarizers. All source code is
available at https://github.com/yg211/acl20-ref-free-eval.