---
layout: publication
title: Impact Of Pretraining Term Frequencies On Few-shot Reasoning
authors: Yasaman Razeghi, Robert L. Iv Logan, Matt Gardner, Sameer Singh
conference: Arxiv
year: 2022
citations: 27
bibkey: razeghi2022impact
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2202.07206'}]
tags: [Training Techniques, GPT, RAG, Few-Shot, Model Architecture]
---
Pretrained Language Models (LMs) have demonstrated ability to perform
numerical reasoning by extrapolating from a few examples in few-shot settings.
However, the extent to which this extrapolation relies on robust reasoning is
unclear. In this paper, we investigate how well these models reason with terms
that are less frequent in the pretraining data. In particular, we examine the
correlations between the model performance on test instances and the frequency
of terms from those instances in the pretraining data. We measure the strength
of this correlation for a number of GPT-based language models (pretrained on
the Pile dataset) on various numerical deduction tasks (e.g., arithmetic and
unit conversion). Our results consistently demonstrate that models are more
accurate on instances whose terms are more prevalent, in some cases above
\\(70%\\) (absolute) more accurate on the top 10% frequent terms in comparison to
the bottom 10%. Overall, although LMs exhibit strong performance at few-shot
numerical reasoning tasks, our results raise the question of how much models
actually generalize beyond pretraining data, and we encourage researchers to
take the pretraining data into account when interpreting evaluation results.