---
layout: publication
title: 'T-NER: An All-round Python Library For Transformer-based Named Entity Recognition'
authors: Asahi Ushio, Jose Camacho-collados
conference: Arxiv
year: 2022
citations: 23
bibkey: ushio2022t
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2209.12616'}]
tags: [Tools, Transformer, Model Architecture, Training Techniques]
---
Language model (LM) pretraining has led to consistent improvements in many
NLP downstream tasks, including named entity recognition (NER). In this paper,
we present T-NER (Transformer-based Named Entity Recognition), a Python library
for NER LM finetuning. In addition to its practical utility, T-NER facilitates
the study and investigation of the cross-domain and cross-lingual
generalization ability of LMs finetuned on NER. Our library also provides a web
app where users can get model predictions interactively for arbitrary text,
which facilitates qualitative model evaluation for non-expert programmers. We
show the potential of the library by compiling nine public NER datasets into a
unified format and evaluating the cross-domain and cross-lingual performance
across the datasets. The results from our initial experiments show that
in-domain performance is generally competitive across datasets. However,
cross-domain generalization is challenging even with a large pretrained LM,
which has nevertheless capacity to learn domain-specific features if fine-tuned
on a combined dataset. To facilitate future research, we also release all our
LM checkpoints via the Hugging Face model hub.