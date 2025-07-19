---
layout: publication
title: Learning Structure And Knowledge Aware Representation With Large Language Models
  For Concept Recommendation
authors: Li et al.
conference: Proceedings of the ACM Web Conference 2024
year: 2024
bibkey: li2024learning
citations: 69
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2405.12442'}]
tags: [Reinforcement Learning, RAG, Tools, Datasets]
---
Concept recommendation aims to suggest the next concept for learners to study
based on their knowledge states and the human knowledge system. While knowledge
states can be predicted using knowledge tracing models, previous approaches
have not effectively integrated the human knowledge system into the process of
designing these educational models. In the era of rapidly evolving Large
Language Models (LLMs), many fields have begun using LLMs to generate and
encode text, introducing external knowledge. However, integrating LLMs into
concept recommendation presents two urgent challenges: 1) How to construct text
for concepts that effectively incorporate the human knowledge system? 2) How to
adapt non-smooth, anisotropic text encodings effectively for concept
recommendation? In this paper, we propose a novel Structure and Knowledge Aware
Representation learning framework for concept Recommendation (SKarREC). We
leverage factual knowledge from LLMs as well as the precedence and succession
relationships between concepts obtained from the knowledge graph to construct
textual representations of concepts. Furthermore, we propose a graph-based
adapter to adapt anisotropic text embeddings to the concept recommendation
task. This adapter is pre-trained through contrastive learning on the knowledge
graph to get a smooth and structure-aware concept representation. Then, it's
fine-tuned through the recommendation task, forming a
text-to-knowledge-to-recommendation adaptation pipeline, which effectively
constructs a structure and knowledge-aware concept representation. Our method
does a better job than previous adapters in transforming text encodings for
application in concept recommendation. Extensive experiments on real-world
datasets demonstrate the effectiveness of the proposed approach.