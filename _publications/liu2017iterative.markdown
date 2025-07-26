---
layout: publication
title: Iterative Policy Learning In End-to-end Trainable Task-oriented Neural Dialog
  Models
authors: Bing Liu, Ian Lane
conference: 2017 IEEE Automatic Speech Recognition and Understanding Workshop (ASRU)
year: 2017
bibkey: liu2017iterative
citations: 97
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1709.06136'}]
tags: ["ASRU", "Reinforcement Learning", "Training Techniques"]
short_authors: Bing Liu, Ian Lane
---
In this paper, we present a deep reinforcement learning (RL) framework for
iterative dialog policy optimization in end-to-end task-oriented dialog
systems. Popular approaches in learning dialog policy with RL include letting a
dialog agent to learn against a user simulator. Building a reliable user
simulator, however, is not trivial, often as difficult as building a good
dialog agent. We address this challenge by jointly optimizing the dialog agent
and the user simulator with deep RL by simulating dialogs between the two
agents. We first bootstrap a basic dialog agent and a basic user simulator by
learning directly from dialog corpora with supervised training. We then improve
them further by letting the two agents to conduct task-oriented dialogs and
iteratively optimizing their policies with deep RL. Both the dialog agent and
the user simulator are designed with neural network models that can be trained
end-to-end. Our experiment results show that the proposed method leads to
promising improvements on task success rate and total task reward comparing to
supervised training and single-agent RL training baseline models.