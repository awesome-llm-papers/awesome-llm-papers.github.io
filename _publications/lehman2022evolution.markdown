---
layout: publication
title: Evolution Through Large Models
authors: Joel Lehman et al.
conference: Genetic and Evolutionary Computation
year: 2022
citations: 28
bibkey: lehman2022evolution
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2206.08896'}]
tags: [Agentic, Reinforcement Learning, Training Techniques, Pre-Training]
---
This paper pursues the insight that large language models (LLMs) trained to
generate code can vastly improve the effectiveness of mutation operators
applied to programs in genetic programming (GP). Because such LLMs benefit from
training data that includes sequential changes and modifications, they can
approximate likely changes that humans would make. To highlight the breadth of
implications of such evolution through large models (ELM), in the main
experiment ELM combined with MAP-Elites generates hundreds of thousands of
functional examples of Python programs that output working ambulating robots in
the Sodarace domain, which the original LLM had never seen in pre-training.
These examples then help to bootstrap training a new conditional language model
that can output the right walker for a particular terrain. The ability to
bootstrap new models that can output appropriate artifacts for a given context
in a domain where zero training data was previously available carries
implications for open-endedness, deep learning, and reinforcement learning.
These implications are explored here in depth in the hope of inspiring new
directions of research now opened up by ELM.