---
layout: publication
title: Abductive Commonsense Reasoning
authors: Chandra Bhagavatula, Ronan Le Bras, Chaitanya Malaviya, Keisuke Sakaguchi,
  Ari Holtzman, Hannah Rashkin, Doug Downey, Scott Wen-tau Yih, Yejin Choi
conference: Arxiv
year: 2019
bibkey: bhagavatula2019abductive
citations: 240
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1908.05739'}]
tags: ["Datasets"]
short_authors: Bhagavatula et al.
---
Abductive reasoning is inference to the most plausible explanation. For
example, if Jenny finds her house in a mess when she returns from work, and
remembers that she left a window open, she can hypothesize that a thief broke
into her house and caused the mess, as the most plausible explanation. While
abduction has long been considered to be at the core of how people interpret
and read between the lines in natural language (Hobbs et al., 1988), there has
been relatively little research in support of abductive natural language
inference and generation. We present the first study that investigates the
viability of language-based abductive reasoning. We introduce a challenge
dataset, ART, that consists of over 20k commonsense narrative contexts and 200k
explanations. Based on this dataset, we conceptualize two new tasks -- (i)
Abductive NLI: a multiple-choice question answering task for choosing the more
likely explanation, and (ii) Abductive NLG: a conditional generation task for
explaining given observations in natural language. On Abductive NLI, the best
model achieves 68.9% accuracy, well below human performance of 91.4%. On
Abductive NLG, the current best language generators struggle even more, as they
lack reasoning capabilities that are trivial for humans. Our analysis leads to
new insights into the types of reasoning that deep pre-trained language models
fail to perform--despite their strong performance on the related but more
narrowly defined task of entailment NLI--pointing to interesting avenues for
future research.