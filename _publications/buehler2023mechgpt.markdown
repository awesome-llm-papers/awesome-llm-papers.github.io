---
layout: publication
title: Mechgpt, A Language-based Strategy For Mechanics And Materials Modeling That
  Connects Knowledge Across Scales, Disciplines And Modalities
authors: Buehler Markus J.
conference: Applied Mechanics Reviews
year: 2023
bibkey: buehler2023mechgpt
citations: 54
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2310.10445'}]
tags: [RAG, Training Techniques, GPT, Agentic, Tools, Model Architecture, Reinforcement
    Learning, Security, Fine Tuning, Multimodal Models]
---
For centuries, researchers have sought out ways to connect disparate areas of
knowledge. While early scholars (Galileo, da Vinci, etc.) were experts across
fields, specialization has taken hold later. With the advent of Artificial
Intelligence, we can now explore relationships across areas (e.g.,
mechanics-biology) or disparate domains (e.g., failure mechanics-art). To
achieve this, we use a fine-tuned Large Language Model (LLM), here for a subset
of knowledge in multiscale materials failure. The approach includes the use of
a general-purpose LLM to distill question-answer pairs from raw sources
followed by LLM fine-tuning. The resulting MechGPT LLM foundation model is used
in a series of computational experiments to explore its capacity for knowledge
retrieval, various language tasks, hypothesis generation, and connecting
knowledge across disparate areas. While the model has some ability to recall
knowledge from training, we find that LLMs are particularly useful to extract
structural insights through Ontological Knowledge Graphs. These interpretable
graph structures provide explanatory insights, frameworks for new research
questions, and visual representations of knowledge that also can be used in
retrieval-augmented generation. Three versions of MechGPT are discussed,
featuring different sizes from 13 billion to 70 billion parameters, and
reaching context lengths of more than 10,000 tokens. This provides ample
capacity for sophisticated retrieval augmented strategies, as well as
agent-based modeling where multiple LLMs interact collaboratively and/or
adversarially, the incorporation of new data from the literature or web
searches, as well as multimodality.