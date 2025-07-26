---
layout: publication
title: Evaluation Of BERT And ALBERT Sentence Embedding Performance On Downstream
  NLP Tasks
authors: Hyunjin Choi, Judong Kim, Seongho Joe, Youngjune Gwon
conference: 2020 25th International Conference on Pattern Recognition (ICPR)
year: 2021
bibkey: choi2021evaluation
citations: 93
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2101.10642'}]
tags: ["Evaluation", "Model Architecture"]
short_authors: Choi et al.
---
Contextualized representations from a pre-trained language model are central
to achieve a high performance on downstream NLP task. The pre-trained BERT and
A Lite BERT (ALBERT) models can be fine-tuned to give state-ofthe-art results
in sentence-pair regressions such as semantic textual similarity (STS) and
natural language inference (NLI). Although BERT-based models yield the [CLS]
token vector as a reasonable sentence embedding, the search for an optimal
sentence embedding scheme remains an active research area in computational
linguistics. This paper explores on sentence embedding models for BERT and
ALBERT. In particular, we take a modified BERT network with siamese and triplet
network structures called Sentence-BERT (SBERT) and replace BERT with ALBERT to
create Sentence-ALBERT (SALBERT). We also experiment with an outer CNN
sentence-embedding network for SBERT and SALBERT. We evaluate performances of
all sentence-embedding models considered using the STS and NLI datasets. The
empirical results indicate that our CNN architecture improves ALBERT models
substantially more than BERT models for STS benchmark. Despite significantly
fewer model parameters, ALBERT sentence embedding is highly competitive to BERT
in downstream NLP evaluations.