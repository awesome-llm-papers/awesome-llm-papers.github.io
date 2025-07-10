---
layout: publication
title: 'Indicbart: A Pre-trained Model For Indic Natural Language Generation'
authors: Raj Dabre et al.
conference: 'Findings of the Association for Computational Linguistics: ACL 2022'
year: 2021
citations: 19
bibkey: dabre2021pre
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2109.02903'}]
tags: [Training Techniques, Fine-Tuning, Pre-Training]
---
In this paper, we study pre-trained sequence-to-sequence models for a group
of related languages, with a focus on Indic languages. We present IndicBART, a
multilingual, sequence-to-sequence pre-trained model focusing on 11 Indic
languages and English. IndicBART utilizes the orthographic similarity between
Indic scripts to improve transfer learning between similar Indic languages. We
evaluate IndicBART on two NLG tasks: Neural Machine Translation (NMT) and
extreme summarization. Our experiments on NMT and extreme summarization show
that a model specific to related languages like IndicBART is competitive with
large pre-trained models like mBART50 despite being significantly smaller. It
also performs well on very low-resource translation scenarios where languages
are not included in pre-training or fine-tuning. Script sharing, multilingual
training, and better utilization of limited model capacity contribute to the
good performance of the compact IndicBART model.