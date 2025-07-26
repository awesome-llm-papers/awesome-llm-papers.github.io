---
layout: publication
title: Multi-domain Neural Network Language Generation For Spoken Dialogue Systems
authors: Tsung-hsien Wen, Milica Gasic, Nikola Mrksic, Lina M. Rojas-barahona, Pei-hao
  Su, David Vandyke, Steve Young
conference: 'Proceedings of the 2016 Conference of the North American Chapter of the
  Association for Computational Linguistics: Human Language Technologies'
year: 2016
bibkey: wen2016multi
citations: 194
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1603.01232'}]
tags: ["NAACL"]
short_authors: Wen et al.
---
Moving from limited-domain natural language generation (NLG) to open domain
is difficult because the number of semantic input combinations grows
exponentially with the number of domains. Therefore, it is important to
leverage existing resources and exploit similarities between domains to
facilitate domain adaptation. In this paper, we propose a procedure to train
multi-domain, Recurrent Neural Network-based (RNN) language generators via
multiple adaptation steps. In this procedure, a model is first trained on
counterfeited data synthesised from an out-of-domain dataset, and then fine
tuned on a small set of in-domain utterances with a discriminative objective
function. Corpus-based evaluation results show that the proposed procedure can
achieve competitive performance in terms of BLEU score and slot error rate
while significantly reducing the data needed to train generators in new, unseen
domains. In subjective testing, human judges confirm that the procedure greatly
improves generator performance when only a small amount of data is available in
the domain.