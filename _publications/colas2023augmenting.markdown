---
layout: publication
title: Augmenting Autotelic Agents With Large Language Models
authors: Colas et al.
conference: Nature Machine Intelligence
year: 2023
bibkey: colas2023augmenting
citations: 182
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2305.12487'}]
tags: [Model Architecture, Fine Tuning, Agentic, LLM for Code, RAG, Reinforcement
    Learning]
---
Humans learn to master open-ended repertoires of skills by imagining and
practicing their own goals. This autotelic learning process, literally the
pursuit of self-generated (auto) goals (telos), becomes more and more
open-ended as the goals become more diverse, abstract and creative. The
resulting exploration of the space of possible skills is supported by an
inter-individual exploration: goal representations are culturally evolved and
transmitted across individuals, in particular using language. Current
artificial agents mostly rely on predefined goal representations corresponding
to goal spaces that are either bounded (e.g. list of instructions), or
unbounded (e.g. the space of possible visual inputs) but are rarely endowed
with the ability to reshape their goal representations, to form new
abstractions or to imagine creative goals. In this paper, we introduce a
language model augmented autotelic agent (LMA3) that leverages a pretrained
language model (LM) to support the representation, generation and learning of
diverse, abstract, human-relevant goals. The LM is used as an imperfect model
of human cultural transmission; an attempt to capture aspects of humans'
common-sense, intuitive physics and overall interests. Specifically, it
supports three key components of the autotelic architecture: 1)~a relabeler
that describes the goals achieved in the agent's trajectories, 2)~a goal
generator that suggests new high-level goals along with their decomposition
into subgoals the agent already masters, and 3)~reward functions for each of
these goals. Without relying on any hand-coded goal representations, reward
functions or curriculum, we show that LMA3 agents learn to master a large
diversity of skills in a task-agnostic text-based environment.