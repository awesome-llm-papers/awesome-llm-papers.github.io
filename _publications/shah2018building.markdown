---
layout: publication
title: Building A Conversational Agent Overnight With Dialogue Self-play
authors: Pararth Shah et al.
conference: Arxiv
year: 2018
citations: 176
bibkey: shah2018building
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1801.04871'}]
tags: [RAG, Tools, Agentic]
---
We propose Machines Talking To Machines (M2M), a framework combining
automation and crowdsourcing to rapidly bootstrap end-to-end dialogue agents
for goal-oriented dialogues in arbitrary domains. M2M scales to new tasks with
just a task schema and an API client from the dialogue system developer, but it
is also customizable to cater to task-specific interactions. Compared to the
Wizard-of-Oz approach for data collection, M2M achieves greater diversity and
coverage of salient dialogue flows while maintaining the naturalness of
individual utterances. In the first phase, a simulated user bot and a
domain-agnostic system bot converse to exhaustively generate dialogue
"outlines", i.e. sequences of template utterances and their semantic parses. In
the second phase, crowd workers provide contextual rewrites of the dialogues to
make the utterances more natural while preserving their meaning. The entire
process can finish within a few hours. We propose a new corpus of 3,000
dialogues spanning 2 domains collected with M2M, and present comparisons with
popular dialogue datasets on the quality and diversity of the surface forms and
dialogue flows.