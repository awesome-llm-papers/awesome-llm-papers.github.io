---
layout: publication
title: Modelling Non-reinforced Preferences Using Selective Attention
authors: Sajid et al.
conference: Neurocomputing
year: 2022
bibkey: sajid2022modelling
citations: 63
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2207.13699'}]
tags: [RAG, Attention Mechanism, Agentic, Tools, Model Architecture, Reinforcement
    Learning, Fine Tuning]
---
How can artificial agents learn non-reinforced preferences to continuously
adapt their behaviour to a changing environment? We decompose this question
into two challenges: (\\(i\\)) encoding diverse memories and (\\(ii\\)) selectively
attending to these for preference formation. Our proposed
*no*n-*re*inforced preference learning mechanism using selective
attention, \textsc\{Nore\}, addresses both by leveraging the agent's world model
to collect a diverse set of experiences which are interleaved with imagined
roll-outs to encode memories. These memories are selectively attended to, using
attention and gating blocks, to update agent's preferences. We validate
\textsc\{Nore\} in a modified OpenAI Gym FrozenLake environment (without any
external signal) with and without volatility under a fixed model of the
environment -- and compare its behaviour to \textsc\{Pepper\}, a Hebbian
preference learning mechanism. We demonstrate that \textsc\{Nore\} provides a
straightforward framework to induce exploratory preferences in the absence of
external signals.