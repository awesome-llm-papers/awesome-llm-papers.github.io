---
layout: publication
title: Inducing Relational Knowledge From BERT
authors: Zied Bouraoui, Jose Camacho-collados, Steven Schockaert
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2020
bibkey: bouraoui2019inducing
citations: 155
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1911.12753'}]
tags: ["AAAI", "Model Architecture"]
short_authors: Zied Bouraoui, Jose Camacho-collados, Steven Schockaert
---
One of the most remarkable properties of word embeddings is the fact that
they capture certain types of semantic and syntactic relationships. Recently,
pre-trained language models such as BERT have achieved groundbreaking results
across a wide range of Natural Language Processing tasks. However, it is
unclear to what extent such models capture relational knowledge beyond what is
already captured by standard word embeddings. To explore this question, we
propose a methodology for distilling relational knowledge from a pre-trained
language model. Starting from a few seed instances of a given relation, we
first use a large text corpus to find sentences that are likely to express this
relation. We then use a subset of these extracted sentences as templates.
Finally, we fine-tune a language model to predict whether a given word pair is
likely to be an instance of some relation, when given an instantiated template
for that relation as input.