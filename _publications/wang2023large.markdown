---
layout: publication
title: 'Recmind: Large Language Model Powered Agent For Recommendation'
authors: Yancheng Wang et al.
conference: Arxiv
year: 2023
citations: 24
bibkey: wang2023large
additional_links: [{name: Paper, url: 'http://arxiv.org/abs/2308.14296v3'}]
tags: [RAG, Few-Shot, Tools, Agentic]
---
While the recommendation system (RS) has advanced significantly through deep
learning, current RS approaches usually train and fine-tune models on
task-specific datasets, limiting their generalizability to new recommendation
tasks and their ability to leverage external knowledge due to model scale and
data size constraints. Thus, we designed an LLM-powered autonomous recommender
agent, RecMind, which is capable of leveraging external knowledge, utilizing
tools with careful planning to provide zero-shot personalized recommendations.
We propose a Self-Inspiring algorithm to improve the planning ability. At each
intermediate step, the LLM self-inspires to consider all previously explored
states to plan for the next step. This mechanism greatly improves the model's
ability to comprehend and utilize historical information in planning for
recommendation. We evaluate RecMind's performance in various recommendation
scenarios. Our experiment shows that RecMind outperforms existing zero/few-shot
LLM-based recommendation baseline methods in various tasks and achieves
comparable performance to a fully trained recommendation model P5.