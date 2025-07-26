---
layout: publication
title: Hierarchical Transformers For Long Document Classification
authors: "Raghavendra Pappagari, Piotr \u017Belasko, Jes\xFAs Villalba, Yishay Carmiel,\
  \ Najim Dehak"
conference: 2019 IEEE Automatic Speech Recognition and Understanding Workshop (ASRU)
year: 2019
bibkey: pappagari2019hierarchical
citations: 192
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1910.10781'}]
tags: ["ASRU", "Model Architecture"]
short_authors: Pappagari et al.
---
BERT, which stands for Bidirectional Encoder Representations from
Transformers, is a recently introduced language representation model based upon
the transfer learning paradigm. We extend its fine-tuning procedure to address
one of its major limitations - applicability to inputs longer than a few
hundred words, such as transcripts of human call conversations. Our method is
conceptually simple. We segment the input into smaller chunks and feed each of
them into the base model. Then, we propagate each output through a single
recurrent layer, or another transformer, followed by a softmax activation. We
obtain the final classification decision after the last segment has been
consumed. We show that both BERT extensions are quick to fine-tune and converge
after as little as 1 epoch of training on a small, domain-specific data set. We
successfully apply them in three different tasks involving customer call
satisfaction prediction and topic classification, and obtain a significant
improvement over the baseline models in two of them.