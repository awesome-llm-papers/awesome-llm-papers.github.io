---
layout: publication
title: 'When In Doubt, Cascade: Towards Building Efficient And Capable Guardrails'
authors: Nagireddy et al.
conference: Journal of Conflict Resolution
year: 2024
bibkey: nagireddy2024when
citations: 132
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2407.06323'}]
tags: [RAG, Datasets, Ethics And Bias]
---
Large language models (LLMs) have convincing performance in a variety of
downstream tasks. However, these systems are prone to generating undesirable
outputs such as harmful and biased text. In order to remedy such generations,
the development of guardrail (or detector) models has gained traction.
Motivated by findings from developing a detector for social bias, we adopt the
notion of a use-mention distinction - which we identified as the primary source
of under-performance in the preliminary versions of our social bias detector.
Armed with this information, we describe a fully extensible and reproducible
synthetic data generation pipeline which leverages taxonomy-driven instructions
to create targeted and labeled data. Using this pipeline, we generate over 300K
unique contrastive samples and provide extensive experiments to systematically
evaluate performance on a suite of open source datasets. We show that our
method achieves competitive performance with a fraction of the cost in compute
and offers insight into iteratively developing efficient and capable guardrail
models.
  Warning: This paper contains examples of text which are toxic, biased, and
potentially harmful.