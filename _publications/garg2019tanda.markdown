---
layout: publication
title: 'TANDA: Transfer And Adapt Pre-trained Transformer Models For Answer Sentence
  Selection'
authors: Siddhant Garg, Thuy Vu, Alessandro Moschitti
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2020
bibkey: garg2019tanda
citations: 184
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1911.04118'}]
tags: ["AAAI", "Fine-Tuning", "Model Architecture", "Training Techniques"]
short_authors: Siddhant Garg, Thuy Vu, Alessandro Moschitti
---
We propose TANDA, an effective technique for fine-tuning pre-trained
Transformer models for natural language tasks. Specifically, we first transfer
a pre-trained model into a model for a general task by fine-tuning it with a
large and high-quality dataset. We then perform a second fine-tuning step to
adapt the transferred model to the target domain. We demonstrate the benefits
of our approach for answer sentence selection, which is a well-known inference
task in Question Answering. We built a large scale dataset to enable the
transfer step, exploiting the Natural Questions dataset. Our approach
establishes the state of the art on two well-known benchmarks, WikiQA and
TREC-QA, achieving MAP scores of 92% and 94.3%, respectively, which largely
outperform the previous highest scores of 83.4% and 87.5%, obtained in very
recent work. We empirically show that TANDA generates more stable and robust
models reducing the effort required for selecting optimal hyper-parameters.
Additionally, we show that the transfer step of TANDA makes the adaptation step
more robust to noise. This enables a more effective use of noisy datasets for
fine-tuning. Finally, we also confirm the positive impact of TANDA in an
industrial setting, using domain specific datasets subject to different types
of noise.