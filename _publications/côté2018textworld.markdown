---
layout: publication
title: 'Textworld: A Learning Environment For Text-based Games'
authors: "Marc-alexandre C\xF4t\xE9, \xC1kos K\xE1d\xE1r, Xingdi Yuan, Ben Kybartas,\
  \ Tavian Barnes, Emery Fine, James Moore, Ruo Yu Tao, Matthew Hausknecht, Layla\
  \ El Asri, Mahmoud Adada, Wendy Tay, Adam Trischler"
conference: Communications in Computer and Information Science
year: 2019
bibkey: "c\xF4t\xE92018textworld"
citations: 138
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1806.11532'}]
tags: ["Tools"]
short_authors: "C\xF4t\xE9 et al."
---
We introduce TextWorld, a sandbox learning environment for the training and
evaluation of RL agents on text-based games. TextWorld is a Python library that
handles interactive play-through of text games, as well as backend functions
like state tracking and reward assignment. It comes with a curated list of
games whose features and challenges we have analyzed. More significantly, it
enables users to handcraft or automatically generate new games. Its generative
mechanisms give precise control over the difficulty, scope, and language of
constructed games, and can be used to relax challenges inherent to commercial
text games like partial observability and sparse rewards. By generating sets of
varied but similar games, TextWorld can also be used to study generalization
and transfer learning. We cast text-based games in the Reinforcement Learning
formalism, use our framework to develop a set of benchmark games, and evaluate
several baseline agents on this set and the curated list.