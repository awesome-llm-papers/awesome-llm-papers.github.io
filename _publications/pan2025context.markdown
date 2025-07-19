---
layout: publication
title: Context Is Not Comprehension
authors: Pan Alex, Williams Mary-anne
conference: Metaphor and Symbolic Activity
year: 2025
bibkey: pan2025context
citations: 204
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2506.04907'}]
tags: [Evaluation, Datasets]
---
The dominant way of judging Large Language Models (LLMs) has been to ask how well they can recall explicit facts from very long inputs. While today's best models achieve near perfect recall, this masks a harder skill: performing multi-step reasoning and tracking intermediate state that never appears verbatim. We introduce Verbose ListOps (VLO), a benchmark that embeds deterministic ListOps computations inside narrative camouflage and, crucially, allows step-level evaluation of every intermediate result. Experiments show that models which solve raw ListOps with approximately 100% accuracy collapse on VLO after only 10,000 tokens. By exposing where a model's reasoning chain first diverges, VLO moves assessment beyond sheer context length and toward genuine comprehension. VLO's generation pipeline is task-agnostic: it can weave any deterministically verifiable reasoning schema -- arithmetic, symbolic, abductive, inductive or defeasible -- into narrative form. This makes VLO a reusable test-bed for the next wave of reasoning-centric model designs, not merely those with step-explicit scaffolds.