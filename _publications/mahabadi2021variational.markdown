---
layout: publication
title: Variational Information Bottleneck For Effective Low-resource Fine-tuning
authors: Rabeeh Karimi Mahabadi, Yonatan Belinkov, James Henderson
conference: Arxiv
year: 2021
citations: 32
bibkey: mahabadi2021variational
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2106.05469'}, {name: Code,
    url: 'https://github.com/rabeehk/vibert'}]
tags: [Ethics and Bias, Training Techniques, Fine-Tuning, BERT, Has Code, Model Architecture]
---
While large-scale pretrained language models have obtained impressive results
when fine-tuned on a wide variety of tasks, they still often suffer from
overfitting in low-resource scenarios. Since such models are general-purpose
feature extractors, many of these features are inevitably irrelevant for a
given target task. We propose to use Variational Information Bottleneck (VIB)
to suppress irrelevant features when fine-tuning on low-resource target tasks,
and show that our method successfully reduces overfitting. Moreover, we show
that our VIB model finds sentence representations that are more robust to
biases in natural language inference datasets, and thereby obtains better
generalization to out-of-domain datasets. Evaluation on seven low-resource
datasets in different tasks shows that our method significantly improves
transfer learning in low-resource scenarios, surpassing prior work. Moreover,
it improves generalization on 13 out of 15 out-of-domain natural language
inference benchmarks. Our code is publicly available in
https://github.com/rabeehk/vibert.