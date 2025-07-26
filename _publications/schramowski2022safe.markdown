---
layout: publication
title: 'Safe Latent Diffusion: Mitigating Inappropriate Degeneration In Diffusion
  Models'
authors: "Patrick Schramowski, Manuel Brack, Bj\xF6rn Deiseroth, Kristian Kersting"
conference: 2023 IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
year: 2023
bibkey: schramowski2022safe
citations: 73
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2211.05105'}]
tags: ["CVPR"]
short_authors: Schramowski et al.
---
Text-conditioned image generation models have recently achieved astonishing
results in image quality and text alignment and are consequently employed in a
fast-growing number of applications. Since they are highly data-driven, relying
on billion-sized datasets randomly scraped from the internet, they also suffer,
as we demonstrate, from degenerated and biased human behavior. In turn, they
may even reinforce such biases. To help combat these undesired side effects, we
present safe latent diffusion (SLD). Specifically, to measure the inappropriate
degeneration due to unfiltered and imbalanced training sets, we establish a
novel image generation test bed-inappropriate image prompts (I2P)-containing
dedicated, real-world image-to-text prompts covering concepts such as nudity
and violence. As our exhaustive empirical evaluation demonstrates, the
introduced SLD removes and suppresses inappropriate image parts during the
diffusion process, with no additional training required and no adverse effect
on overall image quality or text alignment.