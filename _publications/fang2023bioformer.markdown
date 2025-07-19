---
layout: publication
title: 'Bioformer: An Efficient Transformer Language Model For Biomedical Text Mining'
authors: Fang et al.
conference: Bioinformatics
year: 2023
bibkey: fang2023bioformer
citations: 3737
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2302.01588'}]
tags: [Evaluation, Transformer, BERT, Model Architecture, Applications, Datasets]
---
Pretrained language models such as Bidirectional Encoder Representations from
Transformers (BERT) have achieved state-of-the-art performance in natural
language processing (NLP) tasks. Recently, BERT has been adapted to the
biomedical domain. Despite the effectiveness, these models have hundreds of
millions of parameters and are computationally expensive when applied to
large-scale NLP applications. We hypothesized that the number of parameters of
the original BERT can be dramatically reduced with minor impact on performance.
In this study, we present Bioformer, a compact BERT model for biomedical text
mining. We pretrained two Bioformer models (named Bioformer8L and Bioformer16L)
which reduced the model size by 60% compared to BERTBase. Bioformer uses a
biomedical vocabulary and was pre-trained from scratch on PubMed abstracts and
PubMed Central full-text articles. We thoroughly evaluated the performance of
Bioformer as well as existing biomedical BERT models including BioBERT and
PubMedBERT on 15 benchmark datasets of four different biomedical NLP tasks:
named entity recognition, relation extraction, question answering and document
classification. The results show that with 60% fewer parameters, Bioformer16L
is only 0.1% less accurate than PubMedBERT while Bioformer8L is 0.9% less
accurate than PubMedBERT. Both Bioformer16L and Bioformer8L outperformed
BioBERTBase-v1.1. In addition, Bioformer16L and Bioformer8L are 2-3 fold as
fast as PubMedBERT/BioBERTBase-v1.1. Bioformer has been successfully deployed
to PubTator Central providing gene annotations over 35 million PubMed abstracts
and 5 million PubMed Central full-text articles. We make Bioformer publicly
available via https://github.com/WGLab/bioformer, including pre-trained models,
datasets, and instructions for downstream use.