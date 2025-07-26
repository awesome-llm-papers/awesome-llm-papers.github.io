---
layout: publication
title: A Hierarchical Latent Variable Encoder-decoder Model For Generating Dialogues
authors: Iulian Vlad Serban, Alessandro Sordoni, Ryan Lowe, Laurent Charlin, Joelle
  Pineau, Aaron Courville, Yoshua Bengio
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2017
bibkey: serban2016hierarchical
citations: 732
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1605.06069'}]
tags: ["AAAI", "Model Architecture"]
short_authors: Serban et al.
---
Sequential data often possesses a hierarchical structure with complex
dependencies between subsequences, such as found between the utterances in a
dialogue. In an effort to model this kind of generative process, we propose a
neural network-based generative architecture, with latent stochastic variables
that span a variable number of time steps. We apply the proposed model to the
task of dialogue response generation and compare it with recent neural network
architectures. We evaluate the model performance through automatic evaluation
metrics and by carrying out a human evaluation. The experiments demonstrate
that our model improves upon recently proposed models and that the latent
variables facilitate the generation of long outputs and maintain the context.