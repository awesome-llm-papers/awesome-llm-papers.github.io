---
layout: publication
title: Grounding Language To Autonomously-acquired Skills Via Goal Generation
authors: "Ahmed Akakzia, C\xE9dric Colas, Pierre-yves Oudeyer, Mohamed Chetouani,\
  \ Olivier Sigaud"
conference: Arxiv
year: 2020
citations: 15
bibkey: akakzia2020grounding
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2006.07185'}]
tags: [RAG, Tools, Agentic, Reinforcement Learning, Model Architecture]
---
We are interested in the autonomous acquisition of repertoires of skills.
Language-conditioned reinforcement learning (LC-RL) approaches are great tools
in this quest, as they allow to express abstract goals as sets of constraints
on the states. However, most LC-RL agents are not autonomous and cannot learn
without external instructions and feedback. Besides, their direct language
condition cannot account for the goal-directed behavior of pre-verbal infants
and strongly limits the expression of behavioral diversity for a given language
input. To resolve these issues, we propose a new conceptual approach to
language-conditioned RL: the Language-Goal-Behavior architecture (LGB). LGB
decouples skill learning and language grounding via an intermediate semantic
representation of the world. To showcase the properties of LGB, we present a
specific implementation called DECSTR. DECSTR is an intrinsically motivated
learning agent endowed with an innate semantic representation describing
spatial relations between physical objects. In a first stage (G -> B), it
freely explores its environment and targets self-generated semantic
configurations. In a second stage (L -> G), it trains a language-conditioned
goal generator to generate semantic goals that match the constraints expressed
in language-based inputs. We showcase the additional properties of LGB w.r.t.
both an end-to-end LC-RL approach and a similar approach leveraging
non-semantic, continuous intermediate representations. Intermediate semantic
representations help satisfy language commands in a diversity of ways, enable
strategy switching after a failure and facilitate language grounding.