---
layout: publication
title: 'Capacity Matters: A Proof-of-concept For Transformer Memorization On Real-world
  Data'
authors: "Changalidis Anton, H\xE4rm\xE4 Aki"
conference: Trends in Ecology &amp; Evolution
year: 2025
bibkey: changalidis2025capacity
citations: 66
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2506.14704'}]
tags: [Tools, Transformer, Model Architecture, Reinforcement Learning, Datasets]
---
This paper studies how the model architecture and data configurations influence the empirical memorization capacity of generative transformers. The models are trained using synthetic text datasets derived from the Systematized Nomenclature of Medicine (SNOMED) knowledge graph: triplets, representing static connections, and sequences, simulating complex relation patterns. The results show that embedding size is the primary determinant of learning speed and capacity, while additional layers provide limited benefits and may hinder performance on simpler datasets. Activation functions play a crucial role, and Softmax demonstrates greater stability and capacity. Furthermore, increasing the complexity of the data set seems to improve the final memorization. These insights improve our understanding of transformer memory mechanisms and provide a framework for optimizing model design with structured real-world data.