---
layout: publication
title: 'Facts As Experts: Adaptable And Interpretable Neural Memory Over Symbolic
  Knowledge'
authors: Pat Verga, Haitian Sun, Livio Baldini Soares, William W. Cohen
conference: Arxiv
year: 2020
citations: 29
bibkey: verga2020facts
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2007.00849'}]
tags: [Reinforcement Learning, Training Techniques, Ethics and Bias]
---
Massive language models are the core of modern NLP modeling and have been
shown to encode impressive amounts of commonsense and factual information.
However, that knowledge exists only within the latent parameters of the model,
inaccessible to inspection and interpretation, and even worse, factual
information memorized from the training corpora is likely to become stale as
the world changes. Knowledge stored as parameters will also inevitably exhibit
all of the biases inherent in the source materials. To address these problems,
we develop a neural language model that includes an explicit interface between
symbolically interpretable factual information and subsymbolic neural
knowledge. We show that this model dramatically improves performance on two
knowledge-intensive question-answering tasks. More interestingly, the model can
be updated without re-training by manipulating its symbolic representations. In
particular this model allows us to add new facts and overwrite existing ones in
ways that are not possible for earlier models.