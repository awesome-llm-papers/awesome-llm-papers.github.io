---
layout: publication
title: 'Dynamic Activation Pitfalls In Llama Models: An Empirical Study'
authors: Ma et al.
conference: Software &amp; Systems Modeling
year: 2024
bibkey: ma2024dynamic
citations: 52
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2405.09274'}]
tags: [Reinforcement Learning]
---
In this work, we systematically investigate the efficacy of dynamic
activation mechanisms within the LLaMA family of language models. Despite the
potential of dynamic activation methods to reduce computation and increase
speed in models using the ReLU activation function, our empirical findings have
uncovered several inherent pitfalls in the current dynamic activation schemes.
Through extensive experiments across various dynamic activation strategies, we
demonstrate that LLaMA models usually underperform when compared to their ReLU
counterparts, particularly in scenarios demanding high sparsity ratio. We
attribute these deficiencies to a combination of factors: 1) the inherent
complexity of dynamically predicting activation heads and neurons; 2) the
inadequate sparsity resulting from activation functions; 3) the insufficient
preservation of information resulting from KV cache skipping. Our analysis not
only sheds light on the limitations of dynamic activation in the context of
large-scale LLaMA models but also proposes roadmaps for enhancing the design of
future sparsity schemes.