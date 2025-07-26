---
layout: publication
title: Encoder-based Domain Tuning For Fast Personalization Of Text-to-image Models
authors: Rinon Gal, Moab Arar, Yuval Atzmon, Amit H. Bermano, Gal Chechik, Daniel
  Cohen-or
conference: ACM Transactions on Graphics
year: 2023
bibkey: gal2023encoder
citations: 92
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2302.12228'}]
tags: ["Training Techniques"]
short_authors: Gal et al.
---
Text-to-image personalization aims to teach a pre-trained diffusion model to
reason about novel, user provided concepts, embedding them into new scenes
guided by natural language prompts. However, current personalization approaches
struggle with lengthy training times, high storage requirements or loss of
identity. To overcome these limitations, we propose an encoder-based
domain-tuning approach. Our key insight is that by underfitting on a large set
of concepts from a given domain, we can improve generalization and create a
model that is more amenable to quickly adding novel concepts from the same
domain. Specifically, we employ two components: First, an encoder that takes as
an input a single image of a target concept from a given domain, e.g. a
specific face, and learns to map it into a word-embedding representing the
concept. Second, a set of regularized weight-offsets for the text-to-image
model that learn how to effectively ingest additional concepts. Together, these
components are used to guide the learning of unseen concepts, allowing us to
personalize a model using only a single image and as few as 5 training steps -
accelerating personalization from dozens of minutes to seconds, while
preserving quality.