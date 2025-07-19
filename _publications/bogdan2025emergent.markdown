---
layout: publication
title: Emergent Effects Of Scaling On The Functional Hierarchies Within Large Language
  Models
authors: Bogdan Paul C.
conference: Nature Human Behaviour
year: 2025
bibkey: bogdan2025emergent
citations: 178
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2501.07359'}]
tags: [Attention Mechanism, Alt, Transformer, Model Architecture, Reinforcement Learning]
---
Large language model (LLM) architectures are often described as functionally
hierarchical: Early layers process syntax, middle layers begin to parse
semantics, and late layers integrate information. The present work revisits
these ideas. This research submits simple texts to an LLM (e.g., "A church and
organ") and extracts the resulting activations. Then, for each layer, support
vector machines and ridge regressions are fit to predict a text's label and
thus examine whether a given layer encodes some information. Analyses using a
small model (Llama-3.2-3b; 28 layers) partly bolster the common hierarchical
perspective: Item-level semantics are most strongly represented early (layers
2-7), then two-item relations (layers 8-12), and then four-item analogies
(layers 10-15). Afterward, the representation of items and simple relations
gradually decreases in deeper layers that focus on more global information.
However, several findings run counter to a steady hierarchy view: First,
although deep layers can represent document-wide abstractions, deep layers also
compress information from early portions of the context window without
meaningful abstraction. Second, when examining a larger model
(Llama-3.3-70b-Instruct), stark fluctuations in abstraction level appear: As
depth increases, two-item relations and four-item analogies initially increase
in their representation, then markedly decrease, and afterward increase again
momentarily. This peculiar pattern consistently emerges across several
experiments. Third, another emergent effect of scaling is coordination between
the attention mechanisms of adjacent layers. Across multiple experiments using
the larger model, adjacent layers fluctuate between what information they each
specialize in representing. In sum, an abstraction hierarchy often manifests
across layers, but large models also deviate from this structure in curious
ways.