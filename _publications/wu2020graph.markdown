---
layout: publication
title: Graph Convolution Machine For Context-aware Recommender System
authors: Wu et al.
conference: Frontiers of Computer Science
year: 2020
bibkey: wu2020graph
citations: 66
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2001.11402'}]
tags: [Reinforcement Learning, Tools, Datasets]
---
The latest advance in recommendation shows that better user and item
representations can be learned via performing graph convolutions on the
user-item interaction graph. However, such finding is mostly restricted to the
collaborative filtering (CF) scenario, where the interaction contexts are not
available. In this work, we extend the advantages of graph convolutions to
context-aware recommender system (CARS, which represents a generic type of
models that can handle various side information). We propose \textit\{Graph
Convolution Machine\} (GCM), an end-to-end framework that consists of three
components: an encoder, graph convolution (GC) layers, and a decoder. The
encoder projects users, items, and contexts into embedding vectors, which are
passed to the GC layers that refine user and item embeddings with context-aware
graph convolutions on user-item graph. The decoder digests the refined
embeddings to output the prediction score by considering the interactions among
user, item, and context embeddings. We conduct experiments on three real-world
datasets from Yelp and Amazon, validating the effectiveness of GCM and the
benefits of performing graph convolutions for CARS. Our implementations are
available at https://github.com/wujcan/GCM.