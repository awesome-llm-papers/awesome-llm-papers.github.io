---
layout: publication
title: 'E-BERT: Efficient-yet-effective Entity Embeddings For BERT'
authors: "Nina Poerner, Ulli Waltinger, Hinrich Sch\xFCtze"
conference: 'Findings of the Association for Computational Linguistics: EMNLP 2020'
year: 2020
bibkey: poerner2019e
citations: 126
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1911.03681'}]
tags: ["EMNLP", "Model Architecture"]
short_authors: "Nina Poerner, Ulli Waltinger, Hinrich Sch\xFCtze"
---
We present a novel way of injecting factual knowledge about entities into the
pretrained BERT model (Devlin et al., 2019): We align Wikipedia2Vec entity
vectors (Yamada et al., 2016) with BERT's native wordpiece vector space and use
the aligned entity vectors as if they were wordpiece vectors. The resulting
entity-enhanced version of BERT (called E-BERT) is similar in spirit to ERNIE
(Zhang et al., 2019) and KnowBert (Peters et al., 2019), but it requires no
expensive further pretraining of the BERT encoder. We evaluate E-BERT on
unsupervised question answering (QA), supervised relation classification (RC)
and entity linking (EL). On all three tasks, E-BERT outperforms BERT and other
baselines. We also show quantitatively that the original BERT model is overly
reliant on the surface form of entity names (e.g., guessing that someone with
an Italian-sounding name speaks Italian), and that E-BERT mitigates this
problem.