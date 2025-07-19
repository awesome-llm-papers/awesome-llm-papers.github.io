---
layout: publication
title: 'Hierarchical Context Merging: Better Long Context Understanding For Pre-trained
  Llms'
authors: Song et al.
conference: Lecture Notes in Computer Science
year: 2024
bibkey: song2024hierarchical
citations: 1457
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2404.10308'}]
tags: [Training Techniques, Attention Mechanism, Transformer, Model Architecture,
  Efficiency And Optimization, Merging]
---
Large language models (LLMs) have shown remarkable performance in various
natural language processing tasks. However, a primary constraint they face is
the context limit, i.e., the maximum number of tokens they can process.
Previous works have explored architectural changes and modifications in
positional encoding to relax the constraint, but they often require expensive
training or do not address the computational demands of self-attention. In this
paper, we present Hierarchical cOntext MERging (HOMER), a new training-free
scheme designed to overcome the limitations. HOMER uses a divide-and-conquer
algorithm, dividing long inputs into manageable chunks. Each chunk is then
processed collectively, employing a hierarchical strategy that merges adjacent
chunks at progressive transformer layers. A token reduction technique precedes
each merging, ensuring memory usage efficiency. We also propose an optimized
computational order reducing the memory requirement to logarithmically scale
with respect to input length, making it especially favorable for environments
with tight memory restrictions. Our experiments demonstrate the proposed
method's superior performance and memory efficiency, enabling the broader use
of LLMs in contexts requiring extended context. Code is available at
https://github.com/alinlab/HOMER.