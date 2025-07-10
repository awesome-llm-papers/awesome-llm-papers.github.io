---
layout: publication
title: 'Reshaping Robot Trajectories Using Natural Language Commands: A Study Of Multi-modal
  Data Alignment Using Transformers'
authors: Arthur Bucker et al.
conference: 2022 IEEE/RSJ International Conference on Intelligent Robots and Systems
  (IROS)
year: 2022
citations: 29
bibkey: bucker2022reshaping
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2203.13411'}, {name: Code,
    url: 'https://arthurfenderbucker.github.io/NL_trajectory_reshaper/'}]
tags: [Has Code, Model Architecture, Attention Mechanism, Transformer, Tools, Reinforcement
    Learning, Agentic, BERT]
---
Natural language is the most intuitive medium for us to interact with other
people when expressing commands and instructions. However, using language is
seldom an easy task when humans need to express their intent towards robots,
since most of the current language interfaces require rigid templates with a
static set of action targets and commands. In this work, we provide a flexible
language-based interface for human-robot collaboration, which allows a user to
reshape existing trajectories for an autonomous agent. We take advantage of
recent advancements in the field of large language models (BERT and CLIP) to
encode the user command, and then combine these features with trajectory
information using multi-modal attention transformers. We train the model using
imitation learning over a dataset containing robot trajectories modified by
language commands, and treat the trajectory generation process as a sequence
prediction problem, analogously to how language generation architectures
operate. We evaluate the system in multiple simulated trajectory scenarios, and
show a significant performance increase of our model over baseline approaches.
In addition, our real-world experiments with a robot arm show that users
significantly prefer our natural language interface over traditional methods
such as kinesthetic teaching or cost-function programming. Our study shows how
the field of robotics can take advantage of large pre-trained language models
towards creating more intuitive interfaces between robots and machines. Project
webpage: https://arthurfenderbucker.github.io/NL_trajectory_reshaper/