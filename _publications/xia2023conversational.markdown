---
layout: publication
title: Conversational Automated Program Repair
authors: Chunqiu Steven Xia, Lingming Zhang
conference: Arxiv
year: 2023
citations: 27
bibkey: xia2023conversational
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2301.13246'}]
tags: [RAG, GPT, Model Architecture, Prompting]
---
Automated Program Repair (APR) can help developers automatically generate
patches for bugs. Due to the impressive performance obtained using Large
Pre-Trained Language Models (LLMs) on many code related tasks, researchers have
started to directly use LLMs for APR. However, prior approaches simply
repeatedly sample the LLM given the same constructed input/prompt created from
the original buggy code, which not only leads to generating the same incorrect
patches repeatedly but also miss the critical information in testcases. To
address these limitations, we propose conversational APR, a new paradigm for
program repair that alternates between patch generation and validation in a
conversational manner. In conversational APR, we iteratively build the input to
the model by combining previously generated patches with validation feedback.
As such, we leverage the long-term context window of LLMs to not only avoid
generating previously incorrect patches but also incorporate validation
feedback to help the model understand the semantic meaning of the program under
test. We evaluate 10 different LLM including the newly developed ChatGPT model
to demonstrate the improvement of conversational APR over the prior LLM for APR
approach.