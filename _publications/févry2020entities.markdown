---
layout: publication
title: 'Entities As Experts: Sparse Memory Access With Entity Supervision'
authors: "F\xE9vry et al."
conference: Proceedings of the 2020 Conference on Empirical Methods in Natural Language
  Processing (EMNLP)
year: 2020
bibkey: "f\xE9vry2020entities"
citations: 104
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2004.07202'}]
tags: [EMNLP, Transformer, BERT, Model Architecture, Reinforcement Learning]
---
We focus on the problem of capturing declarative knowledge about entities in
the learned parameters of a language model. We introduce a new model - Entities
as Experts (EAE) - that can access distinct memories of the entities mentioned
in a piece of text. Unlike previous efforts to integrate entity knowledge into
sequence models, EAE's entity representations are learned directly from text.
We show that EAE's learned representations capture sufficient knowledge to
answer TriviaQA questions such as "Which Dr. Who villain has been played by
Roger Delgado, Anthony Ainley, Eric Roberts?", outperforming an
encoder-generator Transformer model with 10x the parameters. According to the
LAMA knowledge probes, EAE contains more factual knowledge than a similarly
sized BERT, as well as previous approaches that integrate external sources of
entity knowledge. Because EAE associates parameters with specific entities, it
only needs to access a fraction of its parameters at inference time, and we
show that the correct identification and representation of entities is
essential to EAE's performance.