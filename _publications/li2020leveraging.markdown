---
layout: publication
title: Leveraging Graph To Improve Abstractive Multi-document Summarization
authors: Li et al.
conference: Proceedings of the 58th Annual Meeting of the Association for Computational
  Linguistics
year: 2020
bibkey: li2020leveraging
citations: 106
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2005.10043'}]
tags: [Datasets, Model Architecture, ACL, RAG]
---
Graphs that capture relations between textual units have great benefits for
detecting salient information from multiple documents and generating overall
coherent summaries. In this paper, we develop a neural abstractive
multi-document summarization (MDS) model which can leverage well-known graph
representations of documents such as similarity graph and discourse graph, to
more effectively process multiple input documents and produce abstractive
summaries. Our model utilizes graphs to encode documents in order to capture
cross-document relations, which is crucial to summarizing long documents. Our
model can also take advantage of graphs to guide the summary generation
process, which is beneficial for generating coherent and concise summaries.
Furthermore, pre-trained language models can be easily combined with our model,
which further improve the summarization performance significantly. Empirical
results on the WikiSum and MultiNews dataset show that the proposed
architecture brings substantial improvements over several strong baselines.