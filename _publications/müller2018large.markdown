---
layout: publication
title: A Large-scale Test Set For The Evaluation Of Context-aware Pronoun Translation
  In Neural Machine Translation
authors: "Mathias M\xFCller, Annette Rios, Elena Voita, Rico Sennrich"
conference: 'Proceedings of the Third Conference on Machine Translation: Research
  Papers'
year: 2018
bibkey: "m\xFCller2018large"
citations: 152
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1810.02268'}]
tags: ["Evaluation"]
short_authors: "M\xFCller et al."
---
The translation of pronouns presents a special challenge to machine
translation to this day, since it often requires context outside the current
sentence. Recent work on models that have access to information across sentence
boundaries has seen only moderate improvements in terms of automatic evaluation
metrics such as BLEU. However, metrics that quantify the overall translation
quality are ill-equipped to measure gains from additional context. We argue
that a different kind of evaluation is needed to assess how well models
translate inter-sentential phenomena such as pronouns. This paper therefore
presents a test suite of contrastive translations focused specifically on the
translation of pronouns. Furthermore, we perform experiments with several
context-aware models. We show that, while gains in BLEU are moderate for those
systems, they outperform baselines by a large margin in terms of accuracy on
our contrastive test set. Our experiments also show the effectiveness of
parameter tying for multi-encoder architectures.