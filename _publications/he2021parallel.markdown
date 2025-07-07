---
layout: publication
title: Parallel Refinements For Lexically Constrained Text Generation With BART
authors: Xingwei He
conference: Arxiv
year: 2021
citations: 19
bibkey: he2021parallel
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2109.12487'}]
tags: [RAG, Language Modeling]
---
Lexically constrained text generation aims to control the generated text by
incorporating some pre-specified keywords into the output. Previous work
injects lexical constraints into the output by controlling the decoding process
or refining the candidate output iteratively, which tends to generate generic
or ungrammatical sentences, and has high computational complexity. To address
these challenges, we propose Constrained BART (CBART) for lexically constrained
text generation. CBART leverages the pre-trained model BART and transfers part
of the generation burden from the decoder to the encoder by decomposing this
task into two sub-tasks, thereby improving the sentence quality. Concretely, we
extend BART by adding a token-level classifier over the encoder, aiming at
instructing the decoder where to replace and insert. Guided by the encoder, the
decoder refines multiple tokens of the input in one step by inserting tokens
before specific positions and re-predicting tokens with low confidence. To
further reduce the inference latency, the decoder predicts all tokens in
parallel. Experiment results on One-Billion-Word and Yelp show that CBART can
generate plausible text with high quality and diversity while significantly
accelerating inference.