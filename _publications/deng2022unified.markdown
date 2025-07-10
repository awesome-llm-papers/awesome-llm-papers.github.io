---
layout: publication
title: A Unified Multi-task Learning Framework For Multi-goal Conversational Recommender
  Systems
authors: Yang Deng et al.
conference: ACM Transactions on Information Systems
year: 2022
citations: 33
bibkey: deng2022unified
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2204.06923'}]
tags: [RecSys, Tools, Prompting, Evaluation]
---
Recent years witnessed several advances in developing multi-goal
conversational recommender systems (MG-CRS) that can proactively attract users'
interests and naturally lead user-engaged dialogues with multiple
conversational goals and diverse topics. Four tasks are often involved in
MG-CRS, including Goal Planning, Topic Prediction, Item Recommendation, and
Response Generation. Most existing studies address only some of these tasks. To
handle the whole problem of MG-CRS, modularized frameworks are adopted where
each task is tackled independently without considering their interdependencies.
In this work, we propose a novel Unified MultI-goal conversational recommeNDer
system, namely UniMIND. In specific, we unify these four tasks with different
formulations into the same sequence-to-sequence (Seq2Seq) paradigm.
Prompt-based learning strategies are investigated to endow the unified model
with the capability of multi-task learning. Finally, the overall learning and
inference procedure consists of three stages, including multi-task learning,
prompt-based tuning, and inference. Experimental results on two MG-CRS
benchmarks (DuRecDial and TG-ReDial) show that UniMIND achieves
state-of-the-art performance on all tasks with a unified model. Extensive
analyses and discussions are provided for shedding some new perspectives for
MG-CRS.