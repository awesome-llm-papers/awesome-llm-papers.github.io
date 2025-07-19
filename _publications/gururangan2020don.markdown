---
layout: publication
title: 'Don''t Stop Pretraining: Adapt Language Models To Domains And Tasks'
authors: Gururangan et al.
conference: Proceedings of the 58th Annual Meeting of the Association for Computational
  Linguistics
year: 2020
bibkey: gururangan2020don
citations: 637
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2004.10964'}]
tags: [Training Techniques, ACL, RAG, Datasets, Alt]
---
Language models pretrained on text from a wide variety of sources form the
foundation of today's NLP. In light of the success of these broad-coverage
models, we investigate whether it is still helpful to tailor a pretrained model
to the domain of a target task. We present a study across four domains
(biomedical and computer science publications, news, and reviews) and eight
classification tasks, showing that a second phase of pretraining in-domain
(domain-adaptive pretraining) leads to performance gains, under both high- and
low-resource settings. Moreover, adapting to the task's unlabeled data
(task-adaptive pretraining) improves performance even after domain-adaptive
pretraining. Finally, we show that adapting to a task corpus augmented using
simple data selection strategies is an effective alternative, especially when
resources for domain-adaptive pretraining might be unavailable. Overall, we
consistently find that multi-phase adaptive pretraining offers large gains in
task performance.