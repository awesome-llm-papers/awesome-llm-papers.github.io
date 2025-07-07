---
layout: publication
title: Enabling Robots To Understand Incomplete Natural Language Instructions Using
  Commonsense Reasoning
authors: Haonan Chen, Hao Tan, Alan Kuntz, Mohit Bansal, Ron Alterovitz
conference: Arxiv
year: 2019
citations: 26
bibkey: chen2019enabling
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1904.12907'}]
tags: [RAG, Training Techniques]
---
Enabling robots to understand instructions provided via spoken natural
language would facilitate interaction between robots and people in a variety of
settings in homes and workplaces. However, natural language instructions are
often missing information that would be obvious to a human based on
environmental context and common sense, and hence does not need to be
explicitly stated. In this paper, we introduce Language-Model-based Commonsense
Reasoning (LMCR), a new method which enables a robot to listen to a natural
language instruction from a human, observe the environment around it, and
automatically fill in information missing from the instruction using
environmental context and a new commonsense reasoning approach. Our approach
first converts an instruction provided as unconstrained natural language into a
form that a robot can understand by parsing it into verb frames. Our approach
then fills in missing information in the instruction by observing objects in
its vicinity and leveraging commonsense reasoning. To learn commonsense
reasoning automatically, our approach distills knowledge from large
unstructured textual corpora by training a language model. Our results show the
feasibility of a robot learning commonsense knowledge automatically from
web-based textual corpora, and the power of learned commonsense reasoning
models in enabling a robot to autonomously perform tasks based on incomplete
natural language instructions.