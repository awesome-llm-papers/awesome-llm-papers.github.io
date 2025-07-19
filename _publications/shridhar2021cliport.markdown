---
layout: publication
title: 'Cliport: What And Where Pathways For Robotic Manipulation'
authors: Shridhar Mohit, Manuelli Lucas, Fox Dieter
conference: Arxiv
year: 2021
bibkey: shridhar2021cliport
citations: 78
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2109.12098'}]
tags: [Training Techniques, Agentic, Tools, Model Architecture, Few Shot, Reinforcement
    Learning]
---
How can we imbue robots with the ability to manipulate objects precisely but
also to reason about them in terms of abstract concepts? Recent works in
manipulation have shown that end-to-end networks can learn dexterous skills
that require precise spatial reasoning, but these methods often fail to
generalize to new goals or quickly learn transferable concepts across tasks. In
parallel, there has been great progress in learning generalizable semantic
representations for vision and language by training on large-scale internet
data, however these representations lack the spatial understanding necessary
for fine-grained manipulation. To this end, we propose a framework that
combines the best of both worlds: a two-stream architecture with semantic and
spatial pathways for vision-based manipulation. Specifically, we present
CLIPort, a language-conditioned imitation-learning agent that combines the
broad semantic understanding (what) of CLIP [1] with the spatial precision
(where) of Transporter [2]. Our end-to-end framework is capable of solving a
variety of language-specified tabletop tasks from packing unseen objects to
folding cloths, all without any explicit representations of object poses,
instance segmentations, memory, symbolic states, or syntactic structures.
Experiments in simulated and real-world settings show that our approach is data
efficient in few-shot settings and generalizes effectively to seen and unseen
semantic concepts. We even learn one multi-task policy for 10 simulated and 9
real-world tasks that is better or comparable to single-task policies.