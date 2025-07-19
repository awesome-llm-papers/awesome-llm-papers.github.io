---
layout: publication
title: 'Adaptation Of Biomedical And Clinical Pretrained Models To French Long Documents:
  A Comparative Study'
authors: Bazoge et al.
conference: Journal of the American Medical Informatics Association
year: 2024
bibkey: bazoge2024adaptation
citations: 69
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2402.16689'}]
tags: [RAG, Training Techniques, Alt, Evaluation, BERT, Model Architecture]
---
Recently, pretrained language models based on BERT have been introduced for
the French biomedical domain. Although these models have achieved
state-of-the-art results on biomedical and clinical NLP tasks, they are
constrained by a limited input sequence length of 512 tokens, which poses
challenges when applied to clinical notes. In this paper, we present a
comparative study of three adaptation strategies for long-sequence models,
leveraging the Longformer architecture. We conducted evaluations of these
models on 16 downstream tasks spanning both biomedical and clinical domains.
Our findings reveal that further pre-training an English clinical model with
French biomedical texts can outperform both converting a French biomedical BERT
to the Longformer architecture and pre-training a French biomedical Longformer
from scratch. The results underscore that long-sequence French biomedical
models improve performance across most downstream tasks regardless of sequence
length, but BERT based models remain the most efficient for named entity
recognition tasks.