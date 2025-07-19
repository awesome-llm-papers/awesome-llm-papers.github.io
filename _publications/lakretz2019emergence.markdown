---
layout: publication
title: The Emergence Of Number And Syntax Units In LSTM Language Models
authors: Lakretz et al.
conference: Arxiv
year: 2019
bibkey: lakretz2019emergence
citations: 52
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1903.07435'}]
tags: [Model Architecture, Language Modeling]
---
Recent work has shown that LSTMs trained on a generic language modeling
objective capture syntax-sensitive generalizations such as long-distance number
agreement. We have however no mechanistic understanding of how they accomplish
this remarkable feat. Some have conjectured it depends on heuristics that do
not truly take hierarchical structure into account. We present here a detailed
study of the inner mechanics of number tracking in LSTMs at the single neuron
level. We discover that long-distance number information is largely managed by
two `number units'. Importantly, the behaviour of these units is partially
controlled by other units independently shown to track syntactic structure. We
conclude that LSTMs are, to some extent, implementing genuinely syntactic
processing mechanisms, paving the way to a more general understanding of
grammatical encoding in LSTMs.