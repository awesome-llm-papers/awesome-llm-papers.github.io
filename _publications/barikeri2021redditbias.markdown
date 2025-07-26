---
layout: publication
title: 'Redditbias: A Real-world Resource For Bias Evaluation And Debiasing Of Conversational
  Language Models'
authors: "Soumya Barikeri, Anne Lauscher, Ivan Vuli\u0107, Goran Glava\u0161"
conference: 'Proceedings of the 59th Annual Meeting of the Association for Computational
  Linguistics and the 11th International Joint Conference on Natural Language Processing
  (Volume 1: Long Papers)'
year: 2021
bibkey: barikeri2021redditbias
citations: 82
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2106.03521'}]
tags: ["Ethics & Fairness", "Evaluation", "Tools"]
short_authors: Barikeri et al.
---
Text representation models are prone to exhibit a range of societal biases,
reflecting the non-controlled and biased nature of the underlying pretraining
data, which consequently leads to severe ethical issues and even bias
amplification. Recent work has predominantly focused on measuring and
mitigating bias in pretrained language models. Surprisingly, the landscape of
bias measurements and mitigation resources and methods for conversational
language models is still very scarce: it is limited to only a few types of
bias, artificially constructed resources, and completely ignores the impact
that debiasing methods may have on the final performance in dialog tasks, e.g.,
conversational response generation. In this work, we present RedditBias, the
first conversational data set grounded in the actual human conversations from
Reddit, allowing for bias measurement and mitigation across four important bias
dimensions: gender, race, religion, and queerness. Further, we develop an
evaluation framework which simultaneously 1) measures bias on the developed
RedditBias resource, and 2) evaluates model capability in dialog tasks after
model debiasing. We use the evaluation framework to benchmark the widely used
conversational DialoGPT model along with the adaptations of four debiasing
methods. Our results indicate that DialoGPT is biased with respect to religious
groups and that some debiasing techniques can remove this bias while preserving
downstream task performance.