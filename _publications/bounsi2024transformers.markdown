---
layout: publication
title: Transformers Meet Neural Algorithmic Reasoners
authors: "Wilfried Bounsi, Borja Ibarz, Andrew Dudzik, Jessica B. Hamrick, Larisa\
  \ Markeeva, Alex Vitvitskyi, Razvan Pascanu, Petar Veli\u010Dkovi\u0107"
conference: No Venue
year: 2024
bibkey: bounsi2024transformers
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2406.09308'}]
tags: ["Model Architecture"]
short_authors: Bounsi et al.
---
Transformers have revolutionized machine learning with their simple yet effective architecture. Pre-training Transformers on massive text datasets from the Internet has led to unmatched generalization for natural language understanding (NLU) tasks. However, such language models remain fragile when tasked with algorithmic forms of reasoning, where computations must be precise and robust. To address this limitation, we propose a novel approach that combines the Transformer's language understanding with the robustness of graph neural network (GNN)-based neural algorithmic reasoners (NARs). Such NARs proved effective as generic solvers for algorithmic tasks, when specified in graph form. To make their embeddings accessible to a Transformer, we propose a hybrid architecture with a two-phase training procedure, allowing the tokens in the language model to cross-attend to the node embeddings from the NAR. We evaluate our resulting TransNAR model on CLRS-Text, the text-based version of the CLRS-30 benchmark, and demonstrate significant gains over Transformer-only models for algorithmic reasoning, both in and out of distribution.

https://huggingface.co/discussions/paper/666ba87dfa1b45be6fea774d