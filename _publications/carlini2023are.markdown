---
layout: publication
title: Are Aligned Neural Networks Adversarially Aligned?
authors: Nicholas Carlini et al.
conference: Arxiv
year: 2023
citations: 19
bibkey: carlini2023are
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2306.15447'}]
tags: [Efficiency and Optimization, Security, Multimodal Models]
---
Large language models are now tuned to align with the goals of their
creators, namely to be "helpful and harmless." These models should respond
helpfully to user questions, but refuse to answer requests that could cause
harm. However, adversarial users can construct inputs which circumvent attempts
at alignment. In this work, we study adversarial alignment, and ask to what
extent these models remain aligned when interacting with an adversarial user
who constructs worst-case inputs (adversarial examples). These inputs are
designed to cause the model to emit harmful content that would otherwise be
prohibited. We show that existing NLP-based optimization attacks are
insufficiently powerful to reliably attack aligned text models: even when
current NLP-based attacks fail, we can find adversarial inputs with brute
force. As a result, the failure of current attacks should not be seen as proof
that aligned text models remain aligned under adversarial inputs.
  However the recent trend in large-scale ML models is multimodal models that
allow users to provide images that influence the text that is generated. We
show these models can be easily attacked, i.e., induced to perform arbitrary
un-aligned behavior through adversarial perturbation of the input image. We
conjecture that improved NLP attacks may demonstrate this same level of
adversarial control over text-only models.