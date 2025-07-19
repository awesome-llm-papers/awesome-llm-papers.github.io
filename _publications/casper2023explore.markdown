---
layout: publication
title: 'Explore, Establish, Exploit: Red Teaming Language Models From Scratch'
authors: Casper et al.
conference: Proceedings of the 2022 Conference on Empirical Methods in Natural Language
  Processing
year: 2023
bibkey: casper2023explore
citations: 98
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2306.09442'}]
tags: [Training Techniques, EMNLP, GPT, Prompting, Tools, Evaluation, Model Architecture,
  Security, Datasets]
---
Deploying large language models (LMs) can pose hazards from harmful outputs
such as toxic or false text. Prior work has introduced automated tools that
elicit harmful outputs to identify these risks. While this is a valuable step
toward securing models, these approaches rely on a pre-existing way to
efficiently classify undesirable outputs. Using a pre-existing classifier does
not allow for red-teaming to be tailored to the target model. Furthermore, when
failures can be easily classified in advance, red-teaming has limited marginal
value because problems can be avoided by simply filtering training data and/or
model outputs. Here, we consider red-teaming "from scratch," in which the
adversary does not begin with a way to classify failures. Our framework
consists of three steps: 1) Exploring the model's range of behaviors in the
desired context; 2) Establishing a definition and measurement for undesired
behavior (e.g., a classifier trained to reflect human evaluations); and 3)
Exploiting the model's flaws using this measure to develop diverse adversarial
prompts. We use this approach to red-team GPT-3 to discover classes of inputs
that elicit false statements. In doing so, we construct the CommonClaim dataset
of 20,000 statements labeled by humans as common-knowledge-true, common
knowledge-false, or neither. We are making code and data available.