---
layout: publication
title: 'Diffusion Forcing: Next-token Prediction Meets Full-sequence Diffusion'
authors: Boyuan Chen, Diego Marti Monso, Yilun Du, Max Simchowitz, Russ Tedrake, Vincent
  Sitzmann
conference: No Venue
year: 2024
bibkey: chen2024diffusion
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2407.01392'}]
tags: ["Model Architecture", "Training Techniques"]
short_authors: Chen et al.
---
This paper presents Diffusion Forcing, a new training paradigm where a diffusion model is trained to denoise a set of tokens with independent per-token noise levels. We apply Diffusion Forcing to sequence generative modeling by training a causal next-token prediction model to generate one or several future tokens without fully diffusing past ones. Our approach is shown to combine the strengths of next-token prediction models, such as variable-length generation, with the strengths of full-sequence diffusion models, such as the ability to guide sampling to desirable trajectories. Our method offers a range of additional capabilities, such as (1) rolling-out sequences of continuous tokens, such as video, with lengths past the training horizon, where baselines diverge and (2) new sampling and guiding schemes that uniquely profit from Diffusion Forcing's variable-horizon and causal architecture, and which lead to marked performance gains in decision-making and planning tasks. In addition to its empirical success, our method is proven to optimize a variational lower bound on the likelihoods of all subsequences of tokens drawn from the true joint distribution. Project website: https://boyuan.space/diffusion-forcing/

https://huggingface.co/discussions/paper/6686505eb9a71fa518adad83