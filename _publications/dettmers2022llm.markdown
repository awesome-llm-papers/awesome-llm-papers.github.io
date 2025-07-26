---
layout: publication
title: 'Llm.int8(): 8-bit Matrix Multiplication For Transformers At Scale'
authors: Tim Dettmers, Mike Lewis, Younes Belkada, Luke Zettlemoyer
conference: Arxiv
year: 2022
bibkey: dettmers2022llm
citations: 87
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2208.07339'}]
tags: ["Efficiency", "Model Architecture"]
short_authors: Dettmers et al.
---
Large language models have been widely adopted but require significant GPU
memory for inference. We develop a procedure for Int8 matrix multiplication for
feed-forward and attention projection layers in transformers, which cut the
memory needed for inference by half while retaining full precision performance.
With our method, a 175B parameter 16/32-bit checkpoint can be loaded, converted
to Int8, and used immediately without performance degradation. This is made
possible by understanding and working around properties of highly systematic
emergent features in transformer language models that dominate attention and
transformer predictive performance. To cope with these features, we develop a
two-part quantization procedure, LLM.int8(). We first use vector-wise
quantization with separate normalization constants for each inner product in
the matrix multiplication, to quantize most of the features. However, for the
emergent outliers, we also include a new mixed-precision decomposition scheme,
which isolates the outlier feature dimensions into a 16-bit matrix
multiplication while still more than 99.9% of values are multiplied in 8-bit.
Using LLM.int8(), we show empirically it is possible to perform inference in
LLMs with up to 175B parameters without any performance degradation. This
result makes such models much more accessible, for example making it possible
to use OPT-175B/BLOOM on a single server with consumer GPUs. We open-source our
software.