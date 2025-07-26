---
layout: publication
title: FLUX That Plays Music
authors: Zhengcong Fei, Mingyuan Fan, Changqian Yu, Junshi Huang
conference: No Venue
year: 2024
bibkey: fei2024flux
additional_links: [{name: Code, url: 'https://github.com/black-forest-labs/flux'},
  {name: Code, url: 'https://github.com/feizc/FluxMusic'}, {name: Code, url: 'https://huggingface.co/discussions/paper/66d7fd92a5098dc770352e12'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2409.00587'}]
tags: ["Evaluation", "Has Code", "Model Architecture", "Training Techniques"]
short_authors: Fei et al.
---
This paper explores a simple extension of diffusion-based rectified flow Transformers for text-to-music generation, termed as FluxMusic. Generally, along with design in advanced Fluxhttps://github.com/black-forest-labs/flux model, we transfers it into a latent VAE space of mel-spectrum. It involves first applying a sequence of independent attention to the double text-music stream, followed by a stacked single music stream for denoised patch prediction. We employ multiple pre-trained text encoders to sufficiently capture caption semantic information as well as inference flexibility. In between, coarse textual information, in conjunction with time step embeddings, is utilized in a modulation mechanism, while fine-grained textual details are concatenated with the music patch sequence as inputs. Through an in-depth study, we demonstrate that rectified flow training with an optimized architecture significantly outperforms established diffusion methods for the text-to-music task, as evidenced by various automatic metrics and human preference evaluations. Our experimental data, code, and model weights are made publicly available at: https://github.com/feizc/FluxMusic.

https://huggingface.co/discussions/paper/66d7fd92a5098dc770352e12