---
layout: publication
title: Query-guided Regression Network With Context Policy For Phrase Grounding
authors: Chen Kan, Kovvuri Rama, Nevatia Ram
conference: 2017 IEEE International Conference on Computer Vision (ICCV)
year: 2017
bibkey: chen2017query
citations: 125
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1708.01676'}]
tags: [RAG, ICCV, Agentic, Reinforcement Learning, Datasets]
---
Given a textual description of an image, phrase grounding localizes objects
in the image referred by query phrases in the description. State-of-the-art
methods address the problem by ranking a set of proposals based on the
relevance to each query, which are limited by the performance of independent
proposal generation systems and ignore useful cues from context in the
description. In this paper, we adopt a spatial regression method to break the
performance limit, and introduce reinforcement learning techniques to further
leverage semantic context information. We propose a novel Query-guided
Regression network with Context policy (QRC Net) which jointly learns a
Proposal Generation Network (PGN), a Query-guided Regression Network (QRN) and
a Context Policy Network (CPN). Experiments show QRC Net provides a significant
improvement in accuracy on two popular datasets: Flickr30K Entities and Referit
Game, with 14.25% and 17.14% increase over the state-of-the-arts respectively.