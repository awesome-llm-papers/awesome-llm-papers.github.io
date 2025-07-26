---
layout: publication
title: Long Text Generation Via Adversarial Training With Leaked Information
authors: Jiaxian Guo, Sidi Lu, Han Cai, Weinan Zhang, Yong Yu, Jun Wang
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2018
bibkey: guo2017long
citations: 419
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1709.08624'}]
tags: ["AAAI", "Applications", "Tools", "Training Techniques"]
short_authors: Guo et al.
---
Automatically generating coherent and semantically meaningful text has many
applications in machine translation, dialogue systems, image captioning, etc.
Recently, by combining with policy gradient, Generative Adversarial Nets (GAN)
that use a discriminative model to guide the training of the generative model
as a reinforcement learning policy has shown promising results in text
generation. However, the scalar guiding signal is only available after the
entire text has been generated and lacks intermediate information about text
structure during the generative process. As such, it limits its success when
the length of the generated text samples is long (more than 20 words). In this
paper, we propose a new framework, called LeakGAN, to address the problem for
long text generation. We allow the discriminative net to leak its own
high-level extracted features to the generative net to further help the
guidance. The generator incorporates such informative signals into all
generation steps through an additional Manager module, which takes the
extracted features of current generated words and outputs a latent vector to
guide the Worker module for next-word generation. Our extensive experiments on
synthetic data and various real-world tasks with Turing test demonstrate that
LeakGAN is highly effective in long text generation and also improves the
performance in short text generation scenarios. More importantly, without any
supervision, LeakGAN would be able to implicitly learn sentence structures only
through the interaction between Manager and Worker.