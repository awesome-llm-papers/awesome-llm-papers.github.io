---
layout: publication
title: Neural Text Generation From Structured Data With Application To The Biography
  Domain
authors: Remi Lebret, David Grangier, Michael Auli
conference: Arxiv
year: 2016
citations: 140
bibkey: lebret2016neural
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1603.07771'}]
tags: [Language Modeling, Reinforcement Learning]
---
This paper introduces a neural model for concept-to-text generation that
scales to large, rich domains. We experiment with a new dataset of biographies
from Wikipedia that is an order of magnitude larger than existing resources
with over 700k samples. The dataset is also vastly more diverse with a 400k
vocabulary, compared to a few hundred words for Weathergov or Robocup. Our
model builds upon recent work on conditional neural language model for text
generation. To deal with the large vocabulary, we extend these models to mix a
fixed vocabulary with copy actions that transfer sample-specific words from the
input database to the generated output sentence. Our neural model significantly
out-performs a classical Kneser-Ney language model adapted to this task by
nearly 15 BLEU.