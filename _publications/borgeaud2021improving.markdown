---
layout: publication
title: Improving Language Models By Retrieving From Trillions Of Tokens
authors: Sebastian Borgeaud, Arthur Mensch, Jordan Hoffmann, Trevor Cai, Eliza Rutherford,
  Katie Millican, George van Den Driessche, Jean-baptiste Lespiau, Bogdan Damoc, Aidan
  Clark, Diego de Las Casas, Aurelia Guy, Jacob Menick, Roman Ring, Tom Hennigan,
  Saffron Huang, Loren Maggiore, Chris Jones, Albin Cassirer, Andy Brock, Michela
  Paganini, Geoffrey Irving, Oriol Vinyals, Simon Osindero, Karen Simonyan, Jack W.
  Rae, Erich Elsen, Laurent Sifre
conference: Arxiv
year: 2021
bibkey: borgeaud2021improving
citations: 184
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2112.04426'}]
tags: ["Retrieval Systems"]
short_authors: Borgeaud et al.
---
We enhance auto-regressive language models by conditioning on document chunks
retrieved from a large corpus, based on local similarity with preceding tokens.
With a \\(2\\) trillion token database, our Retrieval-Enhanced Transformer (RETRO)
obtains comparable performance to GPT-3 and Jurassic-1 on the Pile, despite
using 25\\(\times\\) fewer parameters. After fine-tuning, RETRO performance
translates to downstream knowledge-intensive tasks such as question answering.
RETRO combines a frozen Bert retriever, a differentiable encoder and a chunked
cross-attention mechanism to predict tokens based on an order of magnitude more
data than what is typically consumed during training. We typically train RETRO
from scratch, yet can also rapidly RETROfit pre-trained transformers with
retrieval and still achieve good performance. Our work opens up new avenues for
improving language models through explicit memory at unprecedented scale.