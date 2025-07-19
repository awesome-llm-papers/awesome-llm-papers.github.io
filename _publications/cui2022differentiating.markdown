---
layout: publication
title: Differentiating Student Feedbacks For Knowledge Tracing
authors: Cui et al.
conference: 2018 IEEE International Conference on Data Mining (ICDM)
year: 2022
bibkey: cui2022differentiating
citations: 97
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2212.14695'}]
tags: [Training Techniques, Tools, Efficiency And Optimization, Datasets, Merging]
---
Knowledge tracing (KT) is a crucial task in computer-aided education and
intelligent tutoring systems, predicting students' performance on new questions
from their responses to prior ones. An accurate KT model can capture a
student's mastery level of different knowledge topics, as reflected in their
predicted performance on different questions. This helps improve the learning
efficiency by suggesting appropriate new questions that complement students'
knowledge states. However, current KT models have significant drawbacks that
they neglect the imbalanced discrimination of historical responses. A
significant proportion of question responses provide limited information for
discerning students' knowledge mastery, such as those that demonstrate uniform
performance across different students. Optimizing the prediction of these cases
may increase overall KT accuracy, but also negatively impact the model's
ability to trace personalized knowledge states, especially causing a deceptive
surge of performance. Towards this end, we propose a framework to reweight the
contribution of different responses based on their discrimination in training.
Additionally, we introduce an adaptive predictive score fusion technique to
maintain accuracy on less discriminative responses, achieving proper balance
between student knowledge mastery and question difficulty. Experimental results
demonstrate that our framework enhances the performance of three mainstream KT
methods on three widely-used datasets.