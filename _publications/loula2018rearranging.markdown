---
layout: publication
title: 'Rearranging The Familiar: Testing Compositional Generalization In Recurrent
  Networks'
authors: "Jo\xE3o Loula, Marco Baroni, Brenden M. Lake"
conference: 'Proceedings of the 2018 EMNLP Workshop BlackboxNLP: Analyzing and Interpreting
  Neural Networks for NLP'
year: 2018
bibkey: loula2018rearranging
citations: 106
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1807.07545'}]
tags: ["EMNLP"]
short_authors: "Jo\xE3o Loula, Marco Baroni, Brenden M. Lake"
---
Systematic compositionality is the ability to recombine meaningful units with
regular and predictable outcomes, and it's seen as key to humans' capacity for
generalization in language. Recent work has studied systematic compositionality
in modern seq2seq models using generalization to novel navigation instructions
in a grounded environment as a probing tool, requiring models to quickly
bootstrap the meaning of new words. We extend this framework here to settings
where the model needs only to recombine well-trained functional words (such as
"around" and "right") in novel contexts. Our findings confirm and strengthen
the earlier ones: seq2seq models can be impressively good at generalizing to
novel combinations of previously-seen input, but only when they receive
extensive training on the specific pattern to be generalized (e.g.,
generalizing from many examples of "X around right" to "jump around right"),
while failing when generalization requires novel application of compositional
rules (e.g., inferring the meaning of "around right" from those of "right" and
"around").