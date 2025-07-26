---
layout: publication
title: Improving Question Answering Over Incomplete Kbs With Knowledge-aware Reader
authors: Wenhan Xiong, Mo Yu, Shiyu Chang, Xiaoxiao Guo, William Yang Wang
conference: Proceedings of the 57th Annual Meeting of the Association for Computational
  Linguistics
year: 2019
bibkey: xiong2019improving
citations: 118
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1905.07098'}]
tags: ["Evaluation"]
short_authors: Xiong et al.
---
We propose a new end-to-end question answering model, which learns to
aggregate answer evidence from an incomplete knowledge base (KB) and a set of
retrieved text snippets. Under the assumptions that the structured KB is easier
to query and the acquired knowledge can help the understanding of unstructured
text, our model first accumulates knowledge of entities from a question-related
KB subgraph; then reformulates the question in the latent space and reads the
texts with the accumulated entity knowledge at hand. The evidence from KB and
texts are finally aggregated to predict answers. On the widely-used KBQA
benchmark WebQSP, our model achieves consistent improvements across settings
with different extents of KB incompleteness.