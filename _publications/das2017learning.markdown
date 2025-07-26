---
layout: publication
title: Learning Cooperative Visual Dialog Agents With Deep Reinforcement Learning
authors: "Abhishek Das, Satwik Kottur, Jos\xE9 M. F. Moura, Stefan Lee, Dhruv Batra"
conference: 2017 IEEE International Conference on Computer Vision (ICCV)
year: 2017
bibkey: das2017learning
citations: 327
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1703.06585'}]
tags: ["ICCV", "Reinforcement Learning"]
short_authors: Das et al.
---
We introduce the first goal-driven training for visual question answering and
dialog agents. Specifically, we pose a cooperative 'image guessing' game
between two agents -- Qbot and Abot -- who communicate in natural language
dialog so that Qbot can select an unseen image from a lineup of images. We use
deep reinforcement learning (RL) to learn the policies of these agents
end-to-end -- from pixels to multi-agent multi-round dialog to game reward.
  We demonstrate two experimental results.
  First, as a 'sanity check' demonstration of pure RL (from scratch), we show
results on a synthetic world, where the agents communicate in ungrounded
vocabulary, i.e., symbols with no pre-specified meanings (X, Y, Z). We find
that two bots invent their own communication protocol and start using certain
symbols to ask/answer about certain visual attributes (shape/color/style).
Thus, we demonstrate the emergence of grounded language and communication among
'visual' dialog agents with no human supervision.
  Second, we conduct large-scale real-image experiments on the VisDial dataset,
where we pretrain with supervised dialog data and show that the RL 'fine-tuned'
agents significantly outperform SL agents. Interestingly, the RL Qbot learns to
ask questions that Abot is good at, ultimately resulting in more informative
dialog and a better team.