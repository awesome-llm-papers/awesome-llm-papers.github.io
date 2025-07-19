---
layout: publication
title: A Dense Reward View On Aligning Text-to-image Diffusion With Preference
authors: Yang Shentao, Chen Tianqi, Zhou Mingyuan
conference: 2023 IEEE/CVF International Conference on Computer Vision (ICCV)
year: 2024
bibkey: yang2024dense
citations: 66
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2402.08265'}]
tags: [ICCV, Attention Mechanism, Prompting, Model Architecture, Efficiency And Optimization,
  Reinforcement Learning, Merging]
---
Aligning text-to-image diffusion model (T2I) with preference has been gaining
increasing research attention. While prior works exist on directly optimizing
T2I by preference data, these methods are developed under the bandit assumption
of a latent reward on the entire diffusion reverse chain, while ignoring the
sequential nature of the generation process. This may harm the efficacy and
efficiency of preference alignment. In this paper, we take on a finer dense
reward perspective and derive a tractable alignment objective that emphasizes
the initial steps of the T2I reverse chain. In particular, we introduce
temporal discounting into DPO-style explicit-reward-free objectives, to break
the temporal symmetry therein and suit the T2I generation hierarchy. In
experiments on single and multiple prompt generation, our method is competitive
with strong relevant baselines, both quantitatively and qualitatively. Further
investigations are conducted to illustrate the insight of our approach.