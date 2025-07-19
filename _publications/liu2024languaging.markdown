---
layout: publication
title: On Languaging A Simulation Engine
authors: Liu Han, Li Liantang
conference: Arxiv
year: 2024
bibkey: liu2024languaging
citations: 77
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2402.16482'}]
tags: [RAG, Tools]
---
Language model intelligence is revolutionizing the way we program materials
simulations. However, the diversity of simulation scenarios renders it
challenging to precisely transform human language into a tailored simulator.
Here, using three functionalized types of language model, we propose a
language-to-simulation (Lang2Sim) framework that enables interactive navigation
on languaging a simulation engine, by taking a scenario instance of water
sorption in porous matrices. Unlike line-by-line coding of a target simulator,
the language models interpret each simulator as an assembly of invariant tool
function and its variant input-output pair. Lang2Sim enables the precise
transform of textual description by functionalizing and sequentializing the
language models of, respectively, rationalizing the tool categorization,
customizing its input-output combinations, and distilling the simulator input
into executable format. Importantly, depending on its functionalized type, each
language model features a distinct processing of chat history to best balance
its memory limit and information completeness, thus leveraging the model
intelligence to unstructured nature of human request. Overall, this work
establishes language model as an intelligent platform to unlock the era of
languaging a simulation engine.