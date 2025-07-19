---
layout: publication
title: What Makes A Maze Look Like A Maze?
authors: Hsu et al.
conference: Communications of the ACM
year: 2024
bibkey: hsu2024what
citations: 100
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2409.08202'}]
tags: [RAG, Tools, Reinforcement Learning, Multimodal Models, Datasets]
---
A unique aspect of human visual understanding is the ability to flexibly
interpret abstract concepts: acquiring lifted rules explaining what they
symbolize, grounding them across familiar and unfamiliar contexts, and making
predictions or reasoning about them. While off-the-shelf vision-language models
excel at making literal interpretations of images (e.g., recognizing object
categories such as tree branches), they still struggle to make sense of such
visual abstractions (e.g., how an arrangement of tree branches may form the
walls of a maze). To address this challenge, we introduce Deep Schema Grounding
(DSG), a framework that leverages explicit structured representations of visual
abstractions for grounding and reasoning. At the core of DSG are
schemas--dependency graph descriptions of abstract concepts that decompose them
into more primitive-level symbols. DSG uses large language models to extract
schemas, then hierarchically grounds concrete to abstract components of the
schema onto images with vision-language models. The grounded schema is used to
augment visual abstraction understanding. We systematically evaluate DSG and
different methods in reasoning on our new Visual Abstractions Dataset, which
consists of diverse, real-world images of abstract concepts and corresponding
question-answer pairs labeled by humans. We show that DSG significantly
improves the abstract visual reasoning performance of vision-language models,
and is a step toward human-aligned understanding of visual abstractions.