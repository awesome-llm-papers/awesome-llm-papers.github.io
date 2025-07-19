---
layout: publication
title: 'Embedding-to-prefix: Parameter-efficient Personalization For Pre-trained Large
  Language Models'
authors: Huber et al.
conference: Nature Machine Intelligence
year: 2025
bibkey: huber2025embedding
citations: 417
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2505.17051'}]
tags: [Prompting, Fine Tuning, Training Techniques, LLM for Code, RAG, Datasets]
---
Large language models (LLMs) excel at generating contextually relevant content. However, tailoring these outputs to individual users for effective personalization is a significant challenge. While rich user-specific information often exists as pre-existing user representations, such as embeddings learned from preferences or behaviors, current methods to leverage these for LLM personalization typically require costly fine-tuning or token-heavy prompting. We propose Embedding-to-Prefix (E2P), a parameter-efficient method that injects pre-computed context embeddings into an LLM's hidden representation space through a learned projection to a single soft token prefix. This enables effective personalization while keeping the backbone model frozen and avoiding expensive adaptation techniques. We evaluate E2P across two public datasets and in a production setting: dialogue personalization on Persona-Chat, contextual headline generation on PENS, and large-scale personalization for music and podcast consumption. Results show that E2P preserves contextual signals and achieves strong performance with minimal computational overhead, offering a scalable, efficient solution for contextualizing generative AI systems.