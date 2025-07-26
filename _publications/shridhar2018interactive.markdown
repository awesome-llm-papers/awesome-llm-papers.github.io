---
layout: publication
title: Interactive Visual Grounding Of Referring Expressions For Human-robot Interaction
authors: Mohit Shridhar, David Hsu
conference: 'Robotics: Science and Systems XIV'
year: 2018
bibkey: shridhar2018interactive
citations: 116
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1806.03831'}]
tags: ["Datasets"]
short_authors: Mohit Shridhar, David Hsu
---
This paper presents INGRESS, a robot system that follows human natural
language instructions to pick and place everyday objects. The core issue here
is the grounding of referring expressions: infer objects and their
relationships from input images and language expressions. INGRESS allows for
unconstrained object categories and unconstrained language expressions.
Further, it asks questions to disambiguate referring expressions interactively.
To achieve these, we take the approach of grounding by generation and propose a
two-stage neural network model for grounding. The first stage uses a neural
network to generate visual descriptions of objects, compares them with the
input language expression, and identifies a set of candidate objects. The
second stage uses another neural network to examine all pairwise relations
between the candidates and infers the most likely referred object. The same
neural networks are used for both grounding and question generation for
disambiguation. Experiments show that INGRESS outperformed a state-of-the-art
method on the RefCOCO dataset and in robot experiments with humans.