---
layout: publication
title: 'Dialfred: Dialogue-enabled Agents For Embodied Instruction Following'
authors: Xiaofeng Gao et al.
conference: IEEE Robotics and Automation Letters
year: 2022
citations: 15
bibkey: gao2022dialogue
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2202.13330'}]
tags: [RAG, ACL, Tools, Reinforcement Learning, Agentic, Evaluation]
---
Language-guided Embodied AI benchmarks requiring an agent to navigate an
environment and manipulate objects typically allow one-way communication: the
human user gives a natural language command to the agent, and the agent can
only follow the command passively. We present DialFRED, a dialogue-enabled
embodied instruction following benchmark based on the ALFRED benchmark.
DialFRED allows an agent to actively ask questions to the human user; the
additional information in the user's response is used by the agent to better
complete its task. We release a human-annotated dataset with 53K task-relevant
questions and answers and an oracle to answer questions. To solve DialFRED, we
propose a questioner-performer framework wherein the questioner is pre-trained
with the human-annotated data and fine-tuned with reinforcement learning. We
make DialFRED publicly available and encourage researchers to propose and
evaluate their solutions to building dialog-enabled embodied agents.