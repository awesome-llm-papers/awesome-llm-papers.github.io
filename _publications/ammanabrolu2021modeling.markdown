---
layout: publication
title: Modeling Worlds In Text
authors: Ammanabrolu Prithviraj, Riedl Mark O.
conference: Arxiv
year: 2021
bibkey: ammanabrolu2021modeling
citations: 77
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2106.09578'}]
tags: [Training Techniques, Agentic, Evaluation, Reinforcement Learning, Datasets]
---
We provide a dataset that enables the creation of learning agents that can
build knowledge graph-based world models of interactive narratives. Interactive
narratives -- or text-adventure games -- are partially observable environments
structured as long puzzles or quests in which an agent perceives and interacts
with the world purely through textual natural language. Each individual game
typically contains hundreds of locations, characters, and objects -- each with
their own unique descriptions -- providing an opportunity to study the problem
of giving language-based agents the structured memory necessary to operate in
such worlds. Our dataset provides 24198 mappings between rich natural language
observations and: (1) knowledge graphs that reflect the world state in the form
of a map; (2) natural language actions that are guaranteed to cause a change in
that particular world state. The training data is collected across 27 games in
multiple genres and contains a further 7836 heldout instances over 9 additional
games in the test set. We further provide baseline models using rules-based,
question-answering, and sequence learning approaches in addition to an analysis
of the data and corresponding learning tasks.