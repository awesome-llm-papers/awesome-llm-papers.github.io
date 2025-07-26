---
layout: publication
title: Curiosity-driven Exploration By Self-supervised Prediction
authors: Deepak Pathak, Pulkit Agrawal, Alexei A. Efros, Trevor Darrell
conference: 2017 IEEE Conference on Computer Vision and Pattern Recognition Workshops
  (CVPRW)
year: 2017
bibkey: pathak2017curiosity
citations: 1138
additional_links: [{name: Code, url: 'https://pathak22.github.io/noreward-rl/'}, {
    name: Paper, url: 'https://arxiv.org/abs/1705.05363'}]
tags: ["Agentic", "CVPR", "Reinforcement Learning"]
short_authors: Pathak et al.
---
In many real-world scenarios, rewards extrinsic to the agent are extremely
sparse, or absent altogether. In such cases, curiosity can serve as an
intrinsic reward signal to enable the agent to explore its environment and
learn skills that might be useful later in its life. We formulate curiosity as
the error in an agent's ability to predict the consequence of its own actions
in a visual feature space learned by a self-supervised inverse dynamics model.
Our formulation scales to high-dimensional continuous state spaces like images,
bypasses the difficulties of directly predicting pixels, and, critically,
ignores the aspects of the environment that cannot affect the agent. The
proposed approach is evaluated in two environments: VizDoom and Super Mario
Bros. Three broad settings are investigated: 1) sparse extrinsic reward, where
curiosity allows for far fewer interactions with the environment to reach the
goal; 2) exploration with no extrinsic reward, where curiosity pushes the agent
to explore more efficiently; and 3) generalization to unseen scenarios (e.g.
new levels of the same game) where the knowledge gained from earlier experience
helps the agent explore new places much faster than starting from scratch. Demo
video and code available at https://pathak22.github.io/noreward-rl/