---
layout: publication
title: 'Factpegasus: Factuality-aware Pre-training And Fine-tuning For Abstractive
  Summarization'
authors: David Wan, Mohit Bansal
conference: Arxiv
year: 2022
citations: 16
bibkey: wan2022factuality
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2205.07830'}, {name: Code,
    url: 'https://github.com/meetdavidwan/factpegasus'}]
tags: [Training Techniques, Pre-Training, Few-Shot, Fine-Tuning, Has Code]
---
We present FactPEGASUS, an abstractive summarization model that addresses the
problem of factuality during pre-training and fine-tuning: (1) We augment the
sentence selection strategy of PEGASUS's (Zhang et al., 2020) pre-training
objective to create pseudo-summaries that are both important and factual; (2)
We introduce three complementary components for fine-tuning. The corrector
removes hallucinations present in the reference summary, the contrastor uses
contrastive learning to better differentiate nonfactual summaries from factual
ones, and the connector bridges the gap between the pre-training and
fine-tuning for better transfer of knowledge. Experiments on three downstream
tasks demonstrate that FactPEGASUS substantially improves factuality evaluated
by multiple automatic metrics and humans. Our thorough analysis suggests that
FactPEGASUS is more factual than using the original pre-training objective in
zero-shot and few-shot settings, retains factual behavior more robustly than
strong baselines, and does not rely entirely on becoming more extractive to
improve factuality. Our code and data are publicly available at:
https://github.com/meetdavidwan/factpegasus