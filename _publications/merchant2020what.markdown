---
layout: publication
title: What Happens To BERT Embeddings During Fine-tuning?
authors: Amil Merchant, Elahe Rahimtoroghi, Ellie Pavlick, Ian Tenney
conference: Proceedings of the Third BlackboxNLP Workshop on Analyzing and Interpreting
  Neural Networks for NLP
year: 2020
bibkey: merchant2020what
citations: 126
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2004.14448'}]
tags: ["Fine-Tuning", "Model Architecture"]
short_authors: Merchant et al.
---
While there has been much recent work studying how linguistic information is
encoded in pre-trained sentence representations, comparatively little is
understood about how these models change when adapted to solve downstream
tasks. Using a suite of analysis techniques (probing classifiers,
Representational Similarity Analysis, and model ablations), we investigate how
fine-tuning affects the representations of the BERT model. We find that while
fine-tuning necessarily makes significant changes, it does not lead to
catastrophic forgetting of linguistic phenomena. We instead find that
fine-tuning primarily affects the top layers of BERT, but with noteworthy
variation across tasks. In particular, dependency parsing reconfigures most of
the model, whereas SQuAD and MNLI appear to involve much shallower processing.
Finally, we also find that fine-tuning has a weaker effect on representations
of out-of-domain sentences, suggesting room for improvement in model
generalization.