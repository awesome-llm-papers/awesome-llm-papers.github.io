---
layout: publication
title: 'PICARD: Parsing Incrementally For Constrained Auto-regressive Decoding From
  Language Models'
authors: Torsten Scholak, Nathan Schucher, Dzmitry Bahdanau
conference: Proceedings of the 2021 Conference on Empirical Methods in Natural Language
  Processing
year: 2021
bibkey: scholak2021picard
citations: 165
additional_links: [{name: Code, url: 'https://github.com/ElementAI/picard),'}, {name: Paper,
    url: 'https://arxiv.org/abs/2109.05093'}]
tags: ["EMNLP"]
short_authors: Torsten Scholak, Nathan Schucher, Dzmitry Bahdanau
---
Large pre-trained language models for textual data have an unconstrained
output space; at each decoding step, they can produce any of 10,000s of
sub-word tokens. When fine-tuned to target constrained formal languages like
SQL, these models often generate invalid code, rendering it unusable. We
propose PICARD (code and trained models available at
https://github.com/ElementAI/picard), a method for constraining auto-regressive
decoders of language models through incremental parsing. PICARD helps to find
valid output sequences by rejecting inadmissible tokens at each decoding step.
On the challenging Spider and CoSQL text-to-SQL translation tasks, we show that
PICARD transforms fine-tuned T5 models with passable performance into
state-of-the-art solutions.